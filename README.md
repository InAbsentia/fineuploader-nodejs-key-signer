# Fine Uploader Node.js S3 Signing Server

This Express server signs S3 uploads from Fine Uploader, as described in the
[Fine Uploader S3 documentation](http://blog.fineuploader.com/2013/08/16/fine-uploader-s3-upload-directly-to-amazon-s3-from-your-browser/#server-side-integration)

To create this server, I copied and updated their
[example server file](https://github.com/FineUploader/server-examples/tree/master/nodejs/s3).

To run locally in development:

1.  Clone this repo.
1.  Run `npm install` to get the necessary dependencies.
1.  Copy the `.env.sample` file to `.env` and change the required values.
1.  Run `npm start`

You will now have a server running at `localhost:8000`, ready to sign requests.

This server is also ready to deploy to Heroku, as long as the required
environment variables are set on your dyno.
