# Hestia Libraries - `HestiaAI`

[![Hestia Libraries](https://raw.githubusercontent.com/ChewKeanHo/hestiaTOML/main/src/icons/banner_1200x270.svg)](#)

One Peaceful Frontend+Backend Software Library Suite.

This repository facilitates neural network artificial intelligence (AI) related
application-based protocol interfaces (API) functions. Its purpose is to
house prompt keywords and facilitates semi-automated prompt construction use.

For specific neural network functionalities and low-level construction, please
refer to its type from the Hestia library suites (e.g. `HestiaTENSORFLOW` for
TensorFlow).




## Why It Matters

This project was initiated primarily because of:

1. **Performs keywords grouping for higher accuracy prompting** - certain
   keywords when grouped can yield a more accurate generative output with higher
   confidences.
2. **Semi-automated prompt constructions** - Sometimes, one would just want to
   automate grouped keywords with toggles.
3. **Friendly to low memory and low footprint environment** - usable anywhere
   anytime.
4. **Consumption freedom** - Makes NO decision and NO assumption on how you
   consume the grouped keywords.
5. **Simple to integrate** - simple enough to use for all supported programming
   languages.




## Design Principles

The definitions complies to only the following rules:

1. **STRICTLY**: **Everthing is a `string`**. Prompts are string anyway.
2. Primarily uses Unicode for internal operations.
3. Uses supported API from available vendors both locally and remotely.

This library is heavily guarded with localized unit tests whenever available.




## Setup

This library supports multiple programming languages for the same dataset.
Please import based on your programming language(s) using the instructions in
the sub-sections below.

Please do note that branches like `main`, `next`, and `experimental` are for
maintenance & development uses (as in, the production factory itself). Hence,
please avoid them and only use it at your own risk.


### Prechance.org

This library is supported based on what you're interested and usage. The current
URLs would be:

* Prompt Engineering: [src/prompt-keywords](/src/prompt-keywords)
* Text2Image: https://perchance.org/clean-text2image


### Dependencies

This library depends on the following libraries:

1. **HestiaSTRING** - https://github.com/ChewKeanHo/HestiaSTRING




## Data Source

The libraries are based on the following data sources:

1. Perchance - https://perchance.org/generators




## License

This project is licensed under [Chew Kean Ho's Hestia License Agreement](LICENSE.pdf).
