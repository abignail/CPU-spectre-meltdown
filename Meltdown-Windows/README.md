Source from   https://twitter.com/pwnallthethings.
Project from  https://github.com/stormctf/Meltdown-PoC-Windows

Edit By William on VS2017

May be you should adjust the config 
1. Edit Meltdown.vcxproj
   > <Import Project="$(ProgramFiles)\MSBuild\Microsoft.Cpp\v4.0\V120\BuildCustomizations\masm.props" \/>

   >  <Import Project="$(ProgramFiles)\Microsoft Visual Studio\2017\Enterprise\Common7\IDE\VC\VCTargets\BuildCustomizations\masm.targets" \/>

   Change the path of "masm.props" and "masm.targets".
