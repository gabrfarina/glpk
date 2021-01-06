cc_library(
  name = 'glpk',
  srcs = glob(
    [
    'src/*.c',
    'src/**/*.c'
    ]
  ),
  hdrs = glob(
    [
    'src/*.h',
    'src/**/*.h'
    ]
  ),
  copts = [
    '-Iexternal/glpk/src/',
    '-Iexternal/glpk/src/misc',
    '-Iexternal/glpk/src/simplex',
    '-Iexternal/glpk/src/amd',
    '-Iexternal/glpk/src/bflib',
    '-Iexternal/glpk/src/env',
    '-Iexternal/glpk/src/cglib',
    '-Iexternal/glpk/src/mpl',
    '-Iexternal/glpk/src/proxy',
    '-Iexternal/glpk/src/api',
    '-Iexternal/glpk/src/colamd',
    '-Iexternal/glpk/src/minisat',
    '-Iexternal/glpk/src/zlib',
  ],
  visibility = ['//visibility:public'],
)
