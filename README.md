# Static Site Generator

#### Boot.dev definition of a static website
A static site is what it sounds like... static. No matter who is interacting with the site, the content is always the same. You can not log in, you can't leave comments, or upload files to a static site. You would need a dynamic site for that stuff, which is usually powered by a database and a custom web server. We'll learn about dynamic sites later, but for now, we're building a static site. 

#### Screenshot

![static-site-boot](https://github.com/rafaelnacle/static-site-generator/assets/54647722/822120a9-fb7d-41f4-8b43-267c25868568)

#### How to run the project
On your terminal simply run the command below, it will compile the static folder and start the server on `localhost:8888`
```bash:
./main.sh
```

#### To run the tests
```bash:
./test.sh
```

#### If you are having a permission issue you can run:
```bash:
chmod +x file_name.sh
```

### Usage
You can modify the index.md on the `/content` folder and generate a website running the `./main.sh`

To add pictures, you can add a link or just add a new image to `static/images/`