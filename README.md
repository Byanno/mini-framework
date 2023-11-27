This mini framework was developed by (Fabiano Oliveira) or (Byanno)
The intention is to facilitate the development of dynamic pages with php, html, css and twig or you can choose to use a javascript framework such as vue or svelte, very good for those who master javascript.

The documentation is under development and soon ready to help you develop great pages, it is always updated to facilitate improvements and bug removal, it can be used in connection with predis, mongo and mysql, I separated the best tools for facilitate the development

You can download the small framework I recommend php 8.1 above.

I will soon release the function to work with frontend, I'm still working with the api calls, very simple.

Starting the project

Download the file from github

`git clone https://github.com/Byanno/mini-framework.git`

Using Mongo as a database
Go to the dll folder and get the file called `php_mongodb.dll` and then go to your folder where your php is installed and look for ext and add `php_mongodb.dll` inside it.

if you just want to use mysql you need to search for `composer.json` and remove the following line
`"mongodb/mongodb": "^1.15"`,

Open your project folder in the terminal and type

`composer update`

check that everything was installed correctly

then type `php vest start` to start your php server