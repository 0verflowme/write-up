# CTF write-ups

CTF write-ups written by me. Mostly crypto!

## 2020

- **nullcon HackIM 2020**
    - Crypto 419 - SecureLinearFunctionEvaluation - [Writeup](https://github.com/pcw109550/write-up/tree/master/2020/HackTM/SecureLinearFunctionEvaluation)
        - Break Bellare-Micali OT by simple math
- **WhiteHat Grand Pix 06 Quals**
    - Crypto 200 - Cryptography 01 - [Writeup](https://github.com/pcw109550/write-up/tree/master/2020/WhiteHat_GrandPrix/Cryptography_01)
        - Simple substitution cipher.

## 2019

- **Christmas CTF 2019**
	- Crypto 1000 - hide and seek - [Writeup](https://github.com/pcw109550/write-up/tree/master/2019/X-MAS/hide_and_seek)
		- Solving hidden number problem + Coppersmith's attack on partial `p` exposure on RSA.
	- Crypto 995 - christmas pockets - [Writeup](https://github.com/pcw109550/write-up/tree/master/2019/X-MAS/christmas_pockets)
		- Classical knapsack cryptosystem is vulnerable to low density attack.
- **HITCON CTF 2019 Quals**
	- Crypto 200 - Lost Modulus Again - [Writeup](https://github.com/pcw109550/write-up/tree/master/2019/HITCON/Lost_Modulus_Again)
		- Recover `n` to decrypt the flag since `d` is given.
	- Crypto 200 - Very Simple Haskell - [Writeup](https://github.com/pcw109550/write-up/tree/master/2019/HITCON/Very_Simple_Haskell)
		- Decrypt Naccache-Stern Knapsack problem by directly knowing the private key.
- **KAPO 2019**
	- Crypto 1 - Lenstra-Lenstra-Lovasz - [Writeup](https://github.com/pcw109550/write-up/tree/master/2019/KAPO/Lenstra-Lenstra-Lovasz)
		- Recover `dp` by using Coppersmith's attack, and recover `p`.
	- Crypto 1 - Weak-Strong - [Writeup](https://github.com/pcw109550/write-up/tree/master/2019/KAPO/Weak-Strong)
		- ROCA attack.
- **CSAW CTF Qualification Round 2019**
	- Crypto 400 - Fault Box - [Writeup](https://github.com/pcw109550/write-up/tree/master/2019/CSAW/Fault_Box)
		- Fault attack on RSA CRT with a slight twist.
	- Crypto 300 - SuperCurve - [Writeup](https://github.com/pcw109550/write-up/tree/master/2019/CSAW/SuperCurve)
		- Solving ECDLP when order is small.
	- Crypto 100 - count on me - [Writeup](https://github.com/pcw109550/write-up/tree/master/2019/CSAW/count_on_me)
		- Misdesigned block cipher leads to information leakage.
- **Affinity CTF 2019 Quals**
	- Crypto 500 - Epic Poem - [Writeup](https://github.com/pcw109550/write-up/tree/master/2019/Affinity/Epic_Poem)
		- XOR encryption, guessing based on flag format.
	- Crypto 350 - GolanG Heights - [Writeup](https://github.com/pcw109550/write-up/tree/master/2019/Affinity/GolanG_Heights)
		- Solve quartic equation to factor `n` on RSA.
- **HackCon 2019**
	- Crypto 467 - AgainAndAgainAndAgain - [Writeup](https://github.com/pcw109550/write-up/tree/master/2019/HackCon/AgainAndAgainAndAgain)
		- Multiple encryption with Rabin cryptosystem.
- **Crypto CTF 2019**
	- Crypto 314 - NSA basement - [Writeup](https://github.com/pcw109550/write-up/tree/master/2019/CryptoCTF/NSA_basement)
		- Factoring `n` using gcd, decryption with OAEP on multiprime condition.
	- Crypto 166 - Alone in the dark - [Writeup](https://github.com/pcw109550/write-up/tree/master/2019/CryptoCTF/Alone_in_the_dark)
		- Solving pellian equation.
- **ISITDTU CTF 2019 Quals**
	- Crypto 304 - Chaos - [Writeup](https://github.com/pcw109550/write-up/tree/master/2019/ISITDTU/Chaos)
		- Simple substitution cipher.
	- Crypto 100 - Easy RSA 1 - [Writeup](https://github.com/pcw109550/write-up/tree/master/2019/ISITDTU/Easy_RSA_1)
		- `n` and `e` have similar size, so apply Boneh-Durfee attack.
	- Crypto 919 - Easy RSA 2 - [Writeup](https://github.com/pcw109550/write-up/tree/master/2019/ISITDTU/Easy_RSA_2)
		- Crack multiprime RSA with Fermat factorization.
	- Crypto 238 - Old Story - [Writeup](https://github.com/pcw109550/write-up/tree/master/2019/ISITDTU/Old_story)
		- Base64 encoding with guessing.
	- Crypto 395 - decrypt to me - [Writeup](https://github.com/pcw109550/write-up/tree/master/2019/ISITDTU/decrypt_to_me)
		- Weak prng.
- **Facebook CTF 2019**
	- Crypto 974 - netscream - [Writeup](https://github.com/pcw109550/write-up/tree/master/2019/Facebook/netscream)
		- Dual_EC_DRBG with some reversing.
	- Crypto 919 - storagespace - [Writeup](https://github.com/pcw109550/write-up/tree/master/2019/Facebook/storagespace)
		- Order of curve is small, use sage's `discrete_log()` function.
- **DEF CON CTF Qualifier 2019**
	- Crypto 182 - tania - [Writeup](https://github.com/pcw109550/write-up/tree/master/2019/DEFCON/tania)
		- DSA with LCG nonces are broken using LLL, or apply biased nonce attack.
- **Harekaze CTF 2019**
	- Crypto 200 - Now We Can Play!! - [Writeup](https://github.com/pcw109550/write-up/tree/master/2019/Harekaze/Now_We_Can_Play)
		- Simple bruteforcing problem.
	- Crypto 100 - ONCE UPON A  TIME - [Writeup](https://github.com/pcw109550/write-up/tree/master/2019/Harekaze/ONCE_UPON_A_TIME)
		- Hill cipher with randomness and padding.
	- Crypto 200 - Show me your private key - [Writeup](https://github.com/pcw109550/write-up/tree/master/2019/Harekaze/show_me_your_private_key)
		- Order of elliptic curve defined over `Zmod(n)`, where `n` is composite.
