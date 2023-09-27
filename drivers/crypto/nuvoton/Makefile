# SPDX-License-Identifier: GPL-2.0-only

ifeq ($(CONFIG_CRYPTO_DEV_NUVOTON),y)
	obj-$(CONFIG_CRYPTO_DEV_NUVOTON) += nuvoton-crypto.o
	obj-$(CONFIG_CRYPTO_ECDH) += nuvoton-ecc.o
	obj-$(CONFIG_CRYPTO_RSA) += nuvoton-rsa.o
	nuvoton-crypto-objs:= nuvoton-crypto.o nuvoton-prng.o nuvoton-aes.o nuvoton-sha.o
endif

ifeq ($(CONFIG_CRYPTO_DEV_MA35DZ),y)
	obj-$(CONFIG_CRYPTO_DEV_MA35DZ) += ma35dz-crypto.o
	obj-$(CONFIG_CRYPTO_ECDH) += ma35dz-ecc.o
	obj-$(CONFIG_CRYPTO_RSA) += ma35dz-rsa.o
	ma35dz-crypto-objs:= ma35dz-crypto.o ma35dz-prng.o ma35dz-aes.o ma35dz-sha.o
endif

ifeq ($(CONFIG_CRYPTO_DEV_MA35HZ),y)
	obj-$(CONFIG_CRYPTO_DEV_MA35HZ) += ma35hz-crypto.o
	obj-$(CONFIG_CRYPTO_ECDH) += ma35hz-ecc.o
	obj-$(CONFIG_CRYPTO_RSA) += ma35hz-rsa.o
	ma35hz-crypto-objs:= ma35hz-crypto.o ma35hz-prng.o ma35hz-aes.o ma35hz-sha.o
endif
