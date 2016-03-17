# ion-select-autocomplete
Multi &amp; Single Select Box for ionic app

## How to use

Download/clone the repo:
Require file
```
<script src="lib/ion-select-autocomplete/ion-select-autocomplete.js" type="text/javascript"></script>
```
In JS
```
$scope.options = [
  {
    label: 'India',
    value: 'IND'
  },
  {
    label: 'United States',
    value: 'US'
  }
];

$scope.model = null;
```

In HTML
```
<label class="item item-input">
  <span class="input-label">Choose Country</span>
<ion-select-autocomplete multiselect="true" output="model" header="Choose Country" label-key="label" value-key="value" options="optionList">
  </ion-select-autocomplete>
</label>
```
