---  
order: 800  
label: 404 Page  
icon: archive  
---

# 404 Error Page Configuration

A **404 Page** (also known as "Page Not Found") is a standard web page displayed when a user attempts to access a URL that doesn't exist or has been moved. It indicates that the server is reachable, but the specific resource cannot be found.

Below is a complete sample code for your custom 404 page. You can copy and paste it into your `404.html` file (or the filename your hosting provider requires) within your project directory.

## Sample 404 Page Code

Here is the full code for your 404 error page:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>404 - Page Not Found</title>

    <!-- favicon.ico - Feel free to change it or upload your favicon.ico and change it to href="favicon.ico" -->
    <link rel="icon" href="https://profilie.github.io/favicon.ico" type="image/x-icon" />
    
    <!-- Styles
    You can customize your style, currently there are 4 styles available in total.
    Uncomment your desired themes below and don't forget to comment on others. 
    Only one theme can be used at a time otherwise it will cause problems.
    -->
    <!-- <link rel="stylesheet" href="//cdn.harys.is-a.dev/profilie/lib/themes/mint.css"> -->
    <!-- <link rel="stylesheet" href="//cdn.harys.is-a.dev/profilie/lib/themes/maple.css"> -->
    <!-- <link rel="stylesheet" href="//cdn.harys.is-a.dev/profilie/lib/themes/azure.css"> -->
    <link rel="stylesheet" href="//cdn.harys.is-a.dev/profilie/lib/themes/sapphire.css">
</head>
<body>
    <canvas id="particles-canvas"></canvas>
    
    <div class="info-box">
        <h1 class="title">404 - Page Not Found</h1>
        <p class="details">Profilie very hard to locate the page you were looking for, but he couldn't find it. Profilie is an awesome sysadmin. If he couldn't find it, it's probably not there.
            <br />
            <br />
            <i>The page you’re looking for doesn’t exist.</i></p>
        <a href="/" class="home-button">Back to Home</a>
    </div>

    <script src="//cdn.harys.is-a.dev/profilie/lib/profilie.min.js"></script>
</body>
</html>
```

!!!base Note
Feel free to customize the page title or error message. **Do not** modify anything else, as changes outside of these areas may cause the page to malfunction.
!!!

## Support

Need help or have questions? Feel free to open an issue or participate in discussions on our [**GitHub Repository**](https://github.com/profilie/profilie/).
