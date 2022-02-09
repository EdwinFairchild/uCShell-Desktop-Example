cc_library(
  name = "uCShell-main",
  srcs = ["main.c"],
  deps = ["@//:uCShell-lib" ],
)

cc_binary(
   name = "uCShell-bin",
   deps = [":uCShell-main" , "@//:uCShell-lib" ]
)
