# libiconv for Windows
----------------------
![MSBuild](https://github.com/pffang/libiconv-for-Windows/actions/workflows/msbuild.yml/badge.svg)

`libiconv` for Windows (Microsoft Visual Studio Compiler) based on [GNU libiconv][1]

Solution file update to Visual Studio 2022 only.

Update to libiconv `1.17`.

# Supported Builds

<table>
    <thead>
        <tr>
            <th><center>Architecture(s)</center></th>
            <th><center>Configuration(s)</center></th>
            <th><center>Comment(s)</center></th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan=4><center>Win32</center></td>
            <td><center><code>Release</code></center></td>
            <td>The release dynamic linked-library (DLL) and static library (LIB).</td>
        </tr>
        <tr>
            <td><center><code>ReleaseStatic</code></center></td>
            <td>The release static library (LIB) only.</td>
        </tr>
        <tr>
            <td><center><code>Debug</code></center></td>
            <td>The debug dynamic linked-library (DLL) and static library (LIB).</td>
        </tr>
        <tr>
            <td><center><code>DebugStatic</code></center></td>
            <td>The debug static library (LIB) only.</td>
        </tr>
    </tbody>
    <tbody>
        <tr>
            <td rowspan=4><center>x64</center></td>
            <td><center><code>Release</code></center></td>
            <td>The release dynamic linked-library (DLL) and static library (LIB).</td>
        </tr>
        <tr>
            <td><center><code>ReleaseStatic</code></center></td>
            <td>The release static library (LIB) only.</td>
        </tr>
        <tr>
            <td><center><code>Debug</code></center></td>
            <td>The debug dynamic linked-library (DLL) and static library (LIB).</td>
        </tr>
        <tr>
            <td><center><code>DebugStatic</code></center></td>
            <td>The debug static library (LIB) only.</td>
        </tr>
    </tbody>
    <tbody>
        <tr>
            <td rowspan=4><center>ARM64</center></td>
            <td><center><code>Release</code></center></td>
            <td>The release dynamic linked-library (DLL) and static library (LIB).</td>
        </tr>
        <tr>
            <td><center><code>ReleaseStatic</code></center></td>
            <td>The release static library (LIB) only.</td>
        </tr>
        <tr>
            <td><center><code>Debug</code></center></td>
            <td>The debug dynamic linked-library (DLL) and static library (LIB).</td>
        </tr>
        <tr>
            <td><center><code>DebugStatic</code></center></td>
            <td>The debug static library (LIB) only.</td>
        </tr>
    </tbody>
</table>

----------------------
## Licensing

Depend on GNU libiconv [LGPL3.0][3] 

[1]: https://www.gnu.org/software/libiconv
[2]: http://www.codeproject.com/Articles/302012/How-to-Build-libiconv-with-Microsoft-Visual-Studio
[3]: https://www.gnu.org/licenses/lgpl.html

