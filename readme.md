<h1>Extensible Model Representation - XMR</h1>
<h3>Project Requirements</h3>
- git >=2.43.5 <br>
- cmake >=3.25.0 <br>
- C++ >=20 <br>
<h3>Initialize project</h3>
1. Run command: git submodule --init <br>
NOTE: If error in fetching xmr src code then you do not have access to the repo. The access to the unlicensed source code requires express permission from Lucas Vanderheijden and Jason Cisneros. Distribution of the unlicensed source code also requires explicit written approval by Lucas Vanderheijden and Jason Cisneros. To request access to  the pre-released, unlicensed version of xmr source code email lvanderheijden@scu.edu and jcisneros@scu.edu <br>
2. Configure CMake project: cmake -S ./xmr -B ./build <br>
3. Build project: cmake --build ./build 