# Multiuser weblink store
Back-end API/Services for a basic URL web page archiver I've been working on, to practice more with Docker, Kafka &amp; databases. Multiple clients can consume the API to store text snippets or webpages using custom or auto-generated ids

Currently the service allows clients to paste a text snippet or the content from a given URL temporarily along with an id. If the id is unique, the API will store the associated content with the id, allowing the user to access it until the expiration time. In the case of pasting content from a URL though, the client may instead recieve a status message if the service is still (or has failed) processing the upload request. 
