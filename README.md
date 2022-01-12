# logos.kiwibrowser.com
Logos and icons used in Kiwi Browser (in tiles and new tab page)

This is the service behind logos.kiwibrowser.com

The resources uploaded here can be accessed via `https://logos.kiwibrowser.com/<IMAGE_NAME>`

| Header                   | Meaning                                                                                                                                                       |
|--------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
| X-From-GitHub-Cache: Yes | The logo was served from a cached version of this GitHub repository.This is the header you are going to see if the logo is served from this repository.      |
| X-From-Cache: Yes        | The logo was served from cache.                                                                                                                               |
| X-From-Cache: No         | No matching logos were found so a new high-resolution logo was captured by the fetch server directly on the target domain (generally `apple-touch-icon.png`). |

In case of `HTTP Error Code 404`, this means the domain was not found and no alternative could be provided.



#### Specifications
 - File format: .png (only)
 - Image resolution: 128x128



#### Directory structure
 - assets/`<FIRST_LETTER_OF_THE_DOMAIN>`/`<DOMAIN_NAME>.png`

By default, the subdomains are all pointing to the logo of the root domain.
`kiwibrowser.com` and `example.kiwibrowser.com` are both going to point to `k/kiwibrowser.com.png`.

The only exceptions, are the domains listed in the public suffix list ( https://publicsuffix.org/list/public_suffix_list.dat ).
For the domains listed in the .dat file, we keep the subdomain intact.

Essentially, `www.google.com` and `google.com` will be canonicalized to `g/google.com.png`
`test.blogspot.com` and `test2.blogspot.com` are two different sites, and two different files (`t/test.blogspot.com.png` and `t/test2.blogspot.com.png`).

To parse the public suffix list and get the root domain, we are using: https://github.com/lupomontero/psl



#### Examples
| Domain             | Filename                        |
|--------------------|---------------------------------|
| kiwibrowser.net    | assets/k/kiwibrowser.net.png    |
| 007.com            | assets/0/007.com.png            |
| blogspot.com       | assets/b/blogspot.com.png       |
| test.blogspot.com  | assets/t/test.blogspot.com.png  |
| test2.blogspot.com | assets/t/test2.blogspot.com.png |
| gmail.com          | assets/g/gmail.com.png          |
| m.gmail.com        | assets/g/gmail.com.png          |


#### Shortcuts to upload new logos


 - [0](../../upload/main/assets/0) - [1](../../upload/main/assets/1) - [2](../../upload/main/assets/2) - [3](../../upload/main/assets/3) - [4](../../upload/main/assets/4) - [5](../../upload/main/assets/5) - [6](../../upload/main/assets/6) - [7](../../upload/main/assets/7) - [8](../../upload/main/assets/8) - [9](../../upload/main/assets/9)

 - [A](../../upload/main/assets/a) - [B](../../upload/main/assets/b) - [C](../../upload/main/assets/c) - [D](../../upload/main/assets/d) - [E](../../upload/main/assets/e) - [F](../../upload/main/assets/f) - [G](../../upload/main/assets/g) - [H](../../upload/main/assets/h) - [I](../../upload/main/assets/i) - [J](../../upload/main/assets/j) - [K](../../upload/main/assets/k) - [L](../../upload/main/assets/l) - [M](../../upload/main/assets/m) - [N](../../upload/main/assets/n) - [O](../../upload/main/assets/o) - [P](../../upload/main/assets/p) - [Q](../../upload/main/assets/q) - [R](../../upload/main/assets/r) - [S](../../upload/main/assets/s) - [T](../../upload/main/assets/t) - [U](../../upload/main/assets/u) - [V](../../upload/main/assets/v) - [W](../../upload/main/assets/w) - [X](../../upload/main/assets/x) - [Y](../../upload/main/assets/y) - [Z](../../upload/main/assets/z)
