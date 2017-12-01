# sass-bootstrap-2-grid-to-bootstrap-4

Applies Bootstrap 4's grid styles to Bootstrap 2's grid classes. Bootstrap 4's classes are applied
above the 'md' breakpoint. Below that point, all of Bootstrap 2's grid sizes extend the widest
column size (12 by default).

## Install

```
yarn install sass-bootstrap-2-grid-to-bootstrap-4
```

OR

```
npm install sass-bootstrap-2-grid-to-bootstrap-4
```

## Usage

Import into your Sass:

```Scss
// ... some other imports, e.g. your Bootstrap variables.

@import '~sass-bootstrap-2-grid-to-bootstrap-4/main';

// The rest of your CSS ...
```

HTML example:

```HTML
<div class="row">
	<div class="span4 offset4"><!-- The same as class="col-12 col-md-4 offset-md-4" -->
		Example
	</div>
</div>
```
