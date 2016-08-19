## cycle-display-driver

This is unreleased, and does not yet work


## Usage

```javascript
import {MakeDisplayDriver} from 'cycle-window-driver';
import {run} from @cycle/xstream-run;
import xs from xstream;

function main() {
  // ...
}

// default type is 'browser', see docs/options.md for supported types
const drivers = {
	Display: MakeDisplayDriver('browser'),
};

run(main, drivers);

```
