# Setting up Content Previews

This is a demo app for the **Setting Up Content Previews** course on our Learning Center.

# Requirements

 - Node JS
 - Contentful API keys



# Step 1

Create an empty space in Contentful and note the API keys(delivery, preview and management).
From the Contentful web app go to  Space settings --> API keys....


# Step 2
Open project location and run "npm install" from your terminal.

# Step 3
After installing the dependencies run the "npm setup" command to configure the app.
type in the keys at the prompt. 
![enter image description here](https://lh3.googleusercontent.com/keep-bbsk/AGk0z-MLyXB-1klQHrwyad3K7M3-VoyqLBkYbo6FtSs-1D-13DoZmZ2oaFcou9Z5bPfjUhN2S2Aja2nUlX03Ycmeb9nNUpO6AmZIHvQ7srE=s587)


# Step 4
Run the app with "npm run dev".

# Step 5
Open the link **[http://localhost:9009/](http://localhost:9009/)”** on your browser.

# Step 6
Setup preview on the Contentful web app, your preview URl should be a combination of your app's URL and your preview secret(from step 3) for example; [http://localhost:9009/api/preview?secret=testing&slug={entry.fields.slug](http://localhost:9009/api/preview?secret=testing&slug=%7Bentry.fields.slug)}

Go to the Contentful Webapp --> space settings --> content preview.

Setup preview for the Post content model and use a url like the below;

[http://localhost:9009/api/preview?secret=](http://localhost:9009/api/preview?secret=your)your-preview-secret&slug={entry.fields.slug}

**![](https://lh5.googleusercontent.com/pteeUdPY97uJGVZvIPbvWGnC48YZvb0CfE3g0EI4mAsQ4_trTLuqpQWA86yLGnDym9wnp526UT77fFu6w-SfJYA2SHto_umHh53M00BDI2eMk_j4c9NMc8hWjY2eJjxQfnYHJHRY=s0)**



