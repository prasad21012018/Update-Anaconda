# Update-Anaconda

(base) C:\Windows\system32>conda update -n base -c defaults conda
Collecting package metadata (current_repodata.json): done
Solving environment: done

## Package Plan ##

  environment location: C:\ProgramData\Anaconda3

  added / updated specs:
    - conda


The following packages will be downloaded:

    package                    |            build
    ---------------------------|-----------------
    absl-py-0.8.1              |           py37_0         165 KB
    astor-0.8.0                |           py37_0          47 KB
    backports.functools_lru_cache-1.6.1|             py_0          11 KB
    conda-4.8.1                |           py37_0         2.8 MB
    future-0.18.2              |           py37_0         656 KB
    gast-0.2.2                 |           py37_0         155 KB
    google-pasta-0.1.8         |             py_0          43 KB
    grpcio-1.16.1              |   py37h351948d_1         850 KB
    keras-applications-1.0.8   |             py_0          33 KB
    keras-preprocessing-1.1.0  |             py_1          36 KB
    libgpuarray-0.7.6          |       hfa6e2cd_0         234 KB
    libprotobuf-3.11.2         |       h7bd577a_0         1.8 MB
    libpython-2.1              |           py37_0          47 KB
    m2w64-binutils-2.25.1      |                5        44.3 MB
    m2w64-bzip2-1.0.6          |                6         100 KB
    m2w64-crt-git-5.0.0.4636.2595836|                2         3.4 MB
    m2w64-gcc-5.3.0            |                6        41.1 MB
    m2w64-gcc-ada-5.3.0        |                6        33.5 MB
    m2w64-gcc-fortran-5.3.0    |                6        10.3 MB
    m2w64-gcc-objc-5.3.0       |                6        15.1 MB
    m2w64-headers-git-5.0.0.4636.c0ad18a|                2         5.6 MB
    m2w64-isl-0.16.1           |                2         655 KB
    m2w64-libiconv-1.14        |                6         1.5 MB
    m2w64-libmangle-git-5.0.0.4509.2e5a9a2|                2          21 KB
    m2w64-make-4.1.2351.a80a8b8|                2         116 KB
    m2w64-mpc-1.0.3            |                3          70 KB
    m2w64-mpfr-3.1.4           |                4         293 KB
    m2w64-pkg-config-0.29.1    |                2         469 KB
    m2w64-toolchain-5.3.0      |                7           2 KB
    m2w64-tools-git-5.0.0.4592.90b8472|                2         314 KB
    m2w64-windows-default-manifest-6.4|                3           3 KB
    m2w64-winpthreads-git-5.0.0.4634.697f757|                2          45 KB
    m2w64-zlib-1.2.8           |               10         197 KB
    mako-1.1.0                 |             py_0          60 KB
    markdown-3.1.1             |           py37_0         132 KB
    opt_einsum-3.1.0           |             py_0          54 KB
    protobuf-3.11.2            |   py37h33f27b4_0         544 KB
    pygpu-0.7.6                |   py37h452e1ab_0         459 KB
    termcolor-1.1.0            |           py37_1           8 KB
    theano-1.0.4               |           py37_0         3.2 MB
    ------------------------------------------------------------
                                           Total:       168.4 MB

