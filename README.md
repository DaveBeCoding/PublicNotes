# PublicNotes
![img](/images/sampleOutputReact.png)











$ ctest -S ${SPACK_ROOT}/share/spack/setup-tests.cmake \
        -D build_dir=. \
        -D trilinos_source_dir=${SPACK_ROOT}/var/spack/repos/spack/packages/trilinos/v13.0.1.a6/source \
        -D trilinos_build_dir=${SPACK_ROOT}/var/spack/repos/spack/packages/trilinos/v13.0.1.a6/build \
        -D trilinos_install_dir=${SPACK_ROOT}/opt/spack/linux-centos7-x86_64/gcc-8.4.0/trilinos-13.0.1.a6-lcvdztmgv7aljgsifz35b76an2lbccj3 \
        -D test_command='ctest --output-on-failure' \
        -VV





















