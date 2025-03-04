# pastewin

pastewin is a light and fast static front-end for users in countries where Pastebin is banned. Designed with Python and Flask, it provides an accessible alternative to Pastebin.

Official instance: [pastewin.up.railway.app](https://pastewin.up.railway.app)

![Screenshot](https://user-images.githubusercontent.com/40023234/164679737-ed4ad861-c215-4faf-b327-dffca21fd6ed.png)

## Key Features
- Fast and lightweight
- Static front-end
- Python and Flask-based

## Recommended Usage
For an enhanced experience, use the [Redirector](https://einaregilsson.com/redirector) browser plugin with the following configuration:

## Redirector Examples

```
Example URL: https://pastewin.up.railway.app/B5EfdLF6
Include pattern: ^https?://(?:.*\.)*(?<!link.)pastebin\.com(/.*)?$
Redirect to: https://pastewin.up.railway.app$1
Pattern type: Regular Expression
Pattern Description: ?
Example result: https://pastewin.up.railway.app/B5EfdLF6
```

## Documentation

Clone the reporistrory:

```shell
git clone https://github.com/OfficialV4NT/pastewin-revive
```

Install dependencies:
```shell
cd pastewin
pip3 install --user -r requirements.txt
```

Running:
```shell
python3 pastewin/app.py
```

Check the `https://0.0.0.0:5000` address.

## License

This project is license under AGPL-3.0 - for details check [LICENSE](LICENSE.md) file.
