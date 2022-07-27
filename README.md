# image_upload_go
A simple API to test image upload. Built on golang

Run using
`go run main.go`

Upload url:
127.0.0.1:8080/upload
Parameters: image as multipart request, key file
Returns: image location 

Download url:
127.0.0.1:8080/image/path={image_path returned from above request}

