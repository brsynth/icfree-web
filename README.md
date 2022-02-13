Source code for [icfree.org](https://icfree.org). The website was built using [Hugo](https://gohugo.io/).
The domain name is available untill 21/09/2026. Check [ovh.com](https://www.ovh.com/fr/) for manual renewal.

# Running the website on a local machine

Clone repository

~~~bash
git clone https://github.com/brsynth/icfree-web.git
~~~

Install Hugo by following the isntructions here: https://gohugo.io/getting-started/installing/

Run the server to access the website

~~~bash
hugo server -D
~~~

Build the public folder for deployment. **You need to generate this folder and delete the old one each time you make changes to the source code**.

~~~bash
hugo
~~~
