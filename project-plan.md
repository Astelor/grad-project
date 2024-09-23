# PLAN
> Side-channel Attack Resistant RSA Hardware Accelerator

phases:
1. Make a working RSA hardware accelerator
2. Make the process secure
3. Make it into a Hardware Security Module

# Phase 1: RSA Hardware accelerator

## Possible Problem

- Serialization WILL be a problem
	- keys and ciphertexts have large bits
	- you have to serialize text input
- Scalability
	- the key or ciphertext WILL be more than 64 bits
	- how to do exponential operation on multiple bits
	- > and make it efficient

## Encryption

- Assume a set of valid keys
- Assume a set of plaintext
- Realize encryption the process with HDL

Not critical:
> but will make your life easier from then on
- Make a module that generates keys

## Decryption

- Assume a set of valid keys
- Assume a set of ciphertext
- Realize the decrytion process with HDL

# Phase 2: Side-channel Attack

## Possible Problem

- How realistic or accurate to simulate attacks on FPGA?
	- power consumption attacks
	- timing analysis attack
	- > could theorize the attack

## Input validation
- desanitize the input as another module

## Timing analysis

## Power consumption analysis


# Phase 3: Hardware Security Module

- Not a must, considering the time limitation
