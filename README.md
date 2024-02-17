# MailGaurd
YOUR ULTIMATE SHIELD AGAINST UNWANTED EMAILS!

## Why MailGaurd?

MailGaurd converts email addresses into images, making them unreadable by email scraping bots or automated programs used by spammers and marketing agencies. This helps in protecting email addresses from being harvested and used for spam or marketing purposes.

[Visit Project:](https://mailgaurd.com)

### MailGaurd API Documentation

The MailGaurd API allows you to dynamically generate images with customizable text and parameters.

#### Example URL

https://mailgaurd.com/protect?id=51603908&color=1763e9&size=42&y=-30

https://mailgaurd.com/protect?text=hello@MailGaurd.com&color=ffffff&bg=1763e9&size=42&y=-30

https://mailgaurd.com/protect?text=hello@MailGaurd.com&font=Roboto&color=ffffff&bg=1763e9&size=42&x=-4&y=-25&p=5

#### Example URL Output

Example with Transparent Background
![MailGaurd Email](https://mailgaurd.com/protect?id=51603908&color=1763e9&size=42&y=-30)

Example with Background Color
![MailGaurd Email](https://mailgaurd.com/protect?text=hello@MailGaurd.com&color=ffffff&bg=000000&size=42&y=-30)

Example with Google Font
![MailGaurd Email](https://mailgaurd.com/protect?text=hello@MailGaurd.com&color=ffffff&bg=000000&size=42&y=-30)


## Parameters

| Parameter | Description |
|-----------|-------------|
| output    | Output file type. Supported types: png, svg, jpg, jpeg. |
| quality   | Image quality for JPEG output. Integer between 1 and 100. |
| id        | ID of the email. If provided, fetches email address from the database. |
| text      | Text to be displayed on the image. Default: MailGaurd. |
| font      | Google font name, case sensitive space replaced with +. |
| size      | Font size in points. |
| width     | Image width in pixels. |
| height    | Image height in pixels. |
| weight    | Font weight. Default: default. Valid values: 100, 200, 300, 400, 500, 600, 700, 800. |
| bg        | Background color in hexadecimal format. Default: transparent. |
| color     | Text color in hexadecimal format. Default: #000000 (black). |
| x         | Horizontal padding of text in pixels. |
| y         | Vertical padding of text in pixels. |
| p         | Shortcut for setting both x and y padding. |
| px        | Horizontal padding in pixels. Overrides x. |
| py        | Vertical padding in pixels. Overrides y. |


## Spam Filtering

Our intelligent spam filtering technology efficiently detects and filters out unwanted spam emails, keeping your inbox clutter-free.

## Phishing Protection

MailGuard's sophisticated phishing protection system identifies and blocks phishing attempts, protecting you from fraudulent emails that aim to steal sensitive information.

## Customizable Settings

Tailor MailGuard's settings to suit your specific needs and preferences. Customize filtering rules, blacklists, whitelists, and more to enhance your email security.

## No Password

Enjoy hassle-free access to MailGuard's protection features with our no password access link option. Simply use your email address to generate a unique ID for easy and secure access.

## Image Generation API

Seamlessly integrate MailGuard's image generation API into your applications to dynamically create protected images with customizable text and styles. Our API supports various image formats, including PNG, JPEG, and SVG.

## Font Flexibility

Choose from a wide range of fonts, including custom fonts and Google Fonts, to personalize your protected images.

# Sponsor Project

MailGaurd is a free project dedicated to providing robust email protection against spam. Your sponsorship plays a crucial role in helping us maintain and improve MailGaurd, ensuring that it remains a reliable and effective solution for users worldwide.

[PayPal:](https://www.paypal.com/paypalme/paypulse)
[BuyMeCoffee](https://www.buymeacoffee.com/dearmosin)