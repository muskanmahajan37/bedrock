```code
this.extendedForm = this.forms.group({
    exampleImage: [ undefined, [ Validators.required ] ],
});
```

```code
<form [formGroup]="extendedForm">
    <rock-image-input
        label="Larger PNG image"
        [height]="500"
        [width]="500"
        format="image/png"
        type="image"
        formControlName="exampleImage"
        [required]="true">
    </rock-image-input>
</form>
```
