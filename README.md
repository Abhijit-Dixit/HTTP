# HTTP

### Body type of a POST Request

* RAW - Used for sending JSON/ string data
* BINARY - image, audio, videos
* URL_ENCODED - allows sending data in key-value based form
* FORM_DATA - in addition to URL_ENCODED it allows sending files


An HTTP method is idempotent if an identical request can be made once or several times in a row with the same effect while leaving the server in the same state. In other words, an idempotent method should not have any side-effects (except for keeping statistics). Implemented correctly, the GET, HEAD, PUT, and DELETE methods are idempotent, but not the POST method. Thus if your operation is non-idempotent use POST.

