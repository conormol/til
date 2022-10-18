Nicely fit elements inside a page header, or anywhere else that may require different secions to be level but on opposite sides of the page

```
.site-header {
    display: block;         /* Display header as block 
}

.site-header-left {
    display: inline-block;  /* Display must be inline block so that the site-header-right can be on the same level */
}

.site-header-right {
    float: right;           /* Brings it right but keeps it the same level as site-header-left */   
}
