# A Backpressure Algorithm for Sender-Side Track Switching in MOQ Transport

This is the working area for the Internet-Draft, "A Backpressure Algorithm for Sender-Side Track Switching in MOQ Transport".

* [Editor's Copy](https://moqtail.github.io/draft-zengin-moq-ssts-backpressure/#go.draft-zengin-moq-ssts-backpressure.html)
* [Datatracker Page](https://datatracker.ietf.org/doc/draft-zengin-moq-ssts-backpressure)
* [Working Group Draft](https://datatracker.ietf.org/doc/html/draft-zengin-moq-ssts-backpressure)
* [Compare Editor's Copy to Working Group Draft](https://moqtail.github.io/draft-zengin-moq-ssts-backpressure/#go.draft-zengin-moq-ssts-backpressure.diff)

The previous version of this algorithm is implemented in the [MOQtail](https://github.com/moqtail/moqtail) relay,
as the `backpressure` algorithm of the `moqtail-ssts` crate. The current version is not yet publicly available.

## Command Line Usage

Formatted text and HTML versions of the draft can be built using `make`.

```sh
$ make
```

Command line usage requires that you have the necessary software installed.  See
[the instructions](https://github.com/martinthomson/i-d-template/blob/main/doc/SETUP.md).

A PDF can be produced locally from the HTML with Chrome:

```sh
$ make
$ "/Applications/Google Chrome.app/Contents/MacOS/Google Chrome" --headless=new \
    --no-pdf-header-footer --print-to-pdf="$PWD/draft-zengin-moq-ssts-backpressure.pdf" \
    "file://$PWD/draft-zengin-moq-ssts-backpressure.html"
```
