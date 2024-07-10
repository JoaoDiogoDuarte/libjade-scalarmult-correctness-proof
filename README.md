# Libjade scalarmult correctness proof

Below are files that run without errors as of latest commit date and time and do not include any `admit.` or `smt.`.


### Common
- [X] EClib.ec
- [X] W64limbs.ec
- [X] Zplimbs.ec
- [X] Zp_25519.ec
- [X] Curve25519_Spec.ec
- [X] Curve25519_Operations.ec
- [X] Curve25519_Procedures.ec
- [X] Curve25519_PHoare.ec

### Ref4
- [X] CorrectnessProof.ec
- [X] Curve25519_auto4.ec

### Mulx
- [ ] CorrectnessProof.ec
    - it_sqr not done.
- [X] Curve25519_auto_mulx.ec

Everything that is to be proven in Cryptoline are in the Curve25519_auto* files, Due to this, all lemmas are admitted for now.

The original Easycrypt files can be found [in the x25519 branch in libjc](https://github.com/tfaoliveira/libjc/tree/x25519/proof/crypto_scalarmult/curve25519).
