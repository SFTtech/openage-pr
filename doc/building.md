# Building

For building this website you will need the static site generator [Hugo](https://gohugo.io/).

All the configuration you find in `config.toml`. To build the website, you go to the root-directory of this repository, open a Terminal and type:

`hugo -D`

The web-directory for hosting is created in the directory of `publicDir` that is set in `config.toml`.


# Developing

Hugo can spin up a webserver for you for development. Just go to the root-directory of this repository, open up a terminal and type:

`hugo server`

# Introduction
Short Introduction to the directory-structure:

``` 
.
|
└── content           // Here you find all the pages, content, etc.
|    └── blog         // self-explanatory
|    └── docs
|
└── data              // In here data is stored that is used by hugo gen
|    └── carousel     // data for the carousel on frontpage
|    └── features     // data for the features on frontpage
|    └── supporters   // data for the supporters on frontpage
|
└── layouts           // In here all the html-templates are stored 
|    └── partials      // partials are small chunks of html/hugo code that can be
|                     // included in any other file
└── static            // css, js, images, fonts
└── themes            // the theme as a git-submodule, 
                      // layout files have priority over theme files
                      // all modifications are made on top of the theme in the 
                      // layout folder
```

Take a look into the [Hugo documentation](https://gohugo.io/documentation/), it's a pretty powerful tool.
