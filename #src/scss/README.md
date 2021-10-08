Project using the [7-1 architecture pattern](http://sass-guidelin.es/#architecture)
and sticking to [Sass Guidelines](http://sass-guidelin.es) writing conventions.

The 7-1 Pattern

## SASS <br />

### abstracts/

\_variables.scss <br />
\_functions.scss <br />
\_mixins.scss <br />
\_placeholders.scss <br />

### base/

\_reset.scss — Reset/normalize <br />
\_typography.scss — Typography rules <br />
… # Etc.

### components/

\_buttons.scss <br />
\_carousel.scss <br />
\_cover.scss <br />
\_dropdown.scss <br />
… # Etc.<br />

### layout/<br />

\_navigation.scss <br />
\_grid.scss <br />
\_header.scss <br />
\_footer.scss <br />
\_sidebar.scss <br />
\_forms.scss <br />
… # Etc.<br />

### pages/<br />

\_home.scss <br />
\_contact.scss <br />
… # Etc.<br />

### themes/<br />

\_theme.scss <br />
\_admin.scss <br />
… # Etc.<br />

### vendors/<br />

\_bootstrap.scss <br />
\_jquery-ui.scss <br />
… # Etc.<br />

<h3> style.scss </h3>  Main Sass file

/_
@media screen and (min-width: 1024px) {
.form**item,
.footer**form-item {
height: 57px;
max-width: 350px;
}
.form**paragraph,
.footer**form-paragraph {
/_ font-size: 14px;
line-height: 21px;
}
.form**input,
.footer**form-input,
.form**input::placeholder,
.footer**form-input::placeholder {
font-size: 18px;
line-height: 27px;
}
.form**submit,
.footer**form-submit {
height: 49px;
width: 94px;
font-size: 18px;
line-height: 27px;
}
.form**submit:hover,
.footer**form-submit:hover {
cursor: pointer;
}
}
\*/
