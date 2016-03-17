# Hi Fidelity Genetics

Website based on
[Grayscale bootstrap theme ](http://ironsummitmedia.github.io/startbootstrap-grayscale/),
which has been adapted to Jekyll
[here](https://github.com/jeromelachaud/grayscale-theme).

## Instructions to create website

1. Fork the Grayscale Jekyll repo at
<https://github.com/jeromelachaud/grayscale-theme>.

In particular, navigate to the directory in which you want to put the website
and then do

```
git clone https://github.com/jeromelachaud/grayscale-theme
```

Once the repo has been cloned rename the directory `grayscle-theme` to
`username.github.io`.

2. Create a repo on your Github account called `username.github.io`.

3. Change the repository in the repo by doing

```
git remote remove origin
git remote add origin https://github.com/username/username.github.io
```

4. Sync the repository, i.e.

```
git pull origin master
```

5. Make changes to the template and then push them.

6. You should now be able to access the website at `https://username.github.io`.

You can find more information about Github pages and setting up the site with
Jekyll at the following locations.

- <https://pages.github.com/>
- <https://help.github.com/articles/setting-up-your-pages-site-locally-with-jekyll/>

## Redirecting URL.

After setting up the CNAME file at the top of the directory, you just need to
set the www entry in the DNS Zone file to `username.github.io`.

- https://help.github.com/articles/setting-up-a-www-subdomain/
- https://help.github.com/articles/setting-up-your-pages-site-repository/
- https://help.github.com/articles/about-supported-custom-domains/

