set(LLVM_LINK_COMPONENTS
  DebugInfoDWARF
  Object
  ObjectYAML
  Support
  )

add_llvm_tool(obj2yaml
  obj2yaml.cpp
  coff2yaml.cpp
  elf2yaml.cpp
  macho2yaml.cpp
  Error.cpp
  )
