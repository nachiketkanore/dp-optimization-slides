# DP Optimization Slides for a YouTube tutorial
![image](https://user-images.githubusercontent.com/44920607/225094358-17b0e64f-93ae-4251-b81a-238af11983bb.png)

## Commands

Now you are ready to view the presentation! To start the slide show:

- Type `npm install` to install the project's dependencies
- Type `npm run dev` to start a local development server
- Visit http://localhost:3030 to view the slides
- Visit http://localhost:3030/presenter to view the slides in presenter mode

The slide show also features other building and development options:

- Typing `npm run remote` will run an additional server supporting remote access
  to your laptop. Please see the diagnostic output for the correct address for
  the server.
- Typing `npm run build` will create a production version of the presentation in
  the form of static HTML
- Typing `npm run export` will create a PDF of the presentation.

Please note that, depending on your version of Playwright, the formatting of the
PDF-based presentation created by `npm run export` may vary slightly from the
version created by either the `npm run dev`, `npm run remote`, or `npm run
build` commands.

## Modifying or Adding Slides

You can edit the [slides.md](./slides.md) in a text editor. If you have a
development server running, then it will notice these changes and regenerate the
web sited and automatically reload your browser, allowing you to to see the
changes. You can learn more about Slidev by visiting its [web
site](https://sli.dev/).
