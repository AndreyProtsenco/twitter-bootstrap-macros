media-queries.less

**Description:** Media query macros

**Example:**
```less
.test {
    @media @lg {
        height: 10px;
    }       
    @media @md, @xs {
        height: 15px;
    }
}
```