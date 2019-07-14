# python-crfpp
## CRF++ In Python Interface ( For Windows )
* Use `Python 3.7`
* Must use `32-bit` (`64-bit` can not be used, the reason is unknown.)

* [Download CRF++ Package for Windows ( CRF++-0.58.zip )  and Linux ( CRF++-0.58.tar.gz or crfpp)] 
     * https://taku910.github.io/crfpp/

    * In Windows package [/CRF++-0.58/sdk/](/CRF++-0.58/sdk/)
        * `crfpp.h`
        *  rename `crfpp.lib` by `libcrfpp.lib`
    * In Windows package [/CRF++-0.58/](/CRF++-0.58/)
        * `libcrfpp.dll`
    *  In [/pthreads-w32-2-9-1-release/Pre-built.2/lib/x64/](/pthreads-w32-2-9-1-release/Pre-built.2/lib/x64/)
        * rename `pthread.lib` by `pthreadVC2.lib`
