# Sbobinator Website

Official landing site for **Sbobinator** — local Italian audio/video transcription with NVIDIA NeMo Parakeet.

Built with **Jekyll** (same layout as [cryptoquantix.github.io](https://github.com/CryptoQuantix/cryptoquantix.github.io)) and deployed on GitHub Pages.

## Local preview

```bash
bundle install
bundle exec jekyll serve
```

## Documentation

MkDocs HTML is published into `docs/` from the main repo:

```cmd
cd ..\sbobinator
scripts\publish_docs.bat
cd ..\sbobinator.github.io
git push
```

Main project: [github.com/sbobinator/sbobinator](https://github.com/sbobinator/sbobinator)
