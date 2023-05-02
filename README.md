# Awesome SGX Open Source Projects

*Hope that you'd be glad to add a star if you think this list is helpful!*

A curated list of academic work from top conferences: [link](https://github.com/Maxul/Awesome-SGX-Open-Source/blob/master/Academy.md)

- [Runtime Framework](#runtime-framework)
  - [Industrial Leading Projects](#industrial-leading-projects)
  - [Library OSes and SDKs](#library-oses-and-sdks)
- [Remote Attestation (RA) and Secure Channels](#remote-attestation-ra-and-secure-channels)
- [Crypto](#crypto)
- [Language Frameworks](#language-frameworks)
- [Blockchains](#blockchains)
- [Machine Learning](#machine-learning)
- [Common Libraries](#common-libraries)
- [Applications](#applications)
- [Network](#network)
- [Data Analytics](#data-analytics)
- [Private Search](#private-search)
- [Key and Password Management](#key-and-password-management)
- [Encrypted Databases and Key-value Stores](#encrypted-databases-and-key-value-stores)
- [Distributed Systems](#distributed-systems)
- [Profiling](#profiling)
- [Performance](#performance)
- [Compatibility](#compatibility)
- [Defenses](#defenses)
  - [Memory Protection](#memory-protection)
  - [I/O Protection](#io-protection)
- [Attacks](#attacks)
- [Beyond SGX Enclave Projects](#beyond-sgx-enclave-projects)
- [Other TEEs](#other-tees)

## Runtime Framework

### Industrial Leading Projects

- **Microsoft Confidential Consortium Framework** [https://github.com/microsoft/CCF](https://github.com/microsoft/CCF)
- **Ant Financial Occlum** [https://github.com/occlum/occlum](https://github.com/occlum/occlum)
- **Next-Generation Occlum, optimized for Intel SGX 2.0** [https://github.com/occlum/ngo](https://github.com/occlum/ngo)
- **Inclavare: a confidential container for cloud-native confidential computing and enclave runtime ecosystem** [https://github.com/inclavare-containers/inclavare-containers](https://github.com/inclavare-containers/inclavare-containers)
- **Enarx: Confidential Computing with WebAssembly** [https://github.com/enarx/enarx](https://github.com/enarx/enarx)
- **enclaive.io: Building confidential containers for the cloud** [https://github.com/enclaive](https://github.com/enclaive)
- **Conclave SDK is an open source platform that makes working with SGX enclaves easy** [https://github.com/R3Conclave/conclave-core-sdk](https://github.com/R3Conclave/conclave-core-sdk)
- **Confidential Containers: Process-based Confidential Container Runtime** [https://github.com/confidential-containers/enclave-cc](https://github.com/confidential-containers/enclave-cc)
- **KubeTEE TFF** [https://github.com/SOFAEnclave/trusted-function-framework](https://github.com/SOFAEnclave/trusted-function-framework)
- **Fortanix Enclave Development Platform** [https://github.com/fortanix/rust-sgx](https://github.com/fortanix/rust-sgx)
- **Scontain: Confidential Computing Playground Virtual Machine** [https://github.com/scontain](https://github.com/scontain)
- **Veracruz: privacy-preserving collaborative compute, now an adopted project of the Confidential Compute Consortium (CCC)** [https://github.com/veracruz-project/veracruz](https://github.com/veracruz-project/veracruz)
- **MarbleRun: a framework for creating distributed confidential-computing apps** [https://github.com/edgelesssys/marblerun](https://github.com/edgelesssys/marblerun)
- **Apache Teaclave** [https://github.com/apache/incubator-teaclave](https://github.com/apache/incubator-teaclave)
- **Google Asylo** [https://github.com/google/asylo](https://github.com/google/asylo)

### Library OSes and SDKs

- **Gramine Library OS with Intel SGX Support (formerly Graphene)** [https://github.com/gramineproject/gramine](https://github.com/gramineproject/gramine)
- **Edgeless RT: SDK for TEEs/SGX based on Open Enclave with Go support** [https://github.com/edgelesssys/edgelessrt](https://github.com/edgelesssys/edgelessrt)
- **Porpoise: A tool to port commodity application to Intel SGX** [https://github.com/iisc-cssl/porpoise](https://github.com/iisc-cssl/porpoise)
- **Mystikos: Tools and runtime for launching unmodified container images in Trusted Execution Environments** [https://github.com/deislabs/mystikos](https://github.com/deislabs/mystikos)
- **SGX-LKL: Library OS for running Linux applications inside SGX enclaves** [https://github.com/lsds/sgx-lkl](https://github.com/lsds/sgx-lkl)
- **Ratel: Dynamic Binary Translation with SGX Enclaves** [https://github.com/ratel-enclave/ratel](https://github.com/ratel-enclave/ratel)
- **Panoply: Low-TCB Linux Applications with SGX Enclaves** [https://github.com/shwetasshinde24/Panoply](https://github.com/shwetasshinde24/Panoply)

## Remote Attestation (RA) and Secure Channels

- **Veraison: Project Veraison creates software components that can be used to build an Attestation Verification Service** [https://github.com/veraison](https://github.com/veraison)
- **OpenEmbedded layer for the use cases on secure boot, integrity and encryption** [https://github.com/jiazhang0/meta-secure-core](https://github.com/jiazhang0/meta-secure-core)
- **MAGE: Mutual Attestation for a Group of Enclaves without Trusted Third Parties (USENIX Security 2022)** [https://github.com/donnod/linux-sgx-mage](https://github.com/donnod/linux-sgx-mage)
- **Microsoft Azure Attestation service (MAA) for Attesting Trusted Execution Environments (TEEs)** [https://github.com/Azure-Samples/microsoft-azure-attestation](https://github.com/Azure-Samples/microsoft-azure-attestation)
- **Linux SGX remote attestation example including the communication with IAS** [https://github.com/svartkanin/linux-sgx-remoteattestation](https://github.com/svartkanin/linux-sgx-remoteattestation)
- **OpenID Connect Via Enclave** [https://github.com/DanielShteinbok/spring-oidc-conclave-authentication](https://github.com/DanielShteinbok/spring-oidc-conclave-authentication)
- **Intel Security Libraries for Data Center (Intel SecL-DC)** [https://github.com/intel-secl/intel-secl](https://github.com/intel-secl/intel-secl)
  - [SGX Caching Service](https://github.com/intel-secl/sgx-caching-service)
  - [SGX Quote Verification Service](https://github.com/intel-secl/sgx-verification-service)
  - [SGX Host Verification Service](https://github.com/intel-secl/sgx-hvs)
  - [SGX Hub](https://github.com/intel-secl/sgx-ah)
  - [SGX Agent](https://github.com/intel-secl/sgx_agent)
- **SGX Quote Verification Service, cloud-nativized** [https://github.com/pw4ever/isecl-sqvs](https://github.com/pw4ever/isecl-sqvs)
- **OPERA: Open Remote Attestation for Intel's Secure Enclaves** [https://github.com/Calctopia-OpenSource/opera](https://github.com/Calctopia-OpenSource/opera)
- **Intel end-to-end RA** [https://github.com/intel/sgx-ra-sample](https://github.com/intel/sgx-ra-sample)
- **Data Center Attestation Primitives (DCAP)** [https://github.com/intel/SGXDataCenterAttestationPrimitives](https://github.com/intel/SGXDataCenterAttestationPrimitives)
- **RA-based TLS** [https://github.com/cloud-security-research/sgx-ra-tls](https://github.com/cloud-security-research/sgx-ra-tls)
- **IBM simplified RA without accessing IAS too frequently** [https://github.com/IBM/sgx-trust-management](https://github.com/IBM/sgx-trust-management)
- **Azure Attestation SGX Certification Cache** [https://github.com/Microsoft/Azure-DCAP-Client](https://github.com/Microsoft/Azure-DCAP-Client)
- **Enclave Mutual Attestation Library** [https://github.com/AntonioDan/SGX_Enclave_Mutual_Attestation_Library](https://github.com/AntonioDan/SGX_Enclave_Mutual_Attestation_Library)

## Crypto

- **SGX-supported version of safeheron-crypto-suites-cpp library** [https://github.com/Safeheron/safeheron-crypto-suites-cpp-sgx](https://github.com/Safeheron/safeheron-crypto-suites-cpp-sgx)
- **Enclavised OpenSSL (Intel Official)** [https://github.com/intel/intel-sgx-ssl](https://github.com/intel/intel-sgx-ssl)
- **Enclavised LibreSSL** [https://github.com/lsds/TaLoS](https://github.com/lsds/TaLoS)
- **Enclavised mbedTLS** [https://github.com/bl4ck5un/mbedtls-SGX](https://github.com/bl4ck5un/mbedtls-SGX)
- **Enclavised WolfSSL** [https://github.com/wolfSSL/wolfssl-examples](https://github.com/wolfSSL/wolfssl-examples)
- **SGX-OpenSSL (SGX-Tor Project)** [https://github.com/sparkly9399/SGX-OpenSSL](https://github.com/sparkly9399/SGX-OpenSSL)

## Language Frameworks

- **Java** [https://github.com/apache/incubator-teaclave-java-tee-sdk](https://github.com/apache/incubator-teaclave-java-tee-sdk)
- **Rust**
  - **RusTEE: Developing Memory-Safe ARM TrustZone Applications (ACSAC 2020)** [https://github.com/apache/incubator-teaclave-trustzone-sdk](https://github.com/apache/incubator-teaclave-trustzone-sdk)
  - **EigenCC: Confidential Computation** [https://github.com/0xEigenLabs/eigencc](https://github.com/0xEigenLabs/eigencc)
  - [https://github.com/baidu/rust-sgx-sdk](https://github.com/baidu/rust-sgx-sdk)
  - [https://github.com/fortanix/rust-sgx](https://github.com/fortanix/rust-sgx)
- **WebAssembly**
  - **Wasm interpreter in Rust** [https://github.com/mesalock-linux/wasmi-sgx](https://github.com/mesalock-linux/wasmi-sgx)
  - **Twine: An Embedded Trusted Runtime for WebAssembly** [https://github.com/jamesmenetrey/unine-twine](https://github.com/jamesmenetrey/unine-twine)
  - **WebAssembly Micro Runtime (WAMR)** [https://github.com/bytecodealliance/wasm-micro-runtime](https://github.com/bytecodealliance/wasm-micro-runtime)
- **Python**
  - **MesaPy: A Memory-Safe Python Implementation based on PyPy** [https://github.com/mesalock-linux/mesapy](https://github.com/mesalock-linux/mesapy)
  - **Python binder for SGX SDK** [https://github.com/adombeck/python-sgx](https://github.com/adombeck/python-sgx)
- **Golang**
  - **EGo: a framework for building confidential apps in Go** [https://github.com/edgelesssys/ego](https://github.com/edgelesssys/ego)
  - **Golang** [https://github.com/intel/GrapheneSGX-Golang-Support-and-Enhancement](https://github.com/intel/GrapheneSGX-Golang-Support-and-Enhancement)
  - **Golang binder** [https://github.com/rupc/go-with-intel-sgx](https://github.com/rupc/go-with-intel-sgx) 
  - **GOTEE: Secured Routines using SGX** [https://github.com/epfl-dcsl/gotee](https://github.com/epfl-dcsl/gotee)
- **JavaScript** [https://github.com/evervault/node-secureworker](https://github.com/evervault/node-secureworker)
- **C#** [https://github.com/Liaojinghui/A_C-Sharp_Project_With_SGX](https://github.com/Liaojinghui/A_C-Sharp_Project_With_SGX)
- **Lua** [https://github.com/vschiavoni/SecureStreams-DEBS17](https://github.com/vschiavoni/SecureStreams-DEBS17)
- **Erlang** [https://github.com/Erlang-Enclave-Thesis/sgx-erlang-extension](https://github.com/Erlang-Enclave-Thesis/sgx-erlang-extension)
- **C/C++ (Intel Official)** [https://github.com/intel/linux-sgx](https://github.com/intel/linux-sgx)
- **PSec: Programming Language for Creating Secure Distributed Systems leveraging Intel SGX** [https://github.com/ShivKushwah/PSec](https://github.com/ShivKushwah/PSec)

## Blockchains

- **Secret.NET is a .NET Client to interact with the Secret Network blockchain** [https://github.com/0xxCodemonkey/SecretNET](https://github.com/0xxCodemonkey/SecretNET)
- **A Ledger-backed Secure Key-Value store (LSKV), built on the Confidential Consortium Framework (CCF)** [https://github.com/microsoft/LSKV](https://github.com/microsoft/LSKV)
- **Twilight: A Differentially Private Payment Channel Network (USENIX Security 2022)** [https://github.com/saart/Twilight](https://github.com/saart/Twilight)
- **Ethernity Cloud Node** [https://github.com/ethernity-cloud/mvp-pox-node](https://github.com/ethernity-cloud/mvp-pox-node)
- **Oasis Network: Performant and Confidentiality-Preserving Smart Contracts + Blockchains** [https://github.com/oasisprotocol/oasis-core](https://github.com/oasisprotocol/oasis-core)
- **MobileCoin: Private payments for mobile devices** [https://github.com/mobilecoinfoundation/mobilecoin](https://github.com/mobilecoinfoundation/mobilecoin)
- **Integritee off-chain worker and sidechain validateer** [https://github.com/integritee-network/worker](https://github.com/integritee-network/worker)
- **Ternoa's Blockchain to support the secure creation and transfer of Capsules** [https://github.com/capsule-corp-ternoa/chain](https://github.com/capsule-corp-ternoa/chain)
- **Automata Network: Web 3.0 Realized with Tracless Privacy and Seamless Compatibility** [https://github.com/automata-network/automata](https://github.com/automata-network/automata)
- **Phala Blockchain: a blockchain-based confidential computing cloud** [https://github.com/Phala-Network/phala-blockchain](https://github.com/Phala-Network/phala-blockchain)
- **sWorker: Crust MPoW-based Offchain Storage inside TEE Enclaves** [https://github.com/crustio/crust-sworker](https://github.com/crustio/crust-sworker)
- **Teechain: A Secure Payment Network with Asynchronous Blockchain Access (SOSP 2019)** [https://github.com/lsds/Teechain](https://github.com/lsds/Teechain)
- **Ekiden: Confidentiality-Preserving Smart Contract Platform (EuroS&P 2019)** [https://github.com/ekiden/ekiden](https://github.com/ekiden/ekiden)
- **Hardware Secure Crypto Wallet for Ethereum and SKALE** [https://github.com/skalenetwork/sgxwallet](https://github.com/skalenetwork/sgxwallet)
- **Database intended for Blockchain** [https://github.com/kaimast/credb](https://github.com/kaimast/credb)
- **Anonify: A blockchain-Agnostic Execution Environment with Privacy and Auditability** [https://github.com/LayerXcom/anonify](https://github.com/LayerXcom/anonify)
- **Hyperledger: Confidentiality-Preserving, Off-Chain Smart Contracts**
  - [https://github.com/hyperledger-labs/private-data-objects](https://github.com/hyperledger-labs/private-data-objects)
  - [https://github.com/hyperledger/fabric-private-chaincode](https://github.com/hyperledger/fabric-private-chaincode)
- **substraTEE: Trusted Off-Chain Compute Framework for Substrate Blockchains** [https://github.com/scs/substraTEE](https://github.com/scs/substraTEE)
- **eEVM: Enclave EVM as Ethereum Virtual Machine** [https://github.com/Microsoft/eEVM](https://github.com/Microsoft/eEVM)
- **BitCoin Mixer** [https://github.com/BitObscuro/Obscuro](https://github.com/BitObscuro/Obscuro)
- **Proof of Luck for IPFS** [https://github.com/luckychain/lucky](https://github.com/luckychain/lucky)
- **Town Crier: An Authenticated Data Feed For Smart Contracts** [https://github.com/bl4ck5un/Town-Crier](https://github.com/bl4ck5un/Town-Crier)
- **Ledger BOLOS Enclave** [https://github.com/LedgerHQ/bolos-enclave](https://github.com/LedgerHQ/bolos-enclave)

## Machine Learning

- **Machine learning inference in trusted execution environment build from SGX** [https://github.com/Luke20000429/Trusted-ML-SGX](https://github.com/Luke20000429/Trusted-ML-SGX)
- **Azure Bicep/ARM template to quickly deploy standalone secure research environments** [https://github.com/microsoft/Azure-Secure-Enclave-for-Research](https://github.com/microsoft/Azure-Secure-Enclave-for-Research)
- **SOTER: Guarding Black-box Inference for General Neural Networks at the Edge (ATC 2022)** [https://github.com/hku-systems/SOTER](https://github.com/hku-systems/SOTER)
- **TF-Encrypted: A Framework for Encrypted Machine Learning in TensorFlow** [https://github.com/tf-encrypted/tf-encrypted](https://github.com/tf-encrypted/tf-encrypted)
- **BigDL Privacy Preserving Machine Learning** [https://github.com/intel-analytics/BigDL](https://github.com/intel-analytics/BigDL)
- **BlindAI: Fast, accessible and privacy friendly AI deployment** [https://github.com/mithril-security/blindai](https://github.com/mithril-security/blindai)
- **Confidential Computing Zoo provides confidential computing solutions based on Intel SGX, TDX, HEXL, etc. technologies** [https://github.com/intel/confidential-computing-zoo](https://github.com/intel/confidential-computing-zoo)
- **MNIST hand-written text recognition task using FEDn with the PyTorch C++** [https://github.com/scaleoutsystems/tee-mnist](https://github.com/scaleoutsystems/tee-mnist)
- **Pytorch with SGX solution** [https://github.com/intel/sgx-pytorch](https://github.com/intel/sgx-pytorch)
- **Enclave Hardening for Private ML (GBDT Learning + Differential Privacy)** [https://github.com/loretanr/dp-gbdt](https://github.com/loretanr/dp-gbdt)
- **Tensorflow Lite For Intel SGX** [https://github.com/Jumpst3r/tensorflow-lite-sgx](https://github.com/Jumpst3r/tensorflow-lite-sgx)
- **An trusted and lite version of OpenCV based on Intel SGX** [https://github.com/xymeng16/opencv_lite_sgx](https://github.com/xymeng16/opencv_lite_sgx)
- **Open Enclave port of the ONNX runtime for confidential inferencing on Azure Confidential Computing** [https://github.com/microsoft/onnxruntime-openenclave](https://github.com/microsoft/onnxruntime-openenclave)
- **Secure Aggregation for Federated Learning** [https://github.com/mc2-project/secure-aggregation](https://github.com/mc2-project/secure-aggregation)
- **Secure Collaborative Training and Inference for XGBoost** [https://github.com/mc2-project/secure-xgboost](https://github.com/mc2-project/secure-xgboost)
- **Confidential Computing of Machine Learning using Intel SGX** [https://github.com/prasadkjose/confidential-ml-sgx](https://github.com/prasadkjose/confidential-ml-sgx)
- **MesaTEE GBDT-RS: A Fast and Secure GBDT library** [https://github.com/mesalock-linux/gbdt-rs](https://github.com/mesalock-linux/gbdt-rs)
- **TF-Trusted: Run TensorFlow Models in Secure Enclaves** [https://github.com/capeprivacy/tf-trusted](https://github.com/capeprivacy/tf-trusted)
- **Accountable Deep Learning** [https://github.com/arefasvadi/SGX-ADL](https://github.com/arefasvadi/SGX-ADL)
- **Open Deep Learning Compiler Stack** [TVM in Intel SGX Example](https://github.com/dmlc/tvm/tree/master/apps/sgx)
- **Slalom: Fast, Verifiable and Private Execution of Neural Networks in Trusted Hardware (ICLR 2019)** [https://github.com/ftramer/slalom](https://github.com/ftramer/slalom)
- **EnclaveML: a framework for tokenized federated learning** [https://github.com/jamslevy/enclaveML](https://github.com/jamslevy/enclaveML)
- **Plinius: Secure ML model training with Intel SGX and PM for fault tolerance** [https://github.com/anonymous-xh/plinius](https://github.com/anonymous-xh/plinius)
- **SGX-Darknet: SGX compatible ML library** [https://github.com/anonymous-xh/sgx-dnet](https://github.com/anonymous-xh/sgx-dnet)

## Common Libraries

- **A library to orchestrate interoperable Data Cleaning Services using Intel SGX based Containers** [https://github.com/qascade/dcr](https://github.com/qascade/dcr)
- **DarkProto Threshold Cryptosystem** [https://github.com/andrcmdr/darkproto-proposal](https://github.com/andrcmdr/darkproto-proposal)
- **Enclave Memory Manager** [https://github.com/intel/sgx-emm](https://github.com/intel/sgx-emm)
- **VRF-enhanced random number source running inside enclaves** [https://github.com/smartbch/enclave-vrf](https://github.com/smartbch/enclave-vrf)
- **A trusted libjpeg on Intel SGX** [https://github.com/xymeng16/libtjpeg](https://github.com/xymeng16/libtjpeg)
- **Zlib Data Compression Library inside SGX Enclaves** [https://github.com/ffosilva/zlib-sgx](https://github.com/ffosilva/zlib-sgx)
- **SEAL library in SGX** [https://github.com/shenqtao/seal_SGX](https://github.com/shenqtao/seal_SGX)
- **Enclaved-FE: enable applications using Fentec Functional Encryption libraries ([CiFEr](https://github.com/fentec-project/CiFEr), [GoFE](https://github.com/fentec-project/gofe)) in Intel SGX** [https://github.com/cryptohackathon/enclaved-FE](https://github.com/cryptohackathon/enclaved-FE)
- **Libsodium AES-NI based AES-256-GCM** [https://github.com/Maxul/SGX-AES-256](https://github.com/Maxul/SGX-AES-256)
- **GNU Multiple Precision Arithmetic Trusted Library for Intel SGX** [https://github.com/intel/sgx-gmp](https://github.com/intel/sgx-gmp)

## Applications

- **CACIC: Providing Secure and Customizable IoT Data Access Policies with SGX** [https://github.com/GTA-UFRJ/CACIC-Use-Case](https://github.com/GTA-UFRJ/CACIC-Use-Case)
- **BastionLab: a simple framework for privacy-friendly data science collaboration** [https://github.com/mithril-security/bastionlab](https://github.com/mithril-security/bastionlab)
- **180Protocol: Confidential compute for sensitive data sharing and commercial collaboration** [https://github.com/180Protocol/180protocol](https://github.com/180Protocol/180protocol)
- **Secure and Lightweight Deduplicated Storage via Shielded Deduplication-Before-Encryption (ATC 2022)** [https://github.com/yzr95924/DEBE](https://github.com/yzr95924/DEBE)
- **Intel SGX Module for the passpharse key derivation module of GenesisDrive** [https://github.com/VRTeamgenesis/GenesisDrive-SGX](https://github.com/VRTeamgenesis/GenesisDrive-SGX)
- **Verifiable Election** [https://github.com/davidgmorais/verifiable-election](https://github.com/davidgmorais/verifiable-election)
- **Rex: SGX decentralized recommender (IEEE IPDPS 2022)** [https://github.com/rafaelppires/rex](https://github.com/rafaelppires/rex)
- **Loading SGX enclave from DLL on Windows 10 64-bit** [https://github.com/nadiaivc/Load-SGX-enclave-from-DLL](https://github.com/nadiaivc/Load-SGX-enclave-from-DLL)
- **SRX – SGX Recovery Extension** [https://github.com/andrade/srx](https://github.com/andrade/srx)
- **Black-Scholes-Merton computation in Intel SGX** [https://github.com/sbellem/sgx-bsm](https://github.com/sbellem/sgx-bsm)
- **Accelerating Encrypted Deduplication via SGX (ATC 2021)** [https://github.com/jingwei87/sgxdedup](https://github.com/jingwei87/sgxdedup)
- **SGX-based Genome Variants Search** [https://github.com/ndokmai/sgx-genome-variants-search](https://github.com/ndokmai/sgx-genome-variants-search)
- **SMac: Secure Genotype Imputation in Intel SGX** [https://github.com/ndokmai/sgx-genotype-imputation](https://github.com/ndokmai/sgx-genotype-imputation)
- **SGXKaller: Private Contact Discovery Service** [https://github.com/Arslan8/SGXKaller](https://github.com/Arslan8/SGXKaller)
- **Achieving Reconciliation between Privacy Preservation and Auditability For File Hosting (Intel SGX + IPFS + Hyperledger Fabric)** [https://github.com/wuliangshun/SGX-base-File-Hosting](https://github.com/wuliangshun/SGX-base-File-Hosting)
- **bwa-sgx-scone: a parallel privacy preserved** [BWA](https://github.com/lh3/bwa)(DNA sequence alignment) solution using Intel SGX and SCONE** [https://github.com/dsc-sgx/bwa-sgx-scone](https://github.com/dsc-sgx/bwa-sgx-scone)
- **Bioinformatic Interpreter with Intel SGX** [https://github.com/hello31337/BI-SGX](https://github.com/hello31337/BI-SGX)
- **C3PO: providing security functions for Open Mobile Evolved Core (OMEC)** [https://github.com/omec-project/c3po](https://github.com/omec-project/c3po)
- **SafeTrace: Privacy Preserving Voluntary COVID-19 Self-Reporting Platform for Contact Tracing** [https://github.com/enigmampc/SafeTrace](https://github.com/enigmampc/SafeTrace)
- **Private Contact Discovery Service for Signal** [https://github.com/signalapp/ContactDiscoveryService](https://github.com/signalapp/ContactDiscoveryService)
- **Trustworthy and Accountable Function-as-a-Service** [https://github.com/SSGAalto/sfaas](https://github.com/SSGAalto/sfaas)
- **Securing Storage Encryption** [https://github.com/ayeks/TresorSGX](https://github.com/ayeks/TresorSGX)

## Network

- **Setheum - Powering Scalable Web3 Solutions** [https://github.com/Setheum-Labs/Setheum](https://github.com/Setheum-Labs/Setheum)
- **Towards A TEE-based V2V Protocol For Connected And Autonomous Vehicles** [https://github.com/OSUSecLab/v2v-sgx-prelim](https://github.com/OSUSecLab/v2v-sgx-prelim)
- **TrustedGateway: TEE-Assisted Routing and Firewall Enforcement Using ARM TrustZone (RAID 2022)** [https://github.com/trugw](https://github.com/trugw)
- **OpenRelay: Community-built, Privacy-first VPN (WIP)** [https://github.com/triumphantomato/openrelay](https://github.com/triumphantomato/openrelay)
- **Bento: Safely Bringing Network Function Virtualization to Tor (SIGCOMM 2021)** [https://github.com/breakerspace/bento](https://github.com/breakerspace/bento)
- **Nginx-SGX: SGX-ready Nginx open source server** [https://github.com/enclaive/enclaive-docker-nginx-sgx](https://github.com/enclaive/enclaive-docker-nginx-sgx)
- **Hidden anonymization with SGX-based mix-networks** [https://github.com/oEscal/sgx-based-mix-networks](https://github.com/oEscal/sgx-based-mix-networks)
- **ZeroCache: a Cloud-Oriented Middlebox for Network Confidential Computing** [https://github.com/Maxul/zerocache](https://github.com/Maxul/zerocache)
- **Hidden anonymization with SGX-based mixes** [https://github.com/oEscal/sgx-based-mix-networks](https://github.com/oEscal/sgx-based-mix-networks)
- **SnowHaze VPN Zero-Knowledge Verification** [https://github.com/snowhaze/zka-sgx](https://github.com/snowhaze/zka-sgx)
- **MACSec: Secure Network Interface with SGX** [https://github.com/fkirc/secure-network-interface-with-sgx](https://github.com/fkirc/secure-network-interface-with-sgx)
- **SENG: SGX-Enforced Network Gateway (USENIX Security 2020)** [https://github.com/sengsgx/sengsgx](https://github.com/sengsgx/sengsgx)
- **SGX + CDN (USENIX Security 2020)** [https://github.com/smherwig/phoenix](https://github.com/smherwig/phoenix)
- **ConsenSGX: Scaling Anonymous Communications Networks with Trusted Execution Environments (PETS 2019)** [https://github.com/sshsshy/ConsenSGX](https://github.com/sshsshy/ConsenSGX)
- **SGX + Snort Intrusion Detection System** [https://github.com/cloud-security-research/sgx-ids](https://github.com/cloud-security-research/sgx-ids)
- **SafeBricks: Shielding Network Functions in the Cloud (NSDI 2018)** [https://github.com/YangZhou1997/SafeBricks](https://github.com/YangZhou1997/SafeBricks)
- **SGX + Tor (NSDI 2017)** [https://github.com/kaist-ina/SGX-Tor](https://github.com/kaist-ina/SGX-Tor)
- **SGX + Web Crawler** [https://github.com/ShengHow95/simple-selenium-sgx-crawler](https://github.com/ShengHow95/simple-selenium-sgx-crawler)

## Data Analytics

- **SecretFlow: A unified framework for privacy-preserving data analysis and machine learning** [https://github.com/secretflow/secretflow](https://github.com/secretflow/secretflow)
- **MC2: A Platform for Secure Analytics and Machine Learning** [https://github.com/mc2-project/mc2](https://github.com/mc2-project/mc2)
- **Opaque: An encrypted data analytics platform (NSDI 2017)** [https://github.com/mc2-project/opaque-sql](https://github.com/mc2-project/opaque-sql)
- **Ryoan: A distributed sandbox for untrusted computation on secret data (OSDI 2016)** [https://github.com/ut-osa/ryoan](https://github.com/ut-osa/ryoan)
- **Confidential Analytics on Azure SGX VM's with Apache Spark and SCONE** [https://github.com/mdrakiburrahman/sgx-pyspark-sql-demo](https://github.com/mdrakiburrahman/sgx-pyspark-sql-demo)
- **BiORAM-SGX: A Practical Privacy-Preserving Data Analysis for Personal Genome by Intel SGX** [https://github.com/cBioLab/BiORAM-SGX](https://github.com/cBioLab/BiORAM-SGX)

## Private Search

- **Snoopy: Surpassing the Scalability Bottleneck of Oblivious Storage (SOSP 2021)** [https://github.com/ucbrise/snoopy](https://github.com/ucbrise/snoopy)
- **DeSearch: a decentralized search engine with verifiable dataflow (OSDI 2021)** [https://github.com/SJTU-IPADS/DeSearch](https://github.com/SJTU-IPADS/DeSearch)
- **mc-oblivious: Oblivious RAM inside of Intel SGX enclaves** [https://github.com/mobilecoinofficial/mc-oblivious](https://github.com/mobilecoinofficial/mc-oblivious)
- **ZeroTrace: Oblivious Memory Primitives from Intel SGX (NDSS 2018)** [https://github.com/sshsshy/ZeroTrace](https://github.com/sshsshy/ZeroTrace)
- **X-Search: Revisiting Private Web Search using Intel SGX (Middleware 2017)** [https://github.com/Sand-jrd/SGX-Search](https://github.com/Sand-jrd/SGX-Search)
- **Private Information Retrieval** [https://github.com/patrickwang96/BO-PIR-SGX](https://github.com/patrickwang96/BO-PIR-SGX)
- **Private SSE Schemes** [https://github.com/MonashCybersecurityLab/SGXSSE](https://github.com/MonashCybersecurityLab/SGXSSE)
- **POSUP: Oblivious Search and Update Platform with SGX** [https://github.com/thanghoang/POSUP](https://github.com/thanghoang/POSUP)
- **A Secure, Efficient and Scalable Query Framework for Outsourcing Data** [https://github.com/fishermano/QShield](https://github.com/fishermano/QShield)
- **BISEN: Boolean Isolated Searchable Encryption** [https://github.com/bernymac/BISEN](https://github.com/bernymac/BISEN)

## Key and Password Management

- **Safeheron’s TEE Based RSA Key Sharding Service** [https://github.com/Safeheron/sgx-arweave-cpp](https://github.com/Safeheron/sgx-arweave-cpp)
- **FeIDo: Recoverable FIDO2 Tokens Using Electronic IDs (CCS 2022)** [https://github.com/feido-token](https://github.com/feido-token)
- **Let's eSign Enclave** [https://github.com/letsesign/letsesign-enclave](https://github.com/letsesign/letsesign-enclave)
- **Conclave Pass: Password Manager implemented using Conclave Cloud** [https://github.com/R3Conclave/ccl-sample-conclavepass](https://github.com/R3Conclave/ccl-sample-conclavepass)
- **eHSM (SGX Enclave Based Hardware Security Module)** [https://github.com/intel/ehsm](https://github.com/intel/ehsm)
- **Trusted Certificate Service for Kubernetes Platform** [https://github.com/intel/trusted-certificate-issuer](https://github.com/intel/trusted-certificate-issuer)
- **lockbox: Key Share Management in SGX Secure Enclaves** [https://github.com/commerceblock/lockbox](https://github.com/commerceblock/lockbox)
- **Password manager supporting the login where the credentials are stored securely in an enclave** [https://github.com/enclaive/sgx-login](https://github.com/enclaive/sgx-login)
- **Key-Manager for Faasm (a high-performance stateful serverless runtime)** [https://github.com/faasm/keymanager](https://github.com/faasm/keymanager)
- **SGX Enabled OpenStack Barbican Key Management System** [https://github.com/cloud-security-research/sgx-kms](https://github.com/cloud-security-research/sgx-kms)
- **A server with SGX enclave that stores private keys and performs crypto operations upon requests** [https://github.com/cloud-key-store/keystore](https://github.com/cloud-key-store/keystore)
- **Protecting Web Passwords using Trusted Execution Environments** [https://github.com/SafeKeeper](https://github.com/SafeKeeper)
- **Channel ID Private Key Protection** [https://github.com/google/channel-id-enclave](https://github.com/google/channel-id-enclave)

## Encrypted Databases and Key-value Stores

- **memcached-sgx** [https://github.com/Yuhala/memcached-sgx](https://github.com/Yuhala/memcached-sgx)
- **EdgelessDB: a MySQL-compatible database running entirely inside SGX enclaves** [https://github.com/edgelesssys/edgelessdb](https://github.com/edgelesssys/edgelessdb)
- **Avocado: a secure distributed in-memory key-value store (USENIX ATC 2021)** [https://github.com/mbailleu/avocado](https://github.com/mbailleu/avocado)
- **SPEICHER: Securing LSM-based Key-Value Stores using Shielded Execution (FAST 2019)**[https://github.com/mbailleu/SpeicherDPDK](https://github.com/mbailleu/SpeicherDPDK)
- **StealthDB: an encrypted database from intel sgx with small trusted computing base (PETS 2019)** [https://github.com/cryptograph/stealthdb](https://github.com/cryptograph/stealthdb)
- **SQLite database inside a secure Intel SGX enclave (Linux)** [https://github.com/yerzhan7/SGX_SQLite](https://github.com/yerzhan7/SGX_SQLite)
- **STANlite: an in-memory database engine for SGX-enabled secure data processing** [https://github.com/ibr-ds/STANlite](https://github.com/ibr-ds/STANlite)
- **Trusted in-memory key-value stores (EuroSys 2019)** [https://github.com/cocoppang/ShieldStore](https://github.com/cocoppang/ShieldStore)
- **Protect Audit-Log via Sqlite (EuroSys 2018)** [https://github.com/lsds/LibSEAL](https://github.com/lsds/LibSEAL)

## Distributed Systems

- **Intel Technology Enabling for OpenShift** [https://github.com/intel/intel-technology-enabling-for-openshift](https://github.com/intel/intel-technology-enabling-for-openshift)
- **Dissecting BFT Consensus: In Trusted Components we Trust (EuroSys 2023)** [https://github.com/msadoghi/resdb-sgx-eurosys](https://github.com/msadoghi/resdb-sgx-eurosys)
- **uBFT: Microsecond-scale BFT using Disaggregated Memory (ASPLOS 2023)** [https://github.com/LPD-EPFL/ubft](https://github.com/LPD-EPFL/ubft)
- **Byzantine-fault tolerant pessimistic lock manager with Intel SGX** [https://github.com/shangsuru/verifiable-lockmanager](https://github.com/shangsuru/verifiable-lockmanager)
- **Confidential Containers Operator: deploying and managing Confidential Containers Runtime on Kubernetes clusters** [https://github.com/confidential-containers/operator](https://github.com/confidential-containers/operator)
- **Oak: Meaningful Control of Data in Distributed Systems** [https://github.com/project-oak/oak](https://github.com/project-oak/oak)
- **Kubernetes Device Plugin for Intel SGX** [https://github.com/AliyunContainerService/sgx-device-plugin](https://github.com/AliyunContainerService/sgx-device-plugin)
- **Intel Software Guard Extensions (SGX) device plugin for Kubernetes** [https://github.com/intel/intel-device-plugins-for-kubernetes/tree/main/cmd/sgx_plugin](https://github.com/intel/intel-device-plugins-for-kubernetes/tree/main/cmd/sgx_plugin)
- **Robust P2P Primitives Using SGX Enclaves (RAID 2020)** [https://bitbucket.org/P2PUsingSGX/p2pusingsgx](https://bitbucket.org/P2PUsingSGX/p2pusingsgx)
- **SecDATAVIEW: A Secure Big Data Workflow Management System for Heterogeneous Computing Environments (ACSAC 2019)** [https://github.com/shiyonglu/SecDATAVIEW](https://github.com/shiyonglu/SecDATAVIEW)
- **SGX-Migration: A library and an application to provide migratable primitives for SGX enclaves (DSN 2018)** [https://github.com/SSGAalto/sgx-migration](https://github.com/SSGAalto/sgx-migration)
- **Memory Sharing Library for Intel SGX Card** [https://github.com/cloud-security-research/memsharing-sgxcard](https://github.com/cloud-security-research/memsharing-sgxcard)
- **SGX-Aware Container Orchestrator** [https://github.com/sebva/sgx-orchestrator](https://github.com/sebva/sgx-orchestrator)
- **ZooKeeper** [https://github.com/sereca/SecureKeeper](https://github.com/sereca/SecureKeeper)
- **Raft** [https://github.com/LuminousXLB/EnclaveRaft](https://github.com/LuminousXLB/EnclaveRaft)

## Profiling

- **TEEMon: A continuous performance monitoring framework for TEEs (Middleware 2020)** [https://github.com/rcrane/TEEMon](https://github.com/rcrane/TEEMon)
- **sgxtop and sgxstat utilities for monitoring SGX driver statistics** [https://github.com/fortanix/sgxtop](https://github.com/fortanix/sgxtop)
- **Report statistics of E/Ocalls, EPC Paging** [https://github.com/ibr-ds/sgx-perf](https://github.com/ibr-ds/sgx-perf)
- **Stress benchmark** [https://github.com/sebva/stress-sgx](https://github.com/sebva/stress-sgx)
- **nbench benchmark** [https://github.com/utds3lab/sgx-nbench](https://github.com/utds3lab/sgx-nbench)
- **LMbench benchmark** [https://github.com/vsecurity-research/sgx-bench](https://github.com/vsecurity-research/sgx-bench)
- **Linux SGX benchmarks (on encrypted buffer transfer)** [https://github.com/eliadt/sgx_benchmarks](https://github.com/eliadt/sgx_benchmarks)
- **Simple memory benchmarking of Intel SGX** [https://github.com/lsds/sgx-membench](https://github.com/lsds/sgx-membench)

## Performance

- **SGX Switchless Calls Made Configless (DSN 2023)**[https://gitlab.com/Yuhala/zc-switchless](https://gitlab.com/Yuhala/zc-switchless)
- **rkt-io: Library OS for running Linux applications inside of Intel SGX enclaves (EuroSys 2021)** [https://github.com/Mic92/rkt-io](https://github.com/Mic92/rkt-io)
- **Flume: a blazingly fast multi-producer, multi-consumer channel** [https://github.com/occlum/flume](https://github.com/occlum/flume)
- **Actor model for better Enclave IPC (Middleware 2018)** [https://github.com/ibr-ds/EActors](https://github.com/ibr-ds/EActors)
- **User-level paging (EuroSys 2017)** [https://github.com/acsl-technion/eleos](https://github.com/acsl-technion/eleos)
- **Switch-less (ISCA 2017)** [https://github.com/oweisse/hot-calls](https://github.com/oweisse/hot-calls)
- **SGXTuner: a distributed tuning system for enclaves** [https://github.com/dzobbe/sgxtuner](https://github.com/dzobbe/sgxtuner)

## Compatibility

- **Remote SGX enclave for embedded devices (SysTex 2022)** [https://github.com/Zildj1an/PopSGX](https://github.com/Zildj1an/PopSGX)
- **HyperEnclave: An Open and Cross-platform Trusted Execution Environment (ATC 2022)** [https://github.com/HyperEnclave](https://github.com/HyperEnclave)
- **vSGX: Virtualizing SGX Enclaves on AMD SEV (Oakland 2022)** [https://github.com/OSUSecLab/vSGX](https://github.com/OSUSecLab/vSGX)

## Defenses

- **Hacking Valgrind to use it on Rust SGX enclave** [https://github.com/mithril-security/valgrind](https://github.com/mithril-security/valgrind)
- **Enclyzer: Automated Analysis of Transient Data Leaks for Intel SGX** [https://github.com/bloaryth/enclyzer](https://github.com/bloaryth/enclyzer)
- **SgxMonitor (ACSAC 2022)** [https://github.com/tregua87/sgxmonitor-artifact](https://github.com/tregua87/sgxmonitor-artifact)
- **PRIDWEN: Universally Hardening SGX Programs via Load-Time Synthesis (ATC 2022)** [https://github.com/sslab-gatech/Pridwen](https://github.com/sslab-gatech/Pridwen)
- **Minefield: A Software-only Protection for SGX Enclaves against DVFS Attacks (USENIX Security 2022)** [https://github.com/iaik/minefield](https://github.com/iaik/minefield)
- **SGXFuzz: Efficiently Synthesizing Nested Structures for SGX Enclave Fuzzing (USENIX Security 2022)** [https://github.com/uni-due-syssec/sgxfuzz](https://github.com/uni-due-syssec/sgxfuzz)
- **Repurposing Segmentation as a Practical LVI-NULL Mitigation in SGX (USENIX Security 2022)** [https://github.com/IAIK/LVI-NULLify](https://github.com/IAIK/LVI-NULLify)
- **SGXRay: Automated Vulnerability Finding in SGX Enclave Applications** [https://github.com/baidu/sgxray](https://github.com/baidu/sgxray)
- **Collection of tools to perform memory analysis of machine SGX-enabled** [https://github.com/tregua87/sgx-forensic](https://github.com/tregua87/sgx-forensic)
- **Open Enclave specific security automation projects (CodeQL static analysis, Fuzzing and binary analysis)** [https://github.com/openenclave/openenclave-security](https://github.com/openenclave/openenclave-security)
- **Auditee: a Tool to verify the reproducibility of SGX enclave builds** [https://github.com/sbellem/auditee](https://github.com/sbellem/auditee)
- **Tamarin Models (Formal Verification) for State Continuity of Enclave Programs** [https://github.com/OSUSecLab/SGX-Enclave-Formal-Verification](https://github.com/OSUSecLab/SGX-Enclave-Formal-Verification)
- **A Java flow analysis tool for SGX data sensitivity** [https://github.com/SOF3/enclavlow](https://github.com/SOF3/enclavlow)
- **SGXL: Using 2MB large pages to mitigate page-based side-channels** [https://github.com/csl-iisc/SGXL](https://github.com/csl-iisc/SGXL)
- **Obfuscuro: A Commodity Obfuscation Engine for Intel SGX (NDSS 2019)** [https://github.com/adilahmad17/Obfuscuro](https://github.com/adilahmad17/Obfuscuro)
- **CoSMIX: A Compiler-based System for Secure Memory Instrumentation and Execution in Enclaves (ATC 2019)** [https://github.com/acsl-technion/cosmix](https://github.com/acsl-technion/cosmix)
- **Citadel: Trusted Reference Monitors for Linux using Intel SGX Enclaves** [https://github.com/HarriBellThomas/citadel](https://github.com/HarriBellThomas/citadel)
- **SGX Branch Shadowing Mitigation** [https://github.com/SSGAalto/sgx-branch-shadowing-mitigation](https://github.com/SSGAalto/sgx-branch-shadowing-mitigation)
- **Enclave Protected Code Loader** [https://github.com/intel/linux-sgx-pcl](https://github.com/intel/linux-sgx-pcl)
- **A code confidentiality framework for Intel SGX** [https://github.com/utds3lab/sgxelide](https://github.com/utds3lab/sgxelide)
- **Deflection (CAT-SGX): Practical and Efficient in-Enclave Verification of Privacy Compliance** [https://github.com/StanPlatinum/cat-sgx](https://github.com/StanPlatinum/cat-sgx)
- **Behavior-based Program Partitioning for Security Enclaves** [https://github.com/anahitH/program-partitioning-for-security-enclaves](https://github.com/anahitH/program-partitioning-for-security-enclaves)

### Memory Protection

- **Address space layout randomization (NDSS 2017)** [https://github.com/jaebaek/SGX-Shield](https://github.com/jaebaek/SGX-Shield)
- **Hardware transactional memory (NDSS 2017)** [https://github.com/sslab-gatech/t-sgx](https://github.com/sslab-gatech/t-sgx)
- **Compiler-based boundscheck (EuroSys 2017)** [https://github.com/tudinfse/sgxbounds](https://github.com/tudinfse/sgxbounds)
- **Linear/SQRT/Path ORAM** [https://github.com/maanrachid/SGXORAM](https://github.com/maanrachid/SGXORAM)
- **SO2 ORAM** [https://github.com/hiroki-chen/SGXOram](https://github.com/hiroki-chen/SGXOram)

# I/O Protection

- **Fidelius: Protecting User Secrets from Compromised Browsers (Oakland 2019)** [https://github.com/SabaEskandarian/Fidelius](https://github.com/SabaEskandarian/Fidelius)
- **Building Distributed Enclave Applications with Sancus and SGX** [https://github.com/sancus-pma/tutorial-dsn18](https://github.com/sancus-pma/tutorial-dsn18)

## Attacks

- **PMFault: Faulting and Bricking Server CPUs through Management Interfaces (CHES 2023), CVE-2022-43309** [https://github.com/zt-chen/PMFault](https://github.com/zt-chen/PMFault)
- **Rapid Prototyping for Microarchitectural Attacks (USENIX Security 2022)** [https://github.com/libtea/frameworks](https://github.com/libtea/frameworks)
- **SmashEx: Smashing SGX Enclaves Using Exceptions (CCS 2021)** [https://github.com/cimcs/poc-exploits-of-smashex](https://github.com/cimcs/poc-exploits-of-smashex)
- **Interface-Based Side Channel Attack Against Intel SGX (INFOCOM 2022)** [https://github.com/sgx-interface-side-channel/sgx-interface-side-channel](https://github.com/sgx-interface-side-channel/sgx-interface-side-channel)
- **Frontal Attack: Leaking Control-Flow in SGX via the CPU Frontend (USENIX Security 2021)** [https://github.com/dn0sar/frontal_poc](https://github.com/dn0sar/frontal_poc)
- **VoltPillager: Hardware-based fault injection attacks against IntelSGX Enclaves using the SVID voltage scaling interface (USENIX Security 2021)** [https://github.com/zt-chen/voltpillager](https://github.com/zt-chen/voltpillager)
- **TeeRex: Discovery and Exploitation of Memory Corruption Vulnerabilities in SGX Enclaves (USENIX Security 2020)** [https://github.com/uni-due-syssec/teerex-exploits](https://github.com/uni-due-syssec/teerex-exploits)
- **Faulty Point Unit: ABI Poisoning Attacks on Intel SGX (ACSAC 2020)** [https://github.com/fritzalder/faulty-point-unit](https://github.com/fritzalder/faulty-point-unit)
- **COIN Attacks: on Insecurity of Enclave Untrusted Interfaces in SGX (ASPLOS 2020)** [https://github.com/mustakcsecuet/COIN-Attacks](https://github.com/mustakcsecuet/COIN-Attacks)
- **Plundervolt: Software-based Fault Injection Attacks against Intel SGX (Oakland 2020)** [https://github.com/KitMurdock/plundervolt](https://github.com/KitMurdock/plundervolt)
- **SgxPectre Attacks: Stealing Intel Secrets from SGX Enclaves via Speculative Execution (EuroS&P 2019)** [https://github.com/OSUSecLab/SgxPectre](https://github.com/OSUSecLab/SgxPectre)
- **Spectre Attacks: Exploiting Speculative Execution (Oakland 2019)** [https://github.com/lsds/spectre-attack-sgx](https://github.com/lsds/spectre-attack-sgx)
- **RIDL: Rogue In-Flight Data Load (Oakland 2019)** [https://github.com/vusec/ridl](https://github.com/vusec/ridl)
- **ZombieLoad: Cross-Privilege-Boundary Data Sampling (CCS 2019)** [https://github.com/IAIK/ZombieLoad](https://github.com/IAIK/ZombieLoad)
- **SGX-ROP: Practical Enclave Malware with Intel SGX (DIMVA 2019)** [https://github.com/sgxrop/sgxrop](https://github.com/sgxrop/sgxrop)
- **MicroScope: enabling microarchitectural replay attacks (ISCA 2019)** [https://github.com/dskarlatos/MicroScope](https://github.com/dskarlatos/MicroScope)
- **Nemesis: Studying Microarchitectural Timing Leaks in Rudimentary CPU Interrupt Logic (CCS 2018)** [https://github.com/jovanbulck/nemesis](https://github.com/jovanbulck/nemesis)
- **Tutorial: Uncovering and mitigating side-channel leakage in Intel SGX enclaves (SPACE 2018)** [https://github.com/jovanbulck/sgx-tutorial-space18](https://github.com/jovanbulck/sgx-tutorial-space18)
- **SGX-Step: A practical attack framework for precise enclave execution control (SysTEX 2017)** [https://github.com/jovanbulck/sgx-step](https://github.com/jovanbulck/sgx-step)
- **Telling Your Secrets Without Page Faults: Stealthy Page Table-Based Attacks on Enclaved Execution (USENIX Security 2017)** [https://github.com/jovanbulck/sgx-pte](https://github.com/jovanbulck/sgx-pte)
- **SGX-Bomb: Locking Down the Processor via Rowhammer Attack (SysTEX 2017)** [https://github.com/sslab-gatech/sgx-bomb](https://github.com/sslab-gatech/sgx-bomb)
- **SGX-Timing: Cache Attacks on Intel SGX (EuroSec 2017)** [https://github.com/m1ghtym0/sgx-timing](https://github.com/m1ghtym0/sgx-timing)

## Beyond SGX Enclave Projects

- **MIG Partition Editor for NVIDIA GPUs** [https://github.com/NVIDIA/mig-parted](https://github.com/NVIDIA/mig-parted)
- **Linux SVSM (Secure VM Service Module) for AMD SEV-SNP in Rust** [https://github.com/AMDESE/linux-svsm](https://github.com/AMDESE/linux-svsm)
- **salus: RISC-V micro-hypervisor for TEE development** [https://github.com/rivosinc/salus/](https://github.com/rivosinc/salus/)
- **Cerberus: A Formal Approach to Secure and Efficient Enclave Memory Sharing (CCS 2022)** [https://github.com/cerberus-ccs22/TAPC](https://github.com/cerberus-ccs22/TAPC)
- **Elasticlave: An Efficient Memory Model for Enclaves (USENIX Security 2022)** [https://github.com/jasonyu1996/elasticlave](https://github.com/jasonyu1996/elasticlave)
- **TwinVisor: Hardware-isolated Confidential Virtual Machines for ARM (SOSP 2021)** [https://github.com/TwinVisor](https://github.com/TwinVisor)
- **Kata Containers** [https://github.com/kata-containers/kata-containers](https://github.com/kata-containers/kata-containers)
- **AWS Nitro Enclaves: CPU and memory isolation for Amazon EC2 instances using Nitro Hypervisor** [https://github.com/aws/aws-nitro-enclaves-cli](https://github.com/aws/aws-nitro-enclaves-cli)
- **TD-shim: Confidential Containers Shim Firmware** [https://github.com/confidential-containers/td-shim](https://github.com/confidential-containers/td-shim)
- **AMD SEV-SNP measurement** [https://github.com/IBM/sev-snp-measure](https://github.com/IBM/sev-snp-measure)
- **Key Broker Server for SEV(-ES)** [https://github.com/confidential-containers/simple-kbs](https://github.com/confidential-containers/simple-kbs)
- **A dynamic library providing Virtualization-based process isolation capabilities, also capable of creating TEEs using AMD SEV(-ES)** [https://github.com/containers/libkrun](https://github.com/containers/libkrun)
- **Smart Object Oriented: Mobile Entities Migration Between Smart Objects For Fully Decentralized and Autonomous Embedded Systems** [https://github.com/smartobjectoriented/soo](https://github.com/smartobjectoriented/soo)
- **mTower: designed for MicroController Units (MCUs) that support ARM TrustZone** [https://github.com/Samsung/mTower](https://github.com/Samsung/mTower)

## Other TEEs

- **Reference implementation of Arm-CCA RMM specification** [https://github.com/TF-RMM/tf-rmm](https://github.com/TF-RMM/tf-rmm)
- **ARM CCA feature emulation on QEMU** [https://github.com/Huawei/Huawei_CCA_QEMU](https://github.com/Huawei/Huawei_CCA_QEMU)
- **ARMv9 CCA + Samsung ISLET: enable on-device confidential computing for end users on ARM devices** [https://github.com/Samsung/islet](https://github.com/Samsung/islet)
- **Linux Security Hardening for Confidential Compute** [https://github.com/intel/ccc-linux-guest-hardening](https://github.com/intel/ccc-linux-guest-hardening)
- **AMD SEV-SNP** [https://github.com/AMDESE/sev-guest](https://github.com/AMDESE/sev-guest)
- **Intel TDX** [https://github.com/intel/tdx-tools](https://github.com/intel/tdx-tools)
- **Secure Processing Unit (SPU), a provable, measurable secure computation device** [https://github.com/secretflow/spu](https://github.com/secretflow/spu)
- **Penglai-Enclave: Open-sourced secure and scalable TEE system for RISC-V (OSDI 2021)** [https://github.com/Penglai-Enclave/Penglai-Enclave](https://github.com/Penglai-Enclave/Penglai-Enclave)
- **IBM OpenPOWER Protected Execution Facility (EuroSys 2021)** [https://github.com/open-power/ultravisor](https://github.com/open-power/ultravisor)
- **A Lightweight Trusted Execution Environment for Secure IoT Devices (CCS 2021)** [https://github.com/sancus-tee](https://github.com/sancus-tee)
- **Keystone: An Open-Source Secure Enclave Framework for RISC-V Processors (EuroSys 2020)** [https://github.com/keystone-enclave/keystone](https://github.com/keystone-enclave/keystone)
- **MultiZone Security TEE for RISC-V processors** [https://github.com/hex-five/multizone-sdk](https://github.com/hex-five/multizone-sdk)
