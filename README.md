## Responsive Design with SCSS & SASS

- Variables 
- Nesting
- Misins
- Partials
- Functions
- Operators
- Extending
- Importing
- scss map

> Best Responsive Design Breakpoints

<table>
<thead>
<tr><th>no</th><th>Device</th><th>Width</th>
</thead>
<tbody>
<tr>
<td>1️⃣</td><td>Mobile</td><td>360 x 640</td>
</tr>
<tr>
<td>2️⃣</td><td>Mobiel</td><td>375 x 667</td>
</tr>
<tr>
<td>3️⃣</td><td>Mobile</td><td>360 x 720</td>
</tr>
<tr>
<td>4️⃣</td><td>iPhone X</td><td>375 x 812</td>
</tr>
<tr>
<td>5️⃣</td><td>Pixel 2</td><td>441 x 731</td>
</tr>
<tr>
<td>6️⃣</td><td>Tablet</td><td>768 x 1024</td>
</tr>
<tr>
<td>7️⃣</td><td>Laptop</td><td>1366 x 768</td>
</tr>
<tr>
<td>8️⃣</td><td>High-res</br>Latptop or desktop</td><td>1920 x 1080</td>
</tr>
</tbody>
</table>

> Bootstrap uses following mediaquerys for the responsive diesign;

```
@medi (max-width: 575.98px){
    /*styles for the small screens goes here*/
}

@media (min-width: 576px) and (max-width: 767.98px){
    /*styles for medium screens go here*/
}

@media (min-width: 768px) and (max-width: 991.98px){
    /*styles for extra-large screens go here*/
}

@media (min-width: 992px) and (max-width: 1199.98px){
    /*styles for extra-large screens go here*/
}

@media (min-width: 1200px){
    /*styles for extra-extra-large screnns go here*/
}
```