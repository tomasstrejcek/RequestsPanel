# RequestsPanel for Nette v2

Installation
------------
 Best way via [Composer](http://getcomposer.org/):

```sh
$ composer require tomasstrejcek/nette-requests-panel:@dev
```

Usage in <strong>BasePresenter</strong>:


	use \Extras\Debug\RequestsPanel;

	public function startup() {
		parent::startup();
		RequestsPanel::register();
	}

Usage anywhere:

	use \Extras\Debug\RequestsPanel;
	RequestsPanel::dump($variable, 'My Variable'); // label can be omitted

Example:

<img src="http://imageshack.us/a/img525/7865/screenshot20120923at600.png" alt="Screenshot" />