# ASSIGNMENT WEEK 2
##  Create Static website on AWS S3

Here's how I hosted a static website on an AWS S3 bucket:

**Step 1**: I created a bucket and named it, setting it up with default configurations.

**Step 2**: In the bucket properties, I enabled Static website hosting and designated "index.html" as the index document. I kept the other settings as default. However, when I attempted to view my website, it displayed an "access denied" message.

**Step 3**: To resolve this, I navigated to the bucket permissions and removed the block on public access, then saved the changes.

**Step 4**: Next, I configured the bucket policy by creating a script that allowed all content within the bucket to be publicly accessible.

**Step 5**: Finally, I uploaded my simple .html file to the bucket objects.

`My static website created on AWS S3 bucket`

<img alt="Alt text" src="/awssca-week2/web1.JPG">

`Screenshot of my website`

<img alt="Alt text" src="/awssca-week2/web2.JPG">

Here is the link to my static website hosted on AWS S3 bucket

[mywebsite](http://sandra-staticwebsite.s3-website-us-east-1.amazonaws.com)
