# Requirements
* You need `pyjks` package to use this script.

    ```
    pip install pyjks
    ```

# ebsDecrypt.py
* Script can decrypt EBS users passwords in case `apps` user passwords is known. It handles `new` (SHA-1 + 3DES) and `old` (SHA-1-like + ARC4) encryptions.

# Usage
* `apps` user password should be uppercase.

    ```
    $ ebsDecrypt.py -k APPS -d ZH4715DC7E9C2213F7CD56D44CE1CB8625FB71D0F4935EFEAE5B8CA66117B9C2D6A1E733BA80005F4CD19706A03218E8C5E4
    ```

* Special thanks to Mathieu [@gelim](https://twitter.com/gelim) and Bob [@NewFranny](https://twitter.com/NewFranny)