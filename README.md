# ENA's blog

This is the basecode of [my website](https://enailis.fr). This project is made using [Hexo](https://hexo.io/) to simplify the creation of the website and the articles that are simple `.md` files.

## Theme

I used [Cactus](https://github.com/probberechts/hexo-theme-cactus) that I changed to my liking (mostly the color scheme and pages' layout). If you want to use the same theme, just follow the [project's documentation](https://github.com/probberechts/hexo-theme-cactus/blob/master/README.md).

## How to use

Clone the repo and go into the root directory
```
git clone git@github.com:Enailis/blog.git && cd blog
```

Install dependencies
```
npm install
```

Make the changes you want (don't forget to clone whatever theme you want to use to the `themes` directory and change the `theme` name in the `_config.yml` file)

Generate the website
```
hexo generate
```

Once you've done this you should have a `public` directory that is ready to be deployed anywhere