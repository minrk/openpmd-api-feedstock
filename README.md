About openpmd-api
=================

Home: https://www.openPMD.org

Package license: LGPL-3.0-or-later

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/openpmd-api-feedstock/blob/main/LICENSE.txt)

Summary: C++ & Python API for writing & reading (.h5, .bp, .json, ...), serial & MPI parallel openPMD files.

Development: https://github.com/openPMD/openPMD-api

Documentation: https://openpmd-api.readthedocs.io

This library provides a common high-level API for openPMD writing and
reading. It provides a common interface to I/O libraries and file formats
such as HDF5, ADIOS1, ADIOS2, and JSON.
Language bindings are provided for C++14 (or newer) and Python 3.
This conda-forge package provides serial and MPI-parallel I/O. Windows
support is limited to serial versions of HDF5, ADIOS2 and JSON.


Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64_mpimpichpython3.10.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_64_mpimpichpython3.10.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_mpimpichpython3.7.____73_pypypython_implpypy</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_64_mpimpichpython3.7.____73_pypypython_implpypy" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_mpimpichpython3.7.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_64_mpimpichpython3.7.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_mpimpichpython3.8.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_64_mpimpichpython3.8.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_mpimpichpython3.9.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_64_mpimpichpython3.9.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_mpinompipython3.10.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_64_mpinompipython3.10.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_mpinompipython3.7.____73_pypypython_implpypy</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_64_mpinompipython3.7.____73_pypypython_implpypy" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_mpinompipython3.7.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_64_mpinompipython3.7.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_mpinompipython3.8.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_64_mpinompipython3.8.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_mpinompipython3.9.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_64_mpinompipython3.9.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_mpiopenmpipython3.10.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_64_mpiopenmpipython3.10.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_mpiopenmpipython3.7.____73_pypypython_implpypy</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_64_mpiopenmpipython3.7.____73_pypypython_implpypy" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_mpiopenmpipython3.7.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_64_mpiopenmpipython3.7.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_mpiopenmpipython3.8.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_64_mpiopenmpipython3.8.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_mpiopenmpipython3.9.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_64_mpiopenmpipython3.9.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64_mpimpichpython3.10.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_aarch64_mpimpichpython3.10.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64_mpimpichpython3.7.____73_pypypython_implpypy</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_aarch64_mpimpichpython3.7.____73_pypypython_implpypy" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64_mpimpichpython3.7.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_aarch64_mpimpichpython3.7.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64_mpimpichpython3.8.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_aarch64_mpimpichpython3.8.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64_mpimpichpython3.9.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_aarch64_mpimpichpython3.9.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64_mpinompipython3.10.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_aarch64_mpinompipython3.10.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64_mpinompipython3.7.____73_pypypython_implpypy</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_aarch64_mpinompipython3.7.____73_pypypython_implpypy" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64_mpinompipython3.7.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_aarch64_mpinompipython3.7.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64_mpinompipython3.8.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_aarch64_mpinompipython3.8.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64_mpinompipython3.9.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_aarch64_mpinompipython3.9.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64_mpiopenmpipython3.10.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_aarch64_mpiopenmpipython3.10.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64_mpiopenmpipython3.7.____73_pypypython_implpypy</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_aarch64_mpiopenmpipython3.7.____73_pypypython_implpypy" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64_mpiopenmpipython3.7.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_aarch64_mpiopenmpipython3.7.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64_mpiopenmpipython3.8.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_aarch64_mpiopenmpipython3.8.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64_mpiopenmpipython3.9.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_aarch64_mpiopenmpipython3.9.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le_mpimpichpython3.10.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_ppc64le_mpimpichpython3.10.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le_mpimpichpython3.7.____73_pypypython_implpypy</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_ppc64le_mpimpichpython3.7.____73_pypypython_implpypy" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le_mpimpichpython3.7.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_ppc64le_mpimpichpython3.7.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le_mpimpichpython3.8.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_ppc64le_mpimpichpython3.8.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le_mpimpichpython3.9.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_ppc64le_mpimpichpython3.9.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le_mpinompipython3.10.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_ppc64le_mpinompipython3.10.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le_mpinompipython3.7.____73_pypypython_implpypy</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_ppc64le_mpinompipython3.7.____73_pypypython_implpypy" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le_mpinompipython3.7.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_ppc64le_mpinompipython3.7.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le_mpinompipython3.8.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_ppc64le_mpinompipython3.8.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le_mpinompipython3.9.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_ppc64le_mpinompipython3.9.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le_mpiopenmpipython3.10.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_ppc64le_mpiopenmpipython3.10.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le_mpiopenmpipython3.7.____73_pypypython_implpypy</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_ppc64le_mpiopenmpipython3.7.____73_pypypython_implpypy" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le_mpiopenmpipython3.7.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_ppc64le_mpiopenmpipython3.7.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le_mpiopenmpipython3.8.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_ppc64le_mpiopenmpipython3.8.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le_mpiopenmpipython3.9.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=linux&configuration=linux_ppc64le_mpiopenmpipython3.9.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_mpimpichpython3.10.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=osx&configuration=osx_64_mpimpichpython3.10.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_mpimpichpython3.7.____73_pypypython_implpypy</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=osx&configuration=osx_64_mpimpichpython3.7.____73_pypypython_implpypy" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_mpimpichpython3.7.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=osx&configuration=osx_64_mpimpichpython3.7.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_mpimpichpython3.8.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=osx&configuration=osx_64_mpimpichpython3.8.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_mpimpichpython3.9.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=osx&configuration=osx_64_mpimpichpython3.9.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_mpinompipython3.10.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=osx&configuration=osx_64_mpinompipython3.10.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_mpinompipython3.7.____73_pypypython_implpypy</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=osx&configuration=osx_64_mpinompipython3.7.____73_pypypython_implpypy" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_mpinompipython3.7.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=osx&configuration=osx_64_mpinompipython3.7.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_mpinompipython3.8.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=osx&configuration=osx_64_mpinompipython3.8.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_mpinompipython3.9.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=osx&configuration=osx_64_mpinompipython3.9.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_mpiopenmpipython3.10.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=osx&configuration=osx_64_mpiopenmpipython3.10.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_mpiopenmpipython3.7.____73_pypypython_implpypy</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=osx&configuration=osx_64_mpiopenmpipython3.7.____73_pypypython_implpypy" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_mpiopenmpipython3.7.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=osx&configuration=osx_64_mpiopenmpipython3.7.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_mpiopenmpipython3.8.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=osx&configuration=osx_64_mpiopenmpipython3.8.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_mpiopenmpipython3.9.____cpythonpython_implcpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=osx&configuration=osx_64_mpiopenmpipython3.9.____cpythonpython_implcpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64_mpimpichpython3.10.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=osx&configuration=osx_arm64_mpimpichpython3.10.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64_mpimpichpython3.8.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=osx&configuration=osx_arm64_mpimpichpython3.8.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64_mpimpichpython3.9.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=osx&configuration=osx_arm64_mpimpichpython3.9.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64_mpinompipython3.10.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=osx&configuration=osx_arm64_mpinompipython3.10.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64_mpinompipython3.8.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=osx&configuration=osx_arm64_mpinompipython3.8.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64_mpinompipython3.9.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=osx&configuration=osx_arm64_mpinompipython3.9.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64_mpiopenmpipython3.10.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=osx&configuration=osx_arm64_mpiopenmpipython3.10.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64_mpiopenmpipython3.8.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=osx&configuration=osx_arm64_mpiopenmpipython3.8.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64_mpiopenmpipython3.9.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=osx&configuration=osx_arm64_mpiopenmpipython3.9.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_python3.10.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=win&configuration=win_64_python3.10.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_python3.7.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=win&configuration=win_64_python3.7.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_python3.8.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=win&configuration=win_64_python3.8.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_python3.9.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=722&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/openpmd-api-feedstock?branchName=main&jobName=win&configuration=win_64_python3.9.____cpython" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-openpmd--api-green.svg)](https://anaconda.org/conda-forge/openpmd-api) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/openpmd-api.svg)](https://anaconda.org/conda-forge/openpmd-api) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/openpmd-api.svg)](https://anaconda.org/conda-forge/openpmd-api) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/openpmd-api.svg)](https://anaconda.org/conda-forge/openpmd-api) |

