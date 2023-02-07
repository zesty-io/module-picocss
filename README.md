# PicoCSS Module
- Module PicoCSS Framework


## Using Theme Switcher 
> For theme switcher informtion and uses.
1. Selecting `Auto` will change the background color based on the User's device settings.
![image](https://user-images.githubusercontent.com/114006998/217041495-ffe33b69-b319-4b98-8c5b-ce3f40fed8e2.png)
2. Selecting `Light` will change the background color to light themed.
![image](https://user-images.githubusercontent.com/114006998/217041741-d04ad4cc-c436-4193-bab5-c2ad951d2edc.png)
3. Selecting `Dark` will change the background color to dark themed.
![image](https://user-images.githubusercontent.com/114006998/217041851-47cf3166-fd82-4955-b6b0-7e6e1e470ec4.png)


## Style Variables
> For style variables declaration.
1. Go to `Code` -> `pico-module-theme.css`.
2. Search for `Variables` or go line `64`.
![image](https://user-images.githubusercontent.com/114006998/217044748-8ac29078-dadd-47aa-929a-d08cd2a620da.png)
3. Here is the list of the style-variables used

| Pico Variable | Zesty Variable | Use | 
| ------------- | ------------- | ------------- |
|  black  |  dk-color  |  Base color for dark theme  |
|  white  |  li-color  |  Base color for light theme  |
|  primary  |  primary-color  |  Primary color for elements  |
|  secondary  |  secondary-color  |  Secondaray color for elements  |
|  contrast  |  contrast-color  |  Contrast color for elements  |
|  text-color  |  paragraph-font-color  |  Base color for paragraph texts  |
|  header-color  |  headings-font-color  |  Base color for headings texts  |

## Setting the value of dk-color
1. Go to `Settings` -> `Body Colors & Spacing` -> `@dk-color`
![image](https://user-images.githubusercontent.com/114006998/217230180-e13fb6ec-74bd-4e8a-94b2-ba3b32555e41.png)
2. Click the `Color picker` icon besides the `@dk-color` and choose a color -> Click `Ok`.
![image](https://user-images.githubusercontent.com/114006998/217053490-13ad9af1-aa24-48c4-8c46-591ceb74793c.png)
3. Click `Save Settings` or `Ctrl + S` -> Preview `Pico module`.
4. `Dark theme` is now based on the newly selected color.
![image](https://user-images.githubusercontent.com/114006998/217053793-ae66425c-4970-4d84-b8fe-567834e45d39.png)

## Setting the value of li-color
1. Go to `Settings` -> `Body Colors & Spacing` -> `@li-color`
![image](https://user-images.githubusercontent.com/114006998/217230195-cbbb2d15-a9fe-4377-a927-d2b5a5521f46.png)
2. Click the `Color picker` icon besides the `@li-color` and choose a color -> Click `Ok`.
![image](https://user-images.githubusercontent.com/114006998/217054046-97783f91-0521-469c-9f88-f3cd93a053f0.png)
3. Click `Save Settings` or `Ctrl + S` -> Preview `Pico module`.
4. `Light theme` is now based on the newly selected color.
![image](https://user-images.githubusercontent.com/114006998/217054331-20f17b22-4d46-4b0e-8ac4-077502fb1cc7.png)

## Setting the value of primary-color
1. Go to `Settings` -> `Body Colors & Spacing` -> `@primary-color`
![image](https://user-images.githubusercontent.com/114006998/217230205-8648b469-b2ac-45d0-bf5f-b9bc661fed72.png)
2. Click the `Color picker` icon besides the `@primary-color` and choose a color -> Click `Ok`.
![image](https://user-images.githubusercontent.com/114006998/217054554-198b129f-8443-4a96-9f1c-b7055a82cc83.png)
3. Click `Save Settings` or `Ctrl + S` -> Preview `Pico module`.
4. Primary elements (eg.buttons, links, etc.) are now based on the newly selected color.
![image](https://user-images.githubusercontent.com/114006998/217054817-b4dc03d8-676f-4392-9f98-6f1614c76743.png)

## Setting the value of secondary-color
1. Go to `Settings` -> `Body Colors & Spacing` -> `@secondary-color`
![image](https://user-images.githubusercontent.com/114006998/217230217-bea029d7-fa9f-42cc-aa65-b9a134a88508.png)
2. Click the `Color picker` icon besides the `@secondary-color` and choose a color -> Click `Ok`.
![image](https://user-images.githubusercontent.com/114006998/217054954-d4c3e1d0-62ff-4f9b-8ae0-35aae3d50489.png)
3. Click `Save Settings` or `Ctrl + S` -> Preview `Pico module`.
4. Secondary elements (eg.buttons, links, etc.) are now based on the newly selected color.
![image](https://user-images.githubusercontent.com/114006998/217055075-59f65a07-30bf-43bc-8a2b-7c541d65a29d.png)
![image](https://user-images.githubusercontent.com/114006998/217055134-05e096ce-c215-4961-940a-0d3c0fc66bf7.png)

## Setting the value of contrast-color
1. Go to `Settings` -> `Body Colors & Spacing` -> `@contrast-color`
![image](https://user-images.githubusercontent.com/114006998/217230229-25d83770-bb2f-41f4-8771-424897d6a38b.png)
2. Click the `Color picker` icon besides the `@contrast-color` and choose a color -> Click `Ok`.
![image](https://user-images.githubusercontent.com/114006998/217055456-38dbe418-5c8d-4259-a315-de8fbacfc0be.png)
3. Click `Save Settings` or `Ctrl + S` -> Preview `Pico module`.
4. Contrast degree in elements (eg.buttons, links, blocks, etc.) are now based on the newly selected color.
![image](https://user-images.githubusercontent.com/114006998/217055744-a24488da-f673-45f1-a1eb-8ed3a072cd57.png)

## Setting the value of paragraph-font-color
1. Go to `Settings` -> `Typography` -> `@paragraph-font-color`
![image](https://user-images.githubusercontent.com/114006998/217230685-9725d472-83b3-4cce-9036-da1c3e7965e5.png)
2. Click the `Dropdown` icon besides the `@paragraph-font-color` and choose a color variable -> Click `Ok`.
3. Click `Save Settings` or `Ctrl + S` -> Preview `Pico module`.
4. Paragraph texts are now based on the newly selected color variable.

## Setting the value of headings-font-color
1. Go to `Settings` -> `Typography` -> `@headings-font-color`
![image](https://user-images.githubusercontent.com/114006998/217230695-21ae4688-8bf4-4f89-a47f-5f21bbfc333d.png)
2. Click the `Dropdown` icon besides the `@headings-font-color` and choose a color variable -> Click `Ok`.
3. Click `Save Settings` or `Ctrl + S` -> Preview `Pico module`.
4. Headings text are now based on the newly selected color variable.
