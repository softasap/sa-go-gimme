sa-go-gimme
===========

[![Build Status](https://travis-ci.org/softasap/sa-go-gimme.svg?branch=master)](https://travis-ci.org/softasap/sa-go-gimme)

Installs travis go version manager (gimme). Suitable for development. For binary installation see sa-go role.


Usage example:

```YAML


     - {
         role: "sa-go-gimme",
       }


```

```YAML

     - {

         role: "sa-go-gimme",
       }

```


Usage with ansible galaxy workflow
----------------------------------

If you installed the sa-go-gimme role using the command

`
   ansible-galaxy install softasap.sa_go_gimme
`

the role will be available in the folder library/softasap.sa_go_gimme
Please adjust the path accordingly.

```YAML

     - {
         role: "softasap.sa_go_gimme"
       }

```




Copyright and license
---------------------


Code licensed under the [BSD 3 clause] (https://opensource.org/licenses/BSD-3-Clause) or the [MIT License] (http://opensource.org/licenses/MIT).

Subscribe for roles updates at [FB] (https://www.facebook.com/SoftAsap/)

Join gitter discussion channel at [Gitter](https://gitter.im/softasap)
