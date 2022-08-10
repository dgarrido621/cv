## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/dgarrido621/cv/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/dgarrido621/cv/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
<!-- To set up the boilerplate, type ! and press tab-->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8"> 
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Daniel's Personal Site</title>
</head>
<body>
    <table cellspacing="10">
        <tr>
         <td> <img src="https://dornsife.usc.edu/assets/sites/1/imgs/news_events/2014/11/SpaceFitness2.jpg" alt="Daniel profile picture"Daniel profile picture>
            <h1>Daniel Garrido</h1>
         <p>Daniel Garrido is a current rising senior at <strong>Rise Kohyang High School</strong>, located in downtown Los Angeles.</p>
         <p> Daniel is an aspiring computer science major, creating this website for the purposes of the course he is currently studying.</p>
        </td>
     </tr>
    </table>

    <p> <a href ="contact.html">Contact me!</a>
    <p><em>Student at <a href ="https://www.brightstarschools.org/RKHS">RKHS</a></em></p>
    <br> <!-- Line break tag -->
    <hr> <!-- Horizontal line tag-->
    <h3> Education History</h3>
    <ul>
        <li> Norwood Elementary: <strong> 2010- 2016 </strong> </li>
        <li> Rise Kohyang Middle School: <strong> 2016 - 2019</strong> </li>
        <li> Rise Kohyang High School: <strong> 2019 - 2022 </strong> </li> 
    </ul> 
    <hr>
    <h3><a href="hobbies.html">My Hobbies</a></h3> <!-- href specifies link to another page-->
    <hr>
    <h3>Work Experience</h3>
    <table cellspacing="20"> <!-- Table sectioned into head/body/foot for later CSS implementation-->
        <thead>
            <tr> <!-- defines row-->
                <th>Dates</th> <!--th tag defines a header cell-->
                <th>Work</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>2021</td> <!-- td defines data cell-->
                <td>Clerk at Pico Union Housing Corporation</td>
            </tr> 
            <tr>
                <td>2022</td>
                <td>Full-time student at RKHS</td>
            </tr>
            <tr> 
                <td> 2021</td>
                <td>Resold sneakers and electronics on various services such as OfferUp</td>
            </tr> 
        </tbody>
        <tfoot>

        </tfoot>
    </table>
    <hr>
    <h3>Skills</h3>
    <table cellspacing="20"> 
        <tr>
            <th>Skill</th>
            <th>Proficiency</th> 
        </tr>
        <tr>
            <td>Coding</td>
            <td> Basic</td>
        </tr>
        <tr>
            <td>English</td>
            <td>Advanced</td>
        </tr>
        <tr>
            <td>Spanish</td>
            <td>Intermidiate </td> 
        </tr>
    </table>

</body>
</html> 
