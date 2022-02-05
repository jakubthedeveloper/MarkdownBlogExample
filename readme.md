# Example markdown blog

This repository contains an example implementation of the markdown blog created using library [https://github.com/jakubthedeveloper/SimpleMarkdownBlog](https://github.com/jakubthedeveloper/SimpleMarkdownBlog)

## Usage

### Requirements
- PHP >= 8.1
- Composer

### Install

```
composer install
```

### Templates

Save your templates in the `template/` directory.

Tags you can use in templates:

- `__BLOG_TITLE__`
- `__PAGES_LIST__`
- `__PAGE_CONTENT__`

### Pages

Save your pages contents in the markdown format in the `markdown/` directory.

### Configuration

Edit `config/pages.yaml` to set your pages configuration.

Edit `config/blog.yaml` to set your blog configuration.

### Generate HTML

Use the following command to generate pages:

```
./bin/console generate:pages
```

### Output

Generated HTML files will be saved in `public/` directory, vhost on your server should point to this directory for the public files.


