# Example Blogger API V3 code using javascript and OAuth to create future dated posts

## The problem

With the new Blogger GUI, future dated posts are 'scheduled', not 'published'

## The Solution

Use the API to move the posts into the past when it can be published, then move it back to the future :)

## The Demo

Before you start. Do you need OAuth? Yes if you are using any non-public API calls.

Follow the loose instructions on the Blogger API V3 page to sign up for a Google Cloud Account. Create a project. Add Blogger API V3 to it, Create an API_KEY and a CLIENT_ID

Now, look at the code. You'll need to edit the stuff at the top.

Then open the page in your browser.

You'll need to edit the URL line (this example was taken from something specific)

```oauth-blogger.html?post_id=123456789&date=2030-08-07T09:18:00.000+01:00```

Hope this helps

Andrew
