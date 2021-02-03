project('CppRealLifeExamples', 'c', 'cpp',
        default_options : ['cpp_std=c++2a'])


foreach proj : ['SimpleTest',]
  if not get_option(proj).disabled()
    subdir(proj)
  endif
endforeach