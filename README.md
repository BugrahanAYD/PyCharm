install openai

when ı try to install openai always ı have same problem with

ı install microsoft visual c++ but ı dont know how can ı use for this files 

-_-

















Collecting openai
  Using cached openai-0.28.1-py3-none-any.whl.metadata (11 kB)
Requirement already satisfied: requests>=2.20 in c:\users\mehme\pycharmprojects\pythonproject\venv\lib\site-packages (from openai) (2.31.0)
Collecting tqdm (from openai)
  Using cached tqdm-4.66.1-py3-none-any.whl.metadata (57 kB)
Collecting aiohttp (from openai)
  Using cached aiohttp-3.8.6.tar.gz (7.4 MB)
  Installing build dependencies: started
  Installing build dependencies: finished with status 'done'
  Getting requirements to build wheel: started
  Getting requirements to build wheel: finished with status 'done'
  Installing backend dependencies: started
  Installing backend dependencies: finished with status 'done'
  Preparing metadata (pyproject.toml): started
  Preparing metadata (pyproject.toml): finished with status 'done'
Requirement already satisfied: charset-normalizer<4,>=2 in c:\users\mehme\pycharmprojects\pythonproject\venv\lib\site-packages (from requests>=2.20->openai) (3.3.1)
Requirement already satisfied: idna<4,>=2.5 in c:\users\mehme\pycharmprojects\pythonproject\venv\lib\site-packages (from requests>=2.20->openai) (3.4)
Requirement already satisfied: urllib3<3,>=1.21.1 in c:\users\mehme\pycharmprojects\pythonproject\venv\lib\site-packages (from requests>=2.20->openai) (2.0.7)
Requirement already satisfied: certifi>=2017.4.17 in c:\users\mehme\pycharmprojects\pythonproject\venv\lib\site-packages (from requests>=2.20->openai) (2023.7.22)
Collecting attrs>=17.3.0 (from aiohttp->openai)
  Using cached attrs-23.1.0-py3-none-any.whl (61 kB)
Collecting multidict<7.0,>=4.5 (from aiohttp->openai)
  Using cached multidict-6.0.4.tar.gz (51 kB)
  Installing build dependencies: started
  Installing build dependencies: finished with status 'done'
  Getting requirements to build wheel: started
  Getting requirements to build wheel: finished with status 'done'
  Installing backend dependencies: started
  Installing backend dependencies: finished with status 'done'
  Preparing metadata (pyproject.toml): started
  Preparing metadata (pyproject.toml): finished with status 'done'
Collecting async-timeout<5.0,>=4.0.0a3 (from aiohttp->openai)
  Using cached async_timeout-4.0.3-py3-none-any.whl.metadata (4.2 kB)
Collecting yarl<2.0,>=1.0 (from aiohttp->openai)
  Using cached yarl-1.9.2.tar.gz (184 kB)
  Installing build dependencies: started
  Installing build dependencies: finished with status 'done'
  Getting requirements to build wheel: started
  Getting requirements to build wheel: finished with status 'done'
  Preparing metadata (pyproject.toml): started
  Preparing metadata (pyproject.toml): finished with status 'done'
Collecting frozenlist>=1.1.1 (from aiohttp->openai)
  Using cached frozenlist-1.4.0.tar.gz (90 kB)
  Installing build dependencies: started
  Installing build dependencies: finished with status 'done'
  Getting requirements to build wheel: started
  Getting requirements to build wheel: finished with status 'done'
  Preparing metadata (pyproject.toml): started
  Preparing metadata (pyproject.toml): finished with status 'done'
Collecting aiosignal>=1.1.2 (from aiohttp->openai)
  Using cached aiosignal-1.3.1-py3-none-any.whl (7.6 kB)
Requirement already satisfied: colorama in c:\users\mehme\pycharmprojects\pythonproject\venv\lib\site-packages (from tqdm->openai) (0.4.6)
Using cached openai-0.28.1-py3-none-any.whl (76 kB)
Using cached tqdm-4.66.1-py3-none-any.whl (78 kB)
Using cached async_timeout-4.0.3-py3-none-any.whl (5.7 kB)
Building wheels for collected packages: aiohttp, frozenlist, multidict, yarl
  Building wheel for aiohttp (pyproject.toml): started
  Building wheel for aiohttp (pyproject.toml): finished with status 'error'
  Building wheel for frozenlist (pyproject.toml): started
  Building wheel for frozenlist (pyproject.toml): finished with status 'error'
  Building wheel for multidict (pyproject.toml): started
  Building wheel for multidict (pyproject.toml): finished with status 'error'
  Building wheel for yarl (pyproject.toml): started
  Building wheel for yarl (pyproject.toml): finished with status 'error'
