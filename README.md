# number-directive-max-3-
directive limiting numeric field to 3 digits

Modify number of digits: this._el.nativeElement.value = initialValue.replace(/[^0-9]*/g, '').slice(0, 3);
Add directive to html: <input type="number" pInputText formControlName="yourControlName" appNumberOnly>
Add directive to your module.ts: @NgModule({ declarations: [ NumberOnlyDirective ] })