Installing openpmd-api
======================

Installing `openpmd-api` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
conda config --set channel_priority strict
```

Once the `conda-forge` channel has been enabled, `openpmd-api` can be installed with `conda`:

```
conda install openpmd-api
```

or with `mamba`:

```
mamba install openpmd-api
```

It is possible to list all of the versions of `openpmd-api` available on your platform with `conda`:

```
conda search openpmd-api --channel conda-forge
```

or with `mamba`:

```
mamba search openpmd-api --channel conda-forge
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search openpmd-api --channel conda-forge

# List packages depending on `openpmd-api`:
mamba repoquery whoneeds openpmd-api --channel conda-forge

# List dependencies of `openpmd-api`:
mamba repoquery depends openpmd-api --channel conda-forge
```


About conda-forge
=================

[![Powered by
NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](https://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[Azure](https://azure.microsoft.com/en-us/services/devops/), [GitHub](https://github.com/),
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/),
[Drone](https://cloud.drone.io/welcome), and [TravisCI](https://travis-ci.com/)
it is possible to build and upload installable packages to the
[conda-forge](https://anaconda.org/conda-forge) [Anaconda-Cloud](https://anaconda.org/)
channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating openpmd-api-feedstock
==============================

If you would like to improve the openpmd-api recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/openpmd-api-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@ax3l](https://github.com/ax3l/)
* [@franzpoeschel](https://github.com/franzpoeschel/)

