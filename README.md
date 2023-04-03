# Content for [srfschack.org][1]

This is the content for the website [srfschack.org][1].

The static website is built using [Hugo][2] and deployed to [Netlify][3].

## Building locally

You will need to install a recent version of [Hugo][2].
Then, perform the following steps:

```Bash
$ git clone https://github.com/tage64/sssf
$ cd sssf
$ hugo serve
```

The last command should display something like:
```Bash
Web Server is available at http://localhost:XXXX/ (bind address 127.0.0.1)
Press Ctrl+C to stop
```
where `XXXX` is some port number.
Just point your favorite web browser to `localhost:XXXX` and you should see the website.

If you have [Netlify CLI][4] installed, you should alternatively be able to run:
```Bash
$ netlify dev
```

## Deploying to [srfschack.org][1]

To deploy the changes to the main site, you may install [Netlify CLI][4] and run:
```Bash
$ netlify deploy --build --prod
```

[1]: https://srfschack.org
[2]: https://gohugo.io
[3]: https://www.netlify.com
[4]: https://github.com/netlify/cli
