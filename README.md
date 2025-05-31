# YourIndiaHolidays.com Client Questionnaire

This is a web form that collects client responses for building the YourIndiaHolidays.com tourism website. The form sends responses to a Discord webhook for easy tracking.

## Features

- Complete questionnaire covering all aspects of website development
- Mobile-responsive design
- Form validation
- Sends responses directly to a Discord channel via webhook
- Easy to deploy on GitHub Pages

## Setup Instructions

1. Fork this repository to your GitHub account
2. Go to your forked repository's Settings
3. Navigate to the "Pages" section in the sidebar
4. Under "Source", select "Deploy from a branch"
5. Select the "main" branch and "/" (root) folder
6. Click "Save"
7. Wait a few minutes for GitHub to build and deploy the site
8. Your form will be available at `https://[your-username].github.io/[repository-name]/`

## Webhook Configuration

The Discord webhook URL is already configured in the `script.js` file. If you want to change where form responses are sent, update the `webhookUrl` constant in `script.js` with your own Discord webhook URL.

## Customization

You can customize the form's appearance by modifying the `styles.css` file. The form structure can be edited in `index.html`, and form handling logic is in `script.js`.

## Testing

Before sharing the form with clients, test it by filling out the form and checking that responses are received in your Discord channel.

## License

This project is free to use for YourIndiaHolidays.com client questionnaire purposes. 