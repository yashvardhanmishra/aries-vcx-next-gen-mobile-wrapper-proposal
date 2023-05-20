# Aries-VCX Next-Gen Mobile Wrapper

#### Author : [@Yashvardhan mishra](https://github.com/yashvardhanmishra)


# Contents
[1. Background](#background)   
[2. Objectives](#objectives)    
[3. Proposal](#proposal)        
[4. Initial Experimentation](#initial-experimentation)   
[5. References](#references)



## Background
The Aries-VCX library is a powerful tool for building SSI wallets with support for Aries and DIDComm protocols. However, there is a need for a mobile-specific wrapper to improve its usability and compatibility on mobile platforms. This project aims to fill that gap by creating a Rust crate that generates mobile bindings for the Aries-VCX library.

## Objectives
1. Develop the "uniffi_aries_vcx" Rust crate to generate mobile bindings for Aries-VCX.
2. Implement a mediator client with Aries message pick-up protocol support.
3. Create a simple Android demo application showcasing the capabilities of the wrapper.
4. Establish continuous integration (CI) jobs for build automation and testing of the wrapper.


## Proposal
### Objective 1: Develop the "uniffi_aries_vcx" Rust crate
1. Conduct research and analysis to understand the Aries-VCX library and identify necessary Rust features and bindings.
2. Create the uniffi_aries_vcx Rust crate to generate mobile bindings for Aries-VCX.
3. Implement the required Rust features, APIs, and bindings to establish seamless integration between Aries-VCX and mobile platforms.

### Objective 2: Implement a mediator client with Aries message pick-up protocol support

1. Extend the uniffi_aries_vcx crate with a mediator client.
2. Research and understand the Aries message pick-up protocol.
3. Implement the necessary functionality to support the Aries message pick-up protocol in the mediator client.
4. Integrate the mediator client with the Aries-VCX library to enable efficient communication and message exchange.

### Objective 3: Create a simple Android demo application

1. Develop an Android application that serves as a demo for the uniffi_aries_vcx wrapper.
2. Implement the necessary user interface components and functionality to showcase the capabilities of the wrapper.
3. Test the Android demo application on simulators and physical devices to ensure compatibility and proper integration with the "uniffi_aries_vcx" wrapper.

### Objective 4: Establish continuous integration (CI) jobs

1. Set up CI jobs to automate the build process for Kotlin and iOS bindings of the uniffi_aries_vcx wrapper.
2. Configure CI tests to ensure the stability, reliability, and compatibility of the wrapper across different mobile platforms.
3. Monitor and review the CI pipeline regularly to identify and address any build or test failures.


### Initial Experimentation

Throughout the mentorship program, regular experimentation and testing will be conducted to validate the functionality, performance, and compatibility of the wrapper. This will involve building and running the Android demo application in simulators and physical devices, as well as conducting integration tests with existing Aries-VCX instances. Feedback and suggestions from the mentor and the community will be gathered and incorporated to enhance the wrapper's features and address any identified issues.

### References

Aries-VCX Library: [hyperledger/aries-vcx](https://github.com/hyperledger/aries-vcx)                
Aries Message Pick-up Protocol: [Aries message pick-up protocol documentation](https://github.com/hyperledger/aries-rfcs/tree/main/features/0685-pickup-v2)
