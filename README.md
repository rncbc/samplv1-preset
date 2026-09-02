# SamplV1 Factory Presets

A collaborative repository of factory presets for SamplV1. 
If you want to submit your own presets, we are keen to include them, provided they meet the requirements below.

## Requirements

### 1. Mandatory License: Creative Commons Zero (CC0) 1.0
Your presets and samples must be released strictly under the **Creative Commons Zero (CC0) 1.0 Universal (Public Domain)** license.

* **Why?** Must be easily editable and shareable. Attribution-locked licenses require extra tracking documentation, which is neither practical nor viable for this project.
* **Credit:** Recognition is fundamental to us. We highly recommend including your author metadata within the file.

### 2. Authorized Samples Only

**To ensure that the samples we receive are universally usable, we only accept:**
* Original acoustic recordings from the preset's author.
* Samples from libraries or synthesizers included in our [list of Authorized Resources](https://github.com/rncbc/samplv1-preset/blob/main/AUTHORICED_RESOURCES.md).

**Contributor Responsibility:**
You are responsible for being the original author of the samples or for ensuring that it comes from our [list of Authorized Resources](https://github.com/rncbc/samplv1-preset/blob/main/AUTHORICED_RESOURCES.md).

**Take-down Policy:**
If an copyright infringement is reported, the material will be verified and removed from the repository immediately.

### 3. Audio Optimization in Samples

* **Format:** All audio samples must be compressed in **OGG** format.
* **Size:** No single audio sample may exceed **100 KiB** in size.
* **Upload Criteria:** Upload a new audio sample only if absolutely necessary. We prioritize using existing base samples within the repository, transforming them using SamplV1's internal parameters and engine.

### 4. Immutability of Presets and Samples
**It is strictly forbidden to update or overwrite an existing preset or sample.** 

* To improve or vary an existing factory preset or sample, you must save and submit it under a **different name**.
### 5. Required Metadata
Before submitting, open your preset file in a text editor and include the metadata in the header.

**Example:**

```xml
<!DOCTYPE samplv1>
<preset name="MyPreset" collection="Vee One Factory" author="MyName (or alias)" license="Creative Commons Zero (CC0) 1.0 Universal">
 <comments>
    You can use the comments tag to:
    * Credit the original preset (if it is a variant)
    * Specify technical details and the source of the samples
    * Add usage recommendations
    * Others
 </comments>
```

## Support and Suggestions
We do not use GitHub Issues for questions. Please submit all inquiries and suggestions to the [official SamplV1 forum](https://www.rncbc.org/drupal/forum/18).

## Submitting Presets
You are welcome to submit multiple presets at once. We do not accept configuration files (`.samplv1.conf`) used to supply banks. To propose new banks, please open a discussion thread in the [official SamplV1 forum](https://www.rncbc.org/drupal/forum/18.

### Submission Methods
* **Via GitHub:** Fork this repository, create a branch, and submit a Pull Request with your presets (including those samples that are not in the repository).
* **Via Forum:** Register at the [official SamplV1 forum](https://www.rncbc.org/drupal/forum/18) and post your presets (including those samples that are not in the repository) inside a compressed `.zip` file.
