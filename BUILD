licenses(['notice'])

cc_library(
  name = "cryptopp",
  visibility = ['//visibility:public'],
  hdrs = glob([
    '*.h',
    '*.cpp',
  ]),
  srcs = [
    '3way.cpp',
    'adler32.cpp',
    'algebra.cpp',
    'algparam.cpp',
    'arc4.cpp',
    'asn.cpp',
    'authenc.cpp',
    'base32.cpp',
    'base64.cpp',
    'basecode.cpp',
    'bfinit.cpp',
    'blowfish.cpp',
    'blumshub.cpp',
    'camellia.cpp',
    'cast.cpp',
    'casts.cpp',
    'cbcmac.cpp',
    'ccm.cpp',
    'channels.cpp',
    'cmac.cpp',
    'cpu.cpp',
    'crc.cpp',
    'cryptlib_bds.cpp',
    'cryptlib.cpp',
    'default.cpp',
    'des.cpp',
    'dessp.cpp',
    'dh2.cpp',
    'dh.cpp',
    'dll.cpp',
    'dsa.cpp',
    'eax.cpp',
    'ec2n.cpp',
    'eccrypto.cpp',
    'ecp.cpp',
    'elgamal.cpp',
    'emsa2.cpp',
    'eprecomp.cpp',
    'esign.cpp',
    'files.cpp',
    'filters.cpp',
    'fips140.cpp',
    'fipstest.cpp',
    'gcm.cpp',
    'gf2_32.cpp',
    'gf256.cpp',
    'gf2n.cpp',
    'gfpcrypt.cpp',
    'gost.cpp',
    'gzip.cpp',
    'hex.cpp',
    'hmac.cpp',
    'hrtimer.cpp',
    'ida.cpp',
    'idea.cpp',
    'integer.cpp',
    'iterhash.cpp',
    'luc.cpp',
    'mars.cpp',
    'marss.cpp',
    'md2.cpp',
    'md4.cpp',
    'md5.cpp',
    'misc.cpp',
    'modes.cpp',
    'mqueue.cpp',
    'mqv.cpp',
    'nbtheory.cpp',
    'network.cpp',
    'oaep.cpp',
    'osrng.cpp',
    'panama.cpp',
    'pch.cpp',
    'pkcspad.cpp',
    'polynomi.cpp',
    'pssr.cpp',
    'pubkey.cpp',
    'queue.cpp',
    'rabin.cpp',
    'randpool.cpp',
    'rc2.cpp',
    'rc5.cpp',
    'rc6.cpp',
    'rdtables.cpp',
    'rijndael.cpp',
    'ripemd.cpp',
    'rng.cpp',
    'rsa.cpp',
    'rw.cpp',
    'safer.cpp',
    'salsa.cpp',
    'seal.cpp',
    'seed.cpp',
    'serpent.cpp',
    'sha3.cpp',
    'shacal2.cpp',
    'sha.cpp',
    'sharkbox.cpp',
    'shark.cpp',
    'simple.cpp',
    'skipjack.cpp',
    'socketft.cpp',
    'sosemanuk.cpp',
    'square.cpp',
    'squaretb.cpp',
    'strciphr.cpp',
    'tea.cpp',
    'tftables.cpp',
    'tiger.cpp',
    'tigertab.cpp',
    'trdlocal.cpp',
    'ttmac.cpp',
    'twofish.cpp',
    'vmac.cpp',
    'wait.cpp',
    'wake.cpp',
    'whrlpool.cpp',
    'winpipes.cpp',
    'xtr.cpp',
    'xtrcrypt.cpp',
    'zdeflate.cpp',
    'zinflate.cpp',
    'zlib.cpp'
  ],
  linkopts = [
    '-lm',
  ]
)

cc_binary(
  name = "cryptest",
  deps = [
    ':cryptopp',
    '//external:pthread',
  ],
  srcs = [
    'bench.cpp',
    'bench2.cpp',
    'test.cpp',
    'validat1.cpp',
    'validat2.cpp',
    'validat3.cpp',
    'adhoc.cpp',
    'datatest.cpp',
    'regtest.cpp',
    'fipsalgt.cpp',
    'dlltest.cpp',
  ],
  data = [
    'TestData',
    'TestVectors',
  ],
)
