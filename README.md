# Minimalist Manga Site Framework

A complete framework to get a manga site going. For: original web comics, scanlation, whatever. Includes: admin dashboard, e-reader, comments (using Disqus), Google Analytics. Site create using framework: [SiberOwl](http://siberowl.com)

## Getting Started

Open index.php, chapterPageTemplate.html, and mangaPageTemplate.html. 

Search "###" in those files and replace "###blah blah###" as necessary. 

Open .htaccess and change 

```
AuthUserFile /home/users/TO-YOUR-REPOSITORY/.htpassword" 
```
to match your server.

Open .htpassword and go to: [Htpasswd Generator](http://www.htaccesstools.com/htpasswd-generator/) to generate your entry.

Replace

```
user:$apr1$GSTNtzih$0bqsoOKDHJBMLLD4m35z5.
```
with the entry you've just generated.

Make changes to main.css as you wish.

You're done!!

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details