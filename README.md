# number-directive-max-3-
directive limiting numeric field to 3 digits

* Modify number of digits: this._el.nativeElement.value = initialValue.replace(/[^0-9]*/g, '').slice(0, 3);

* Add directive to html: <code><input type="number" pInputText formControlName="yourControlName" appNumberOnly></code>

* Add directive to your module.ts: @NgModule({ declarations: [ NumberOnlyDirective ] })
