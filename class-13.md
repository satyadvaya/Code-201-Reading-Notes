# External Article
## _The Past, Present, & Future of Local Storage for Web Applications_
- **HTML5 Storage** provides a way for web pages to store named key/value pairs locally within the client web browser.
    - Data is stored and retrieved based on a named key, and stored as a string.
- Like other JavaScript objects, the `localStorage` object can be treated as an associative array.
- To programmatically track when the storage area changes you can trap the storage event.
- The storage event is supported everywhere the `localStorage` object is supported.
    - You'll need to check which event mechanism the browser supports in order to hook the storage event.
- The storage event cannot be canceled.
    - It's not possible to a change event from occurring from within the `handle_storage` callback function.
- Each origin gets 5MB of storage space by default.
    - Remember that you're storing strings rather than data in its original format.  _If you are storing something other than a string, you'll need to coerce it yourself when you retrieve it._
