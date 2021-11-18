# App Samples

-   [Introduction](#section1470103520301)
-   [Usage](#section17988202503116)
-   [Limitations](#section18841871178)
-   [Repositories Involved](#section741114082513)

## Introduction

We provide a series of app samples to help you quickly get familiar with the APIs and app development process of the HarmonyOS SDKs. Each app sample is an independent project in DevEco Studio. You can import a project into DevEco Studio to learn how to use APIs in the sample by browsing code, building the project, and installing and running the app.

## Usage

1.  Import an independent app sample project into DevEco Studio for compilation, building, running, and debugging.
2.  Some samples contain multiple modules. You can compile and build a single module to generate a HAP file or compile and build the entire project to generate multiple HAP files.
3.  After HAP installation and execution, you can view the execution effect of the sample on the device and then conduct debugging.

## Limitations

1.  Before installing and running the sample, check the  **deviceType**  field in the  **config.json**  file to obtain the device types supported by the sample. You can modify this field to enable the sample to run on your target device. \(The  **config.json**  file is generally stored in the  **entry/src/main**  directory, which may be different depending on the samples.\)
2.  If you want to run the app sample on HarmonyOS, configure the development environment by referring to  [HUAWEI DevEco Studio User Guide](https://developer.harmonyos.com/en/docs/documentation/doc-guides/tools_overview-0000001053582387).
3.  App samples that can run on standard-system or small-system devices (as stipulated in **Readme**) must run on OpenHarmony, whereas those that can run on large-system devices must run on HarmonyOS.
4.  All app samples that must run on OpenHarmony are available in the [app_samples](https://gitee.com/openharmony/app_samples) repository in the OpenHarmony community.

## Repositories Involved

1.  HarmonyOS app samples for complicated scenarios: [HarmonyOS codelabs](https://gitee.com/harmonyos/harmonyos_codelabs)
2.  Basic OpenHarmony app samples: [OpenHarmony app_samples](https://gitee.com/openharmony/app_samples)
3.  OpenHarmony app samples for complicated scenarios: [OpenHarmony codelabs](https://gitee.com/openharmony/codelabs)
