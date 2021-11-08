# Atal Bihari Vajpayee Indian Institute of Information Technology and Management, Gwalior

## Grp15-DecentralizedElectionSys

<br>

SE Project: Blockchain based E-Voting System with OTP based authentication of Voters

> Submitted to: Dr Santosh Singh Rathore

---

> Submitted by: GROUP - 15 (2019 IMT)

- Abhishek Singh Chauhan - 005
- Hardik Goyal - 035
- Shikhar Shukla - 095

## How to start Smart Contract

### Way 1 => Ganache GUI + Truffle

- open ganache if you want you may create & save a workspace

```
$ truffle console --network ganache
```

### Way 2 => No GUI just Truffle

```
$ truffle develop
```

### Rest Procedure is common

- If you need backend

```
$ yarn backend
```

- If you need frontend

```
$ yarn frontend
```

- If you need both

```
$ yarn dev
```

- If you have changed the contract then just type to update artifacts

```
deploy --reset
```
