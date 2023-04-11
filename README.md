## NiceWang's Personal Page

### v1 (202304)

* Using Hexo template with Fluid theme

#### 0. Requirements

```markdown
    NodeJS
    Hexo: npm install -g hexo-cli
```

#### 1. init hexo project

```shell
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

  * ```shell
    hexo new post new_blog
    ```

* Modify related markdown file

#### 4. About, Categorues and Tags

```shell
    hexo new page about
    hexo new page tags
    hexo new page categories
```

#### 5. Local Start-Up

```shell
    hexo g -d
    hexo s
```

#### 6. Deploy to GitHub Pages

```shell
    mkdir .github
    mv hexo-blog/ .≈/
    cp .github/hexo-blog/public/* ./
```

#### 7. PDF support
* Install hexo-pdf
```shell
    npm install --save hexo-pdf
```
* Modify _config.yml

#### Appendix
[NodeJS Support For Hexo](https://www.npmjs.com/package/hexo-pdf)