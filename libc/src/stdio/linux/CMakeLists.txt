add_entrypoint_object(
  remove
  SRCS
    remove.cpp
  HDRS
    ../remove.h
  DEPENDS
    libc.include.fcntl
    libc.include.stdio
    libc.include.unistd
    libc.include.sys_syscall
    libc.src.__support.OSUtil.osutil
    libc.src.errno.errno
)