The following NEW packages will be INSTALLED:

  libpython          pkgs/main/win-64::libpython-2.1-py37_0
  m2w64-binutils     pkgs/msys2/win-64::m2w64-binutils-2.25.1-5
  m2w64-bzip2        pkgs/msys2/win-64::m2w64-bzip2-1.0.6-6
  m2w64-crt-git      pkgs/msys2/win-64::m2w64-crt-git-5.0.0.4636.2595836-2
  m2w64-gcc          pkgs/msys2/win-64::m2w64-gcc-5.3.0-6
  m2w64-gcc-ada      pkgs/msys2/win-64::m2w64-gcc-ada-5.3.0-6
  m2w64-gcc-fortran  pkgs/msys2/win-64::m2w64-gcc-fortran-5.3.0-6
  m2w64-gcc-objc     pkgs/msys2/win-64::m2w64-gcc-objc-5.3.0-6
  m2w64-headers-git  pkgs/msys2/win-64::m2w64-headers-git-5.0.0.4636.c0ad18a-2
  m2w64-isl          pkgs/msys2/win-64::m2w64-isl-0.16.1-2
  m2w64-libiconv     pkgs/msys2/win-64::m2w64-libiconv-1.14-6
  m2w64-libmangle-g~ pkgs/msys2/win-64::m2w64-libmangle-git-5.0.0.4509.2e5a9a2-2
  m2w64-make         pkgs/msys2/win-64::m2w64-make-4.1.2351.a80a8b8-2
  m2w64-mpc          pkgs/msys2/win-64::m2w64-mpc-1.0.3-3
  m2w64-mpfr         pkgs/msys2/win-64::m2w64-mpfr-3.1.4-4
  m2w64-pkg-config   pkgs/msys2/win-64::m2w64-pkg-config-0.29.1-2
  m2w64-toolchain    pkgs/msys2/win-64::m2w64-toolchain-5.3.0-7
  m2w64-tools-git    pkgs/msys2/win-64::m2w64-tools-git-5.0.0.4592.90b8472-2
  m2w64-windows-def~ pkgs/msys2/win-64::m2w64-windows-default-manifest-6.4-3
  m2w64-winpthreads~ pkgs/msys2/win-64::m2w64-winpthreads-git-5.0.0.4634.697f757-2
  m2w64-zlib         pkgs/msys2/win-64::m2w64-zlib-1.2.8-10

The following packages will be REMOVED:

  vs2015_win-64-14.0.25420-h55c1224_11

The following packages will be UPDATED:

  astor                conda-forge/noarch::astor-0.7.1-py_0 --> pkgs/main/win-64::astor-0.8.0-py37_0
  backports.functoo~                               1.5-py_2 --> 1.6.1-py_0
  conda                     conda-forge::conda-4.8.0-py37_1 --> pkgs/main::conda-4.8.1-py37_0
  future                                      0.17.1-py37_0 --> 0.18.2-py37_0
  keras-preprocessi~ conda-forge::keras-preprocessing-1.1.~ --> pkgs/main::keras-preprocessing-1.1.0-py_1

The following packages will be SUPERSEDED by a higher-priority channel:

  absl-py                 conda-forge::absl-py-0.9.0-py37_0 --> pkgs/main::absl-py-0.8.1-py37_0
  gast                  conda-forge/noarch::gast-0.2.2-py_0 --> pkgs/main/win-64::gast-0.2.2-py37_0
  google-pasta                                  conda-forge --> pkgs/main
  grpcio             conda-forge::grpcio-1.23.0-py37h3db2c~ --> pkgs/main::grpcio-1.16.1-py37h351948d_1
  keras-applications conda-forge::keras-applications-1.0.8~ --> pkgs/main::keras-applications-1.0.8-py_0
  libgpuarray        conda-forge::libgpuarray-0.7.6-hfa6e2~ --> pkgs/main::libgpuarray-0.7.6-hfa6e2cd_0
  libprotobuf        conda-forge::libprotobuf-3.11.2-h1a1b~ --> pkgs/main::libprotobuf-3.11.2-h7bd577a_0
  mako                                          conda-forge --> pkgs/main
  markdown           conda-forge/noarch::markdown-3.1.1-py~ --> pkgs/main/win-64::markdown-3.1.1-py37_0
  opt_einsum                                    conda-forge --> pkgs/main
  protobuf           conda-forge::protobuf-3.11.2-py37he02~ --> pkgs/main::protobuf-3.11.2-py37h33f27b4_0
  pygpu              conda-forge::pygpu-0.7.6-py37hc8d92b1~ --> pkgs/main::pygpu-0.7.6-py37h452e1ab_0
  termcolor          conda-forge/noarch::termcolor-1.1.0-p~ --> pkgs/main/win-64::termcolor-1.1.0-py37_1
  theano             conda-forge::theano-1.0.4-py37h653833~ --> pkgs/main::theano-1.0.4-py37_0


