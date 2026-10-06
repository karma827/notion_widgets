## Subresource Integrity

If you are loading Highlight.js via CDN you may wish to use [Subresource Integrity](https://developer.mozilla.org/en-US/docs/Web/Security/Subresource_Integrity) to guarantee that you are using a legimitate build of the library.

To do this you simply need to add the `integrity` attribute for each JavaScript file you download via CDN. These digests are used by the browser to confirm the files downloaded have not been modified.

```html
<script
  src="//cdnjs.cloudflare.com/ajax/libs/highlight.js/11.12.0/highlight.min.js"
  integrity="sha384-KnPvYPx1poT554tHDV1nuYV9sOkh4cZPBvLZQlXgJmoRQZPdgQNwL50/xq9kynp9"></script>
<!-- including any other grammars you might need to load -->
<script
  src="//cdnjs.cloudflare.com/ajax/libs/highlight.js/11.12.0/languages/go.min.js"
  integrity="sha384-orYKHAs3chK3oDMQLy5ywrzoY8z9zvzfmNIjmVxKXioAUtwDhP+xf6THWYSI/43Y"></script>
```

The full list of digests for every file can be found below.

### Digests

```
sha384-aud7Bs/LNDYM5VaFv7oYny/ZuHhS2WB97SeEiVKUL8wFAXvhfH65gShq42rBCdnl /es/languages/actionscript.js
sha384-JklYt1ogwdy5VQ4qXS5cc1/sbESGZg0XtD9szULnB7suLabZWwCyaH/gg7xhEX2z /es/languages/actionscript.min.js
sha384-i/6EEc9FnRaeDWem8m4ym+cpXqHI/w2puDFdUxWgXGOAtA0vua1mvQCA6jU7MQgu /es/languages/angelscript.js
sha384-7y+azRKyH05pGxG+yLy9uBXMKKWhImMyILDNatMJrIA7MhwPNCCad2G30PfEGfe6 /es/languages/angelscript.min.js
sha384-n7+lBVUblUTCJIr1L0Z0/+3157MEwLX/60SqJqlWmyB31P+vG3ZGbMs3wgS5aKxm /es/languages/autohotkey.js
sha384-EjHb8tSLwN8eEvYk75xaR7ETcGn3G1UAgndj0y1WUfAdr2KnofqCLgMAWzsv/NCI /es/languages/autohotkey.min.js
sha384-RXftkXoNvYqUJwOt6SHqM2LYeZbYCBjM5NavsO90nFvSyfeabXOwVuiQQPK9IiXG /es/languages/csharp.js
sha384-/Y02okSZEfrz8yFmiDDj3/KtF/vixqlddULDmRbQpm3mzodelRMVW9a02TKwR6XI /es/languages/csharp.min.js
sha384-amdMjFrQeV1IlGyVyYRGeUBxPp1NVz7WG5xs0heAwCiAZLj0ISxeJwiOTeom9RfS /es/languages/css.js
sha384-rLeEizUP6J+98gF7EZ4ngav3h+slU5SqCVDahqOoYBEdjzhWQ3g6XldnqR9BSlBR /es/languages/css.min.js
sha384-DZjuukqcYYTk/hS3IuTO2kx7pRBNCZdEaS9Lb1oZvW+IOfY3rmrxaoDj+/BRB4eY /es/languages/excel.js
sha384-1dWgPKmSBS1dVQnax3aQfjco9OU4pjtv3Jyg3mm+Bypn4MGpQeoc6KLHlszZXxMk /es/languages/excel.min.js
sha384-hzQ2yj1Qgn9QFeoeiOxlecYge16nDa0kYU3K/iQ5+2Y0JelkS2+LEgu86rHjA/yO /es/languages/http.js
sha384-sVSw9OMM4hyWaJ7X1x8cNgeubs4kjR9jfW1hab3Nh6STAKRdw7yBtaVRnSeVFOCH /es/languages/http.min.js
sha384-o4UvWNmnl1L+ChjYSiEzv6+SmutMhWyMN6YBulDKvTe8IUDetXNVFtu3jjjUcEy6 /es/languages/ini.js
sha384-om1+Rx6vks+orizrPIf1OpBFEOqHVfjPlx6hSoIY80V1fDLkPa69GFlafLtsMSWQ /es/languages/ini.min.js
sha384-z9bZmXQ6WniHUvySgc0/iokrwX54kIx/ZDvUIHIwAjgHRFjLZgNKiTX3UBi5aY/4 /es/languages/java.js
sha384-WmZNtzcna3shPin4x0B8fSeXgtW14zoyha+gmtNTU53pa/ZImw0O8FmX0x06ETq+ /es/languages/java.min.js
sha384-mxaIAuwA1l6te9LMbWwt9PNtaoRiwRk1/345TMC2UQtNTi1kjbhizCrSxaHAegHF /es/languages/javascript.js
sha384-r8C5XKdITWu1xHcHMIfmqgbWZTa0w/MPyAykL+WctwUoeTsEHBo5+jSSoHQ+qFy6 /es/languages/javascript.min.js
sha384-lt0gg86v1uEAI7/c2402dN+9T2iQXopS6OJ8P1jHo1uOZu1zIV5sX8vmlOLGozq0 /es/languages/json.js
sha384-UJwfLbfKiYs+crNOV1xJL6wDet7JiH/Kav6qZ9c+cOjar4piP1X0VQqwVE3RJt+z /es/languages/json.min.js
sha384-bDh/jrDlM0OSA6LIT2wBxy50zFGhtLxAZ+iJONX+uwjJqYld7tF+mhbOF27H9Z0z /es/languages/less.js
sha384-vs76c5ilg0Vaa9O2Qj6tXlllVDVRb2RFmGDLV2esNIN+7VVbwi+MDZwkvDHs3qsl /es/languages/less.min.js
sha384-vW4uMxypI7CdpYNqn5GxisalenKeZqzn3RCKBc5c5enqkK5V0TY6YtCdFcj4ONK+ /es/languages/lisp.js
sha384-jVm7LV924j3PfruoVYf5/8QJR2tnVJgxUU9Ata18cVpXyZKlchzfom4B+bBVYIae /es/languages/lisp.min.js
sha384-Cutk0C9aXwvjDHuiO9BvDqmciz1aqYbONjaKHEY0xdhpRISU3bYVyjPZKK+kmZrG /es/languages/lsl.js
sha384-QyFJEQNm4gJZxNfbqMvnRFxSMT9MPZHg5vxMI1PRDnBCVsZU0S63vCQyOIGYRX6O /es/languages/lsl.min.js
sha384-47Dn27oZJHoNVUL4leYvOLfxpXtmetYh9lZ7olKoDqzPebdZqqLE3xNY9iHEu3O/ /es/languages/lua.js
sha384-RUO5JMeXmbOe7bDSAF/Yzw4V9xXupHGlmNKK4+/UZIPdock3BGdBwaWYzM+j5se2 /es/languages/lua.min.js
sha384-qXAmSIiI587+IHpd/KU7WRz9snrtBhVCR5pST316BxhuxRbXzb6uWmB8WC/2eqUi /es/languages/markdown.js
sha384-atzUeXgldTnp0Vvir5hFSZ4MRX0FWOpxp7UdXca7uje0uL5S6swwfRhq5SB5Ag0m /es/languages/markdown.min.js
sha384-UbOS4JomBdQgpHT9lwmZipdtIqKiJP8T2IG7oG0l6K/LnyVrSMoaPI7Hh6vWatoS /es/languages/plaintext.js
sha384-RhTHpYmm2hh4ZEkHCbk+tklVV1oUvBVYUfdesSGg3QO/JtYDmqYoycxlBJxg9Lqb /es/languages/plaintext.min.js
sha384-6odyGlinr87WkUy8CrIkkGXADbjASyp4QurigkfoQsE/7EDdRtidR8ZRREPZzyq8 /es/languages/powershell.js
sha384-J4aMNiIZh/D5uD+4kvRw5xdBsyJlZe6y+/smXZwdzIK8MJ53AesXxyGsV1ltnmbU /es/languages/powershell.min.js
sha384-M29KVshhb1nOr+V9fD7zculEkusgFmZdZpLoQxEiEJ7nTncEiXzJ9/tXuofiOIYK /es/languages/python.js
sha384-1SN2ySEZrgpb2XQB4PRJli/u1Jj5sm1j+Be77jnSNNmKzhUZK8OBkGFFexuOPSHu /es/languages/python.min.js
sha384-eOXRcD62va+i9VlDYecRvoMjuDY7GltQDo4PJM4ylUsN49CCqXu+fumqfopj7Lbi /es/languages/python-repl.js
sha384-L9i6yG+cVyCdxP1Bu+OO1lfIT+A+6bU5xgNYBtvY7AhRK7eOLvwnxXS696wxFZVR /es/languages/python-repl.min.js
sha384-RdcmcN+/XvSqKljXtkqUJHBlUAT8ndQI+w5IhKHuioHvZs+m8sMRxV5JihKPWgV7 /es/languages/r.js
sha384-pzlBoVr78luNmZ2t7oTrDsAWnaoDLVO/ZQBEYBuN5dR2QLH0oldQCd4Wjn64HJxH /es/languages/r.min.js
sha384-2GCu62tJwVVFqmC5PUNwKJev0TVKHYUU8hHtXTaaz/bwtVpJ4sVIrI6tl4zXmZPr /es/languages/scheme.js
sha384-2n5BiRIQuLlxF/0W3BI//OoLimZ+YKFSTK7bWCgQkkO72miZ4xjcSpGA1+0xVA1w /es/languages/scheme.min.js
sha384-KIISJ1MIG4sJ5EmeehDSTxWDQLEV3xogIXFtI39eXo4DjSvbAIm6s6m0Ckw5OsxB /es/languages/scss.js
sha384-qTIHQ6M1cS8rvFci6dL2FprsPEsvR7KlWL271KM5K76FwC6VVGHaDL0HP4/YDzQA /es/languages/scss.min.js
sha384-1x+arn/A8CSZOUs83+Fa6bwOOwxzz9Fqc+OZ3YVh+yVOvF5H6uvqHDx6Bh4UNAp2 /es/languages/sql.js
sha384-e1St/oZyx5GxD71Zry3asHLIZmg/b20NgNJLUwvput4g+SZj8Rjuq+aP7pdWC2qh /es/languages/sql.min.js
sha384-KffmG1xrid4XTUVKka4JVU/lSdYqWjanFvd48ZE7oDSAWWvU99ygwqJ2KMNIkIkm /es/languages/stylus.js
sha384-Eu2Q1I5nOzr3hX+X/PybnKQlr/J9EKds40qGpauG90/chp+vBeGLN0aHmQQDSVGf /es/languages/stylus.min.js
sha384-zxDxZt8QGQFSoSCDbGYZh+Wo2IEgOus0mwRz72b+9Lis3RVnYQw5/AKZPKDp93oa /es/languages/vbscript.js
sha384-XDJ/N/B2ab58bJomwzGn7jtVBhhZR/xVipUF3Fu53wTGqTW0lZjtPfVlANiqMl6n /es/languages/vbscript.min.js
sha384-XaXcfZIK+ndxxNaZ1kbdtFWuG1q3xu5H4o/zWaF/LKRX6VlUJ399fJHNoVckEEI+ /es/languages/vbscript-html.js
sha384-NJG+n4Z5bKuiK502tXMro47TbVSz0lMEn+p/KdiqMplh05cbHsBSaLMKNwdgkogO /es/languages/vbscript-html.min.js
sha384-XZNCXUeNSjWoW5lAESpD8AkU5NhwkwL0a6wIzJWfMEx6qNtF29L+81oxGOy4b3Pj /es/languages/xml.js
sha384-7lgbaoMNJXxrndTFyw0ll0hq1MZzDLFkFmLhYLibSJNXgcW6xOSU9e+OS2QaAKDP /es/languages/xml.min.js
sha384-V4dEHxGPcfKe0nPj1Kf4bHhhEWQok5V5odOaTC9ADMs0bJqyVuFfVDkhTZaSWwpC /es/languages/yaml.js
sha384-nw7e1KnZnvc0mX9u7q45N8KXp4CIDO3+GsbJgpVp4Ye3b1taSPCD2+dtUlqqjTYC /es/languages/yaml.min.js
sha384-9d8edz7bqKVyZkE6ETOCmUyGYRM7EEhEkEtCnF/rv+WjjAeEimhRN9rmyRLsuGCT /languages/actionscript.js
sha384-9x3tLiEFYbGRxL2aW2dE4bBLIC2ikrzq3hDr0QhY6o3wOBeOqccOlN5CdQtw3TtU /languages/actionscript.min.js
sha384-G4MS3wtRY862Bi+LuOJ5qkcvlXktl9q9fDrGdCK2oVFsCy4bmFh2oO2mlLAF0yv2 /languages/angelscript.js
sha384-eS14DqT/Hn+h7VImaaNcfRwvD0x0thQKkYt2NjsPYvOXHjBbd8pY8u7it8Rop/um /languages/angelscript.min.js
sha384-EZSN05Mgh9YP0VxHceL+yWQ4VfilAlDN5PjU2krNjJ2K15/v4Lir0bhl6Fyf2ny9 /languages/autohotkey.js
sha384-ETU9ophSb0GK/xgHFcGYMaf/7Xufu0TKDpmyumud5YRR6tX1m8xStyA/8hdGNp+6 /languages/autohotkey.min.js
sha384-QYHS+ofe4eSYS3zcwW+oElJPLA2HYu4aYzmzXOpHsGwaM19ytDaqjbRzE0odwrtF /languages/csharp.js
sha384-UmTmCSuac/JgV+xJdKhzfTJ6R7AIX7P48kgC024cGCbJSx6vePS4XPyMrzU5LW/v /languages/csharp.min.js
sha384-+G97Y66qjmfAEeNK5AYrOqbLn/hBNX41qhtyiVW7z3Zq/1llyjGJr3gHmNi+AVKN /languages/css.js
sha384-FvHR2wIZNmDX0TgSuoOhAZRl6R5yRi26wu2/MVXDm1ZFCGJUvotj2RrvVLGC4y88 /languages/css.min.js
sha384-hXqni2TcPAoV7TsY7aT4Cg0maOTsMakXoZmO+/65AI2LA1p+lAo5l6imPYp/OvZn /languages/excel.js
sha384-58/fdyRU4xnHhJjtucGxcmuREWKSkYeGELj5LoqjS2pk2/HxrKXfTWIFdShavX71 /languages/excel.min.js
sha384-zmInyL/uNPOnQvVfQtEAadsrA71Cn2otNpIRZB5XZznH8p6RQb5UaYxSToivYtM3 /languages/http.js
sha384-L0lAPMci4/TxXazgm0dJIgX9udJzIJf78sk4o9v5sYuRVYJSjymFXF13LmyCU3L0 /languages/http.min.js
sha384-0tQ9l/wLu1PEfcESn4J1X2XjEGE4pKgn9SG3tfgEpRwX0yuZfCPtxSDQmjOgoO+b /languages/ini.js
sha384-FtUKo+hpWyLS/IYUX6GZGKptmt2igNPFsWSqPRz7qk7cnN+/sbt/22tz8lH2iEyk /languages/ini.min.js
sha384-Qj/fL9z0ymYPbd/2AWbWGyDfM3jjtdV4Vs4KdUS6OoIbA4AahIb3PpkR8nociDdi /languages/java.js
sha384-1OHpuM8WHOF2rIMbr6F9TXndkg39R1UtQGGfiifSXWlIthYEjIVkx94n05/gy931 /languages/java.min.js
sha384-5vRFHgNazcqNV/wYjVV73vv/mmcguTGfUhutWTMzUdixVclmxoe32uu3C1i5U+b3 /languages/javascript.js
sha384-luOC72UPK+5vw8AmdAZNVaFIY8IN7MayLzqcVcnUdCCVug/rAyhze5dpWklUZW8b /languages/javascript.min.js
sha384-xRs5pKapNPranWV1tpWwbWD8FN6u6gwlBXWwW+3wcfgCrXtc+VuTjt6Ff2MZTUoZ /languages/json.js
sha384-BuKQB2q4LIWSYzKqO0qkAQOdYLvqUmSmzUtLZDkTHy5po4tY7DSEcu/r5555QON2 /languages/json.min.js
sha384-ldbjDAIm+nFWhElZuPzQQPxffBSeej7snYvy8fb3pps6mGcqHEn1KPZGn6li62cn /languages/less.js
sha384-vtOZVRxEmiU1iIbY6AdrnW5QCRjdA1XwkG3TmGr8QvQvUvmBUdu8FzGkqde7xrjh /languages/less.min.js
sha384-pZTJ3Uur8k8zqFzqXRuA+Fy7SJLuz4VIRzg6mgE5EzcIvtXzvo3pxEhrumcrIKaH /languages/lisp.js
sha384-JPkK+3oG1Os0vhKRFRZnvEH6NeoWJn8y9pDddmqFOOMjNV+Y4BEB4WtG9Yf2/JG7 /languages/lisp.min.js
sha384-lRky4Djkot7LTAmJEed6oNoqLAapTTOrEICdZ6V48q3MEhp5UYCrv0/ML126M99F /languages/lsl.js
sha384-lXxJYwHPcbBA/BVinPI0ggMvTpPxZdX73ISlerBKfXPHMdUAtIinHpBdj1wUwrY2 /languages/lsl.min.js
sha384-X7kIOhO4b0cvc9Ro4AM1xtGHL0uSrOPcvdCaVRV4R2bp0WfZ+rwq0nRA+gcYmRsU /languages/lua.js
sha384-4O9XXj4HbJ3xc7QSKua6ZC/g7oB7lUP5VJo2Otc6LY62LJVfV/Ruod9z3NLR+W2R /languages/lua.min.js
sha384-E5HEb58PlD3DyF1d/ePfVyiVVyWY78cCsbBBHPtlGSEFbNDHTcMoBnlt8dHP62OU /languages/markdown.js
sha384-VEGOCRct+04gpJrYhkaah46lXsjH+/u05lA+0IwU+eqzRpr2/bcRlnoHdu2xVr6+ /languages/markdown.min.js
sha384-5antmxjEm+wiK5ytnS/IhTDt8w3EK4ELSuskQjN+4wPiEPP0PE6aE65JRI9R4ZVj /languages/plaintext.js
sha384-vpQpEp61iIf7WRxlpZKYck63VGy6819HP7jPmr8BoVQ1D6Ov7Z4RR9deMn/v/6t+ /languages/plaintext.min.js
sha384-tKUvlrViq1irRudj0It+O6fP+yvFuAE5o7cv0jeI54Eh+BQ9tis828GWbdqwT+XS /languages/powershell.js
sha384-jigawbLJjSW9uklht6/lvMBC7b00t25Id0RQW+qORcsF6B+LARvlTLfzyIaNolYG /languages/powershell.min.js
sha384-vHFyigyrxXKrLcfzhSiSgjFvq0h4IaawkRiHBKD7g4xx6ny6hQvUeIe5o0vcr2Qi /languages/python.js
sha384-MjEDnJ45PjESeDQtPkC0gdCZlwA6MWEYLl/Qw95D9e1Ow8yAlz/xkS/EDIxFiig6 /languages/python.min.js
sha384-3TgqxwRPducb5/vGWjiLb4y0YJyGT8Z5mJ2kuoQDS+HuQgH16PHxiKupjgYSbM4c /languages/python-repl.js
sha384-2cTCVdOaOTLF7bNkHF1TF7PDz9YciUPV7pvo+IZaAjjY0r/Ph0medtLzbhZFAOnd /languages/python-repl.min.js
sha384-fFMR5EFIa6YPqEGnYTOztGy4PwYhgl2InEd1SOifkNjUrnY/FX1JO3vnz+YIP/tI /languages/r.js
sha384-x149hketIbY4jDkg82cxpbkuCJO+b+PunNrxHFuzTlkIMbEUflx7qOIwMU5kVNzO /languages/r.min.js
sha384-GR/y3vciTefXdhWRS9HQZXkTtS3QzAU698tITUPR4UlFT/X3gDI4ygMzRWhDmbIg /languages/scheme.js
sha384-MAbum4IyUmlGkScyApilwRqISD/a/teYmeh67/ohQqHHwY0FlkeIvxWLxwdNXM2p /languages/scheme.min.js
sha384-Pw/HuYa78ix1/THPAU1fbp4nN2tOT7inj88wIU0Y2HyhnwV6jigMIBNhzr+SLCVW /languages/scss.js
sha384-o1Gduq31NS1KqRP7OOK2ahBW/7+2WK3PxfaOnJoN12i6wpxzz0mc66xl+3IriZtw /languages/scss.min.js
sha384-a+Iw5odyfpVyqnZLhXgjgfrTGL83SYa8BG2NpF/DmbvRloJefgDUZEDQ4j2662cz /languages/sql.js
sha384-xmw+Wgf/U9GjB60m9/I4SBh8zETMwAFC8GqSL7kCfkfgoKHDffjcnkQrNpQLc/96 /languages/sql.min.js
sha384-aXSIpcfPVpbjs9T7bCsq1oAh6TGNDU3pY6dlPTaBYg8C5NdRoCZBgxbVmL5hjhis /languages/stylus.js
sha384-x/TbqfrW7rPeTk96dpU4gyJjGbUM5W4Cv3WUg9Ny8RWAbdz7pVIkj/irin942SF0 /languages/stylus.min.js
sha384-y5cC2ILYzdFvP6KatxW8S/ZNfqeZ/uGp0rJSzNoueNKYQKYqIfFirgig478PIhb2 /languages/vbscript.js
sha384-F3PdTu1H9EQbf9+kaCgXMsK9KatSzkU8gN5BlM6zw+NwiN5HaUmcEjs/fQlgUf8P /languages/vbscript.min.js
sha384-I5DWgGrrs1ef0oSQu7qRJ5zAd4cN5efXDwRsTCewsNkTJMCbVrX/qEgiCbpNtp24 /languages/vbscript-html.js
sha384-L1GVKH/XONTx/Ax4PfPpugJAYv6Vboz6EJHm7eYBBu56lE97DJWzYnxkvEMbjiqo /languages/vbscript-html.min.js
sha384-NNLNlM+AFtDXFlKRhmVO4gnfAl8a6U0y/QRO+jb8Cbx/1wYFSjpS8XF3mexCbQ7x /languages/xml.js
sha384-1iugfrw26YFHz7tD9aJCXklIDFXhf2qx4cJGfo4T8mWP+9nwOCnZpq0PqoXqcpO5 /languages/xml.min.js
sha384-QiM+6eBaRFHV4SXe9mvWNsiQXkInig0NsYzM6aIHbVEcgJ2j4WDRKSjUBTkqLUjg /languages/yaml.js
sha384-3Z1ACXMaXuAS5eP39k4q24JKpbbb3hxVfEYQuXhujNu4KZSYl/BepBcMrSys6psg /languages/yaml.min.js
sha384-woPeB0T/6Ftg6CjN1UiGr1kfkhnynpQ2Zae1iY5oDtnAmfzIFewSJ6O9WVpUJZ7K /highlight.js
sha384-FVUkl/w8DIfkWJPxg0cMDxpCwqCziRyyyS9r+WUIrB0tmzj+uyuGPK4iaLZKftir /highlight.min.js
```