Failed to build aiohttp frozenlist multidict yarl

  error: subprocess-exited-with-error
  
  Building wheel for aiohttp (pyproject.toml) did not run successfully.
  exit code: 1
  
  [94 lines of output]
  *********************
  * Accelerated build *
  *********************
  running bdist_wheel
  running build
  running build_py
  creating build
  creating build\lib.win-amd64-cpython-312
  creating build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\abc.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\base_protocol.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\client.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\client_exceptions.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\client_proto.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\client_reqrep.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\client_ws.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\connector.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\cookiejar.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\formdata.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\hdrs.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\helpers.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\http.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\http_exceptions.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\http_parser.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\http_websocket.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\http_writer.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\locks.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\log.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\multipart.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\payload.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\payload_streamer.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\pytest_plugin.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\resolver.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\streams.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\tcp_helpers.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\test_utils.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\tracing.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\typedefs.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\web.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\web_app.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\web_exceptions.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\web_fileresponse.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\web_log.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\web_middlewares.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\web_protocol.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\web_request.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\web_response.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\web_routedef.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\web_runner.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\web_server.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\web_urldispatcher.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\web_ws.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\worker.py -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\__init__.py -> build\lib.win-amd64-cpython-312\aiohttp
  running egg_info
  writing aiohttp.egg-info\PKG-INFO
  writing dependency_links to aiohttp.egg-info\dependency_links.txt
  writing requirements to aiohttp.egg-info\requires.txt
  writing top-level names to aiohttp.egg-info\top_level.txt
  reading manifest file 'aiohttp.egg-info\SOURCES.txt'
  reading manifest template 'MANIFEST.in'
  warning: no files found matching 'aiohttp' anywhere in distribution
  warning: no previously-included files matching '*.pyc' found anywhere in distribution
  warning: no previously-included files matching '*.pyd' found anywhere in distribution
  warning: no previously-included files matching '*.so' found anywhere in distribution
  warning: no previously-included files matching '*.lib' found anywhere in distribution
  warning: no previously-included files matching '*.dll' found anywhere in distribution
  warning: no previously-included files matching '*.a' found anywhere in distribution
  warning: no previously-included files matching '*.obj' found anywhere in distribution
  warning: no previously-included files found matching 'aiohttp\*.html'
  no previously-included directories found matching 'docs\_build'
  adding license file 'LICENSE.txt'
  writing manifest file 'aiohttp.egg-info\SOURCES.txt'
  copying aiohttp\_cparser.pxd -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\_find_header.pxd -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\_headers.pxi -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\_helpers.pyi -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\_helpers.pyx -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\_http_parser.pyx -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\_http_writer.pyx -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\_websocket.pyx -> build\lib.win-amd64-cpython-312\aiohttp
  copying aiohttp\py.typed -> build\lib.win-amd64-cpython-312\aiohttp
  creating build\lib.win-amd64-cpython-312\aiohttp\.hash
  copying aiohttp\.hash\_cparser.pxd.hash -> build\lib.win-amd64-cpython-312\aiohttp\.hash
  copying aiohttp\.hash\_find_header.pxd.hash -> build\lib.win-amd64-cpython-312\aiohttp\.hash
  copying aiohttp\.hash\_helpers.pyi.hash -> build\lib.win-amd64-cpython-312\aiohttp\.hash
  copying aiohttp\.hash\_helpers.pyx.hash -> build\lib.win-amd64-cpython-312\aiohttp\.hash
  copying aiohttp\.hash\_http_parser.pyx.hash -> build\lib.win-amd64-cpython-312\aiohttp\.hash
  copying aiohttp\.hash\_http_writer.pyx.hash -> build\lib.win-amd64-cpython-312\aiohttp\.hash
  copying aiohttp\.hash\_websocket.pyx.hash -> build\lib.win-amd64-cpython-312\aiohttp\.hash
  copying aiohttp\.hash\hdrs.py.hash -> build\lib.win-amd64-cpython-312\aiohttp\.hash
  running build_ext
  building 'aiohttp._websocket' extension
  error: Microsoft Visual C++ 14.0 or greater is required. Get it with "Microsoft C++ Build Tools": https://visualstudio.microsoft.com/visual-cpp-build-tools/
  [end of output]
  
  note: This error originates from a subprocess, and is likely not a problem with pip.
  ERROR: Failed building wheel for aiohttp
  error: subprocess-exited-with-error
  
  Building wheel for frozenlist (pyproject.toml) did not run successfully.
  exit code: 1
  
  [33 lines of output]
  *********************
  * Accelerated build *
  *********************
  running bdist_wheel
  running build
  running build_py
  creating build
  creating build\lib.win-amd64-cpython-312
  creating build\lib.win-amd64-cpython-312\frozenlist
  copying frozenlist\__init__.py -> build\lib.win-amd64-cpython-312\frozenlist
  running egg_info
  writing frozenlist.egg-info\PKG-INFO
  writing dependency_links to frozenlist.egg-info\dependency_links.txt
  writing top-level names to frozenlist.egg-info\top_level.txt
  reading manifest file 'frozenlist.egg-info\SOURCES.txt'
  reading manifest template 'MANIFEST.in'
  warning: no previously-included files matching '*.pyc' found anywhere in distribution
  warning: no previously-included files matching '*.pyd' found anywhere in distribution
  warning: no previously-included files matching '*.so' found anywhere in distribution
  warning: no previously-included files matching '*.lib' found anywhere in distribution
  warning: no previously-included files matching '*.dll' found anywhere in distribution
  warning: no previously-included files matching '*.a' found anywhere in distribution
  warning: no previously-included files matching '*.obj' found anywhere in distribution
  warning: no previously-included files found matching 'frozenlist\*.html'
  no previously-included directories found matching 'docs\_build'
  adding license file 'LICENSE'
  writing manifest file 'frozenlist.egg-info\SOURCES.txt'
  copying frozenlist\__init__.pyi -> build\lib.win-amd64-cpython-312\frozenlist
  copying frozenlist\_frozenlist.pyx -> build\lib.win-amd64-cpython-312\frozenlist
  copying frozenlist\py.typed -> build\lib.win-amd64-cpython-312\frozenlist
  running build_ext
  building 'frozenlist._frozenlist' extension
  error: Microsoft Visual C++ 14.0 or greater is required. Get it with "Microsoft C++ Build Tools": https://visualstudio.microsoft.com/visual-cpp-build-tools/
  [end of output]
  
  note: This error originates from a subprocess, and is likely not a problem with pip.
  ERROR: Failed building wheel for frozenlist
  error: subprocess-exited-with-error
  
  Building wheel for multidict (pyproject.toml) did not run successfully.
  exit code: 1
  
  [74 lines of output]
  *********************
  * Accelerated build *
  *********************
  running bdist_wheel
  running build
  running build_py
  creating build
  creating build\lib.win-amd64-cpython-312
  creating build\lib.win-amd64-cpython-312\multidict
  copying multidict\_abc.py -> build\lib.win-amd64-cpython-312\multidict
  copying multidict\_compat.py -> build\lib.win-amd64-cpython-312\multidict
  copying multidict\_multidict_base.py -> build\lib.win-amd64-cpython-312\multidict
  copying multidict\_multidict_py.py -> build\lib.win-amd64-cpython-312\multidict
  copying multidict\__init__.py -> build\lib.win-amd64-cpython-312\multidict
  running egg_info
  writing multidict.egg-info\PKG-INFO
  writing dependency_links to multidict.egg-info\dependency_links.txt
  writing top-level names to multidict.egg-info\top_level.txt
  reading manifest file 'multidict.egg-info\SOURCES.txt'
  reading manifest template 'MANIFEST.in'
  warning: no previously-included files matching '*.pyc' found anywhere in distribution
  warning: no previously-included files found matching 'multidict\_multidict.html'
  warning: no previously-included files found matching 'multidict\*.so'
  warning: no previously-included files found matching 'multidict\*.pyd'
  warning: no previously-included files found matching 'multidict\*.pyd'
  no previously-included directories found matching 'docs\_build'
  adding license file 'LICENSE'
  writing manifest file 'multidict.egg-info\SOURCES.txt'
  C:\Users\mehme\AppData\Local\Temp\pip-build-env-nwmhwdtr\overlay\Lib\site-packages\setuptools\command\build_py.py:204: _Warning: Package 'multidict._multilib' is absent from the `packages` configuration.
  !!
  
          ********************************************************************************
          ############################
          # Package would be ignored #
          ############################
          Python recognizes 'multidict._multilib' as an importable package[^1],
          but it is absent from setuptools' `packages` configuration.
  
          This leads to an ambiguous overall configuration. If you want to distribute this
          package, please make sure that 'multidict._multilib' is explicitly added
          to the `packages` configuration field.
  
          Alternatively, you can also rely on setuptools' discovery methods
          (for example by using `find_namespace_packages(...)`/`find_namespace:`
          instead of `find_packages(...)`/`find:`).
  
          You can read more about "package discovery" on setuptools documentation page:
  
          - https://setuptools.pypa.io/en/latest/userguide/package_discovery.html
  
          If you don't want 'multidict._multilib' to be distributed and are
          already explicitly excluding 'multidict._multilib' via
          `find_namespace_packages(...)/find_namespace` or `find_packages(...)/find`,
          you can try to use `exclude_package_data`, or `include-package-data=False` in
          combination with a more fine grained `package-data` configuration.
  
          You can read more about "package data files" on setuptools documentation page:
  
          - https://setuptools.pypa.io/en/latest/userguide/datafiles.html
  
  
          [^1]: For Python, any directory (with suitable naming) can be imported,
                even if it does not contain any `.py` files.
                On the other hand, currently there is no concept of package data
                directory, all directories are treated like packages.
          ********************************************************************************
  
  !!
    check.warn(importable)
  copying multidict\__init__.pyi -> build\lib.win-amd64-cpython-312\multidict
  copying multidict\py.typed -> build\lib.win-amd64-cpython-312\multidict
  running build_ext
  building 'multidict._multidict' extension
  error: Microsoft Visual C++ 14.0 or greater is required. Get it with "Microsoft C++ Build Tools": https://visualstudio.microsoft.com/visual-cpp-build-tools/
  [end of output]
  
  note: This error originates from a subprocess, and is likely not a problem with pip.
  ERROR: Failed building wheel for multidict
  error: subprocess-exited-with-error
  
  Building wheel for yarl (pyproject.toml) did not run successfully.
  exit code: 1
  
  [49 lines of output]
  C:\Users\mehme\AppData\Local\Temp\pip-build-env-igiziucl\overlay\Lib\site-packages\setuptools\config\setupcfg.py:293: _DeprecatedConfig: Deprecated config in `setup.cfg`
  !!
  
          ********************************************************************************
          The license_file parameter is deprecated, use license_files instead.
  
          By 2023-Oct-30, you need to update your project and remove deprecated calls
          or your builds will no longer be supported.
  
          See https://setuptools.pypa.io/en/latest/userguide/declarative_config.html for details.
          ********************************************************************************
  
  !!
    parsed = self.parsers.get(option_name, lambda x: x)(value)
  **********************
  * Accelerated build *
  **********************
  running bdist_wheel
  running build
  running build_py
  creating build
  creating build\lib.win-amd64-cpython-312
  creating build\lib.win-amd64-cpython-312\yarl
  copying yarl\_quoting.py -> build\lib.win-amd64-cpython-312\yarl
  copying yarl\_quoting_py.py -> build\lib.win-amd64-cpython-312\yarl
  copying yarl\_url.py -> build\lib.win-amd64-cpython-312\yarl
  copying yarl\__init__.py -> build\lib.win-amd64-cpython-312\yarl
  running egg_info
  writing yarl.egg-info\PKG-INFO
  writing dependency_links to yarl.egg-info\dependency_links.txt
  writing requirements to yarl.egg-info\requires.txt
  writing top-level names to yarl.egg-info\top_level.txt
  reading manifest file 'yarl.egg-info\SOURCES.txt'
  reading manifest template 'MANIFEST.in'
  warning: no previously-included files matching '*.pyc' found anywhere in distribution
  warning: no previously-included files matching '*.cache' found anywhere in distribution
  warning: no previously-included files found matching 'yarl\*.html'
  warning: no previously-included files found matching 'yarl\*.so'
  warning: no previously-included files found matching 'yarl\*.pyd'
  no previously-included directories found matching 'docs\_build'
  adding license file 'LICENSE'
  writing manifest file 'yarl.egg-info\SOURCES.txt'
  copying yarl\__init__.pyi -> build\lib.win-amd64-cpython-312\yarl
  copying yarl\_quoting_c.pyi -> build\lib.win-amd64-cpython-312\yarl
  copying yarl\_quoting_c.pyx -> build\lib.win-amd64-cpython-312\yarl
  copying yarl\py.typed -> build\lib.win-amd64-cpython-312\yarl
  running build_ext
  building 'yarl._quoting_c' extension
  error: Microsoft Visual C++ 14.0 or greater is required. Get it with "Microsoft C++ Build Tools": https://visualstudio.microsoft.com/visual-cpp-build-tools/
  [end of output]
  
  note: This error originates from a subprocess, and is likely not a problem with pip.
  ERROR: Failed building wheel for yarl
ERROR: Could not build wheels for aiohttp, frozenlist, multidict, yarl, which is required to install pyproject.toml-based projects

 
 
