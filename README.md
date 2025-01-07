# 💮 Magnolia

<div align="center">
	<img src="./images/final.png" alt="Screenshot of the homepage" width="600"/>
</div>

First of all, this is a website that I made for a charity project called **88224**. The project is a website that helps my teammate to fill in the Google Form faster with a good looking design that match the main theme of the entire campaign. The website is made with the most basic things like HTML, CSS, and JavaScript, and it's hosted on GitHub Pages.

## Getting Started

### 1. Online access:

You can access the website at [https://haolamnm.is-a.dev/magnolia/](https://haolamnm.is-a.dev/magnolia/). Feel free to input any information you want, the project has ended and for now it's just a dummy form. You can also use the web development tools to inspect the website and see how it works.

### 2. Local setup:

1. Folk the repository.

2. Clone the repository to your local computer.

```bash
git clone https://github.com/haolamnm/magnolia.git
```

## Technical Stack

1. **HTML:** The structure of the website is built using HTML.
2. **CSS:** The styling and animation of the website is done using CSS.
3. **JavaScript:** Some helper functions.

## For Developers

This is quite easy to do, but it take me some time to google and figure out how to do it. So I think it's good to share a little bit about how to make a website that can submit data to Google Form.

### 1. Form tag

```html
<form action="your-google-form-response-url" method="post">
```

- `action`: Make sure the URL is the response link of your Google Form. You can find it by going to your Google Form, click on the three dots on the top right corner, and select "Get pre-filled link". Fill in the form and click "Submit". Then you will be redirected to the response link.

- `method`: Set it to `post`.


### Input tag

```html
<input type="text" name="entry.key">
```

- `name="entry.key"`: This is the key to submit the data to the Google Form. You can find it by inspecting the form fields of your Google Form. Right-click on the form field and select "Inspect" or "Inspect Element". `Ctrl + F` to search for the `name` attribute. Update the `entry.key` with the `name` attribute of the form field.

_NOTE: Your entry key should look like this: `entry.636287609`._

### Button tag

Finally, don't forget to add a submit button to finish the form.

```html
<button type="submit">Submit</button>
```

That's it! For more details, feel free to contact me. I'm happy to help you as much as I can. 🌟

Email: [haolamnm.work@gmail.com](mailto:haolamnm.work@gmail.com).

GitHub: [@haolamnm](https://github.com/haolamnm).

LinkedIn: [@haolamnm](https://www.linkedin.com/in/haolamnm/).

---
