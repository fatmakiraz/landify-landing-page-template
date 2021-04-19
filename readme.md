# Landify Landing Page Template

This Landing Page is a one-page responsive website template which has been created mobile-first design. BEM methodology has been used as a CSS naming method. The sections of the template are as follows: 

**Sections**
- Hero
- Logos of brands with slider
- Features 
- Testimonials
- Achievement counters
- Content areas,
- Call to action sections

## [Demo website](https://landify-landing-page-template.vercel.app/)

# Project Structure

css/main.css file is created from main.scss file which is inside the scss folder. 
main.scss file is used to import the other scss files. CSS codes of the index page are included in the scss/pages and scss/components folders.

LiquidJS is used as a template engine.
Files of the template are in the views folder.

## Installation

```bash
git clone https://github.com/hey-fk/landify-landing-page-template
cd landify-landing-page-template
npm install or yarn install
```

## Start the server

```bash
gulp
```

Now enter [`localhost:3000`](http://localhost:3000) in the address bar of your browser.

## Dist Folder

```bash
gulp dist
```

Production files will be prepared in /dist folder.

## Deploy Vercel

Build Command
```bash
gulp dist
```

Output Directory
```bash
dist
```

## Contributing

Did you found a bug or got an idea for a new feature? Feel free to use the [issue tracker](https://github.com/hey-fk/landify-landing-page-template/issues) to let me know. Or make directly a [pull request](https://github.com/hey-fk/landify-landing-page-template/pulls).

## Credits

Design: [Landify - Landing Page UI Kit by Aravind Little Jack](https://www.figma.com/community/file/894552273937682724)

## License

This template is released under the MIT License.