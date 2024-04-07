use_relative_paths = True

vars = {
  'github': 'https://github.com',

  'abseil_revision': '79ca5d7aad63973c83a4962a66ab07cd623131ea',

  'effcee_revision': '19b4aa87af25cb4ee779a071409732f34bfc305c',

  'googletest_revision': 'f10e11fb27301fba21caa71030bb5024e67aa135',

  # Use protobufs before they gained the dependency on abseil
  'protobuf_revision': 'v21.12',

  're2_revision': 'ac82d4f628a2045d89964ae11c48403d3b091af1',
  'spirv_headers_revision': '4f7b471f1a66b6d06462cd4ba57628cc0cd087d7',
}

deps = {
  'external/abseil_cpp':
      Var('github') + '/abseil/abseil-cpp.git@' + Var('abseil_revision'),

  'external/effcee':
      Var('github') + '/google/effcee.git@' + Var('effcee_revision'),

  'external/googletest':
      Var('github') + '/google/googletest.git@' + Var('googletest_revision'),

  'external/protobuf':
      Var('github') + '/protocolbuffers/protobuf.git@' + Var('protobuf_revision'),

  'external/re2':
      Var('github') + '/google/re2.git@' + Var('re2_revision'),

  'external/spirv-headers':
      Var('github') +  '/KhronosGroup/SPIRV-Headers.git@' +
          Var('spirv_headers_revision'),
}

