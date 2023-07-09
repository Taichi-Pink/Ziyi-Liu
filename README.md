minimal-mistakes/
├── _includes/
|    ├── author-bio.html        # bio stuff layout. pulls optional owner data from _config.yml
|    ├── browser-upgrade   # prompt to install a modern browser for < IE9
|    ├── disqus-comments   # Disqus comments script
|    ├── footer            # site footer
|    ├── head              # site head
|    ├── navigation        # site top navigation
|    ├── open-graph.html        # Twitter Cards and Open Graph meta data
|    └── scripts           # site scripts
├── _layouts/
|    ├── home.html               # homepage layout
|    ├── page.html               # page layout
|    ├── post-index.html         # post index layout
|    └── post.html               # single post layout
├── _posts/                      # MarkDown formatted posts
├── _sass/                       # Sass stylesheets
├── _templates/                  # used by Octopress to define YAML variables for new posts/pages
├── about/                       # sample about page
├── assets/
|    ├── css/                    # compiled stylesheets
|    ├── fonts/                  # webfonts
|    ├── js/
|    |   ├── _main.js            # main JavaScript file, plugin settings, etc
|    |   ├── plugins/            # scripts and jQuery plugins to combine with _main.js
|    |   ├── scripts.min.js      # concatenated and minified _main.js + plugin scripts
|    |   └── vendor/             # vendor scripts to leave alone and load as is
|    └── less/
├── images/                      # images for posts and pages
├── 404.md                       # 404 page
├── feed.xml                     # Atom feed template
├── index.md                     # sample homepage. lists 5 latest posts
├── posts/                       # sample post index page. lists all posts in reverse chronology
└── theme-setup/                 # theme setup page. safe to remove
