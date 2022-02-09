#this library depends on uCShell cc_library
cc_library(
  name = "uCShell-main",
  srcs = ["main.c"],
  deps = ["//uCShell:uCShell-lib" ],
)
# this binary depends on the above cc_library and on the uCShell cc_library 
cc_binary(
   name = "uCShell-bin",
   deps = [":uCShell-main" , "//uCShell:uCShell-lib" ]
)
