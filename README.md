## NiceWang's Personal Page

| Version | Framework           | Release Date |
| ------- | ------------------- | ------------ |
| V1      | [Hexo](https://hexo.io) (Theme: [Fluid](https://github.com/fluid-dev/hexo-theme-fluid)) | 2023-04-09   |

### v1 (202304)

* Using Hexo template with Fluid theme

#### 0. Requirements

```markdown
    NodeJS
    Hexo: npm install -g hexo-cli
```

#### 1. init hexo project

```bash
    hexo init hexo-blog
    cd hexo-blog
    npm install
```

#### 2. Switch theme

* Search from [Hexo Themes](https://hexo.io/themes/) or github to choose favourite theme

* Download (Clone) theme

* Modify _config.yml

  * ```yml
    theme: fluid
    ```

#### 3. Create blog

* Modify _config.yml

  * ```yml
    post_asset_folder: true
    ```

* Generate blog _posts

  * ```bash
    hexo new post new_blog
    ```

* Modify related markdown file

#### 4. About, Categorues and Tags

```bash
    hexo new page about
    hexo new page tags
    hexo new page categories
```

#### 5. Local Start-Up

```bash
    hexo g -d
    hexo s
```

#### 6. Deploy to GitHub Pages

```bash
    mkdir .github
    mv hexo-blog/ ./
    cp .github/hexo-blog/public/* ./
```

#### 7. PDF support

* Install hexo-pdf

```bash
    npm install --save hexo-pdf
```

#### 8. nodeppt

```bash
    npm install -g nodeppt
    nodeppt new slide.md
```
[NodePPT](https://hexo.fluid-dev.com/posts/hexo-nodeppt/)

#### Appendix

[NodeJS Support For Hexo](https://www.npmjs.com/package/hexo-pdf)