Proceed ([y]/n)? y


Downloading and Extracting Packages
astor-0.8.0          | 47 KB     | ############################################################################ | 100%
m2w64-bzip2-1.0.6    | 100 KB    | ############################################################################ | 100%
m2w64-gcc-5.3.0      | 41.1 MB   | ############################################################################ | 100%
termcolor-1.1.0      | 8 KB      | ############################################################################ | 100%
pygpu-0.7.6          | 459 KB    | ############################################################################ | 100%
opt_einsum-3.1.0     | 54 KB     | ############################################################################ | 100%
mako-1.1.0           | 60 KB     | ############################################################################ | 100%
markdown-3.1.1       | 132 KB    | ############################################################################ | 100%
m2w64-binutils-2.25. | 44.3 MB   | ############################################################################ | 100%
google-pasta-0.1.8   | 43 KB     | ############################################################################ | 100%
m2w64-libmangle-git- | 21 KB     | ############################################################################ | 100%
theano-1.0.4         | 3.2 MB    | ############################################################################ | 100%
conda-4.8.1          | 2.8 MB    | ############################################################################ | 100%
m2w64-gcc-ada-5.3.0  | 33.5 MB   | ############################################################################ | 100%
libpython-2.1        | 47 KB     | ############################################################################ | 100%
m2w64-tools-git-5.0. | 314 KB    | ############################################################################ | 100%
future-0.18.2        | 656 KB    | ############################################################################ | 100%
m2w64-windows-defaul | 3 KB      | ############################################################################ | 100%
backports.functools_ | 11 KB     | ############################################################################ | 100%
protobuf-3.11.2      | 544 KB    | ############################################################################ | 100%
m2w64-zlib-1.2.8     | 197 KB    | ############################################################################ | 100%
m2w64-winpthreads-gi | 45 KB     | ############################################################################ | 100%
absl-py-0.8.1        | 165 KB    | ############################################################################ | 100%
m2w64-pkg-config-0.2 | 469 KB    | ############################################################################ | 100%
m2w64-mpc-1.0.3      | 70 KB     | ############################################################################ | 100%
keras-applications-1 | 33 KB     | ############################################################################ | 100%
m2w64-gcc-fortran-5. | 10.3 MB   | ############################################################################ | 100%
m2w64-libiconv-1.14  | 1.5 MB    | ############################################################################ | 100%
m2w64-mpfr-3.1.4     | 293 KB    | ############################################################################ | 100%
keras-preprocessing- | 36 KB     | ############################################################################ | 100%
m2w64-make-4.1.2351. | 116 KB    | ############################################################################ | 100%
m2w64-gcc-objc-5.3.0 | 15.1 MB   | ############################################################################ | 100%
grpcio-1.16.1        | 850 KB    | ############################################################################ | 100%
m2w64-headers-git-5. | 5.6 MB    | ############################################################################ | 100%
m2w64-crt-git-5.0.0. | 3.4 MB    | ############################################################################ | 100%
m2w64-isl-0.16.1     | 655 KB    | ############################################################################ | 100%
m2w64-toolchain-5.3. | 2 KB      | ############################################################################ | 100%
libprotobuf-3.11.2   | 1.8 MB    | ############################################################################ | 100%
gast-0.2.2           | 155 KB    | ############################################################################ | 100%
libgpuarray-0.7.6    | 234 KB    | ############################################################################ | 100%
Preparing transaction: done
Verifying transaction: done
Executing transaction: done

C:\Windows\system32>set "KERAS_BACKEND="

C:\Windows\system32>python C:\ProgramData\Anaconda3\etc\keras\load_config.py  1>temp.txt

C:\Windows\system32>set /p KERAS_BACKEND= 0<temp.txt

C:\Windows\system32>del temp.txt

C:\Windows\system32>python -c "import keras"  1>nul 2>&1

C:\Windows\system32>if errorlevel 1 (
ver  1>nul
 set "KERAS_BACKEND=theano"
 python -c "import keras"  1>nul 2>&1
)
