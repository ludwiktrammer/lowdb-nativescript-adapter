# Lowdb NativeScript Adapter
A lowdb adapter for using the database from NativeScript apps.

## Installation
Run the following command from the root of your project:

```
npm install --save lowdb-nativescript-adapter
```

## Example
### TypeScript
```
import * as lowdb from "lowdb";
import * as NativeScriptAdapter from "lowdb-nativescript-adapter";

const adapter = new NativeScriptAdapter('db.json');
const db = lowdb<lowdb.AdapterSync>(adapter);
```

### JavaScript
```
const lowdb = require("lowdb");
const NativeScriptAdapter = require("lowdb-nativescript-adapter");

const adapter = new NativeScriptAdapter('db.json');
const db = lowdb(adapter);
```
