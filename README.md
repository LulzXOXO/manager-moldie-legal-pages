# Manager Moldie Legal Pages

This project contains the Privacy Policy and Terms of Service web pages for Manager Moldie, a Discord clan management bot. These pages can be used for Discord app verification.

## Bot Information

- **Bot Name**: Manager Moldie
- **Bot URL**: [Add to Discord](https://discord.com/oauth2/authorize?client_id=1356260560626516009)
- **Description**: A Discord clan management bot with a nature/fantasy theme

## Files Included

- `index.html` - Home page with links to the legal pages
- `privacy-policy.html` - Privacy Policy for Manager Moldie
- `terms-of-service.html` - Terms of Service for Manager Moldie
- `images/` - Directory containing the bot mascot and village background images
- `server.js` - Simple Node.js server to host the pages locally
- `404.html` - Custom 404 error page
- `add-images.html` - Helper tool to add your custom images

## How to Use

1. **Run the local server:**
   ```
   python3 -m http.server 3000
   ```

2. **Access the pages:**
   - Home: http://localhost:3000/
   - Privacy Policy: http://localhost:3000/privacy-policy.html
   - Terms of Service: http://localhost:3000/terms-of-service.html

3. **For Discord Verification:**
   - Host these pages on a public web server
   - Use the URLs to the privacy policy and terms of service pages during your Discord bot verification process

## Adding Your Images

The site is designed to use two main images:

1. **Bot Mascot Image** (`bot-mascot.jpg`):
   - This should be an image of Manager Moldie's mascot or logo
   - Save your image as `bot-mascot.jpg` in the `images/` directory
   - This image appears in the header of all pages and as a floating mascot in the corner

2. **Village Background Image** (`village-background.jpg`):
   - This is used as a background image for all pages
   - Save your image as `village-background.jpg` in the `images/` directory

### Image Placement Instructions:

1. Save your images in the `images/` directory with the exact filenames:
   - `bot-mascot.jpg` - For your wolf/fox character with mining helmet
   - `village-background.jpg` - For your village with windmill scene

2. The site is already configured to use these images in the correct places.

## GitHub Pages Deployment

To deploy this site to GitHub Pages:

1. Push this repository to your GitHub account
2. Go to the repository settings
3. Navigate to the "Pages" section
4. Select the main branch as the source
5. Your site will be published at `https://[your-username].github.io/[repo-name]/`

## Customization

- Edit the HTML files to update the content with your specific bot information
- Update your contact information in both legal pages
- Modify the color scheme in the CSS section of each HTML file if desired:
  ```css
  :root {
      --primary-color: #8BC34A;  /* Light green */
      --secondary-color: #4E6E39; /* Dark green */
      --accent-color: #FFB74D;   /* Orange/gold */
      /* Other colors... */
  }
  ```

## Created By

Created by [Lulz](https://github.com/LulzXOXO)
