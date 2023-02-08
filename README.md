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
![image](https://user-images.githubusercontent.com/114006998/217606783-31d09ae6-c950-4d1a-873c-e7806464dab1.png)
3. Here is the list of the style-variables used

| Pico Variable | Zesty Variable | Use | 
| ------------- | ------------- | ------------- |
|  primary-color  |  primary  |  Primary color for elements  |
|  secondary-color  |  secondary  |  Secondary color for elements  |
|  black  |  dark  |  Base color for dark theme  |
|  white  |  light  |  Base color for light theme  |
|  text-color  |  paragraph-font-color  |  Base color for paragraph texts  |
|  header-color  |  headings-custom-color  |  Base color for headings texts  |
|  text-font  |  font-family-base |  The font family base of all text elements  |
|  header-font  |  headings-font-base  |  The font family base of all headings (<h1-6>)  |

## Setting the value of dark-color
1. Go to `Settings` -> `Body Colors & Spacing`
![image](https://user-images.githubusercontent.com/114006998/217230180-e13fb6ec-74bd-4e8a-94b2-ba3b32555e41.png)
2. Click the `Color picker` icon besides the `@dark-color` and choose a color -> Click `Ok`.
![image](https://user-images.githubusercontent.com/114006998/217607477-5e8b5722-518c-416e-af1c-f6472890c070.png)
3. Click `Save Settings` or `Ctrl + S` -> Preview `Pico module`.
4. `Dark theme` is now based on the newly selected color.
![image](https://user-images.githubusercontent.com/114006998/217053793-ae66425c-4970-4d84-b8fe-567834e45d39.png)

## Setting the value of light-color
1. Go to `Settings` -> `Body Colors & Spacing`
![image](https://user-images.githubusercontent.com/114006998/217230195-cbbb2d15-a9fe-4377-a927-d2b5a5521f46.png)
2. Click the `Color picker` icon besides the `@light-color` and choose a color -> Click `Ok`.
![image](https://user-images.githubusercontent.com/114006998/217607740-aa0d4329-66c5-4f63-ba9f-7f4b48b1a0c9.png)
3. Click `Save Settings` or `Ctrl + S` -> Preview `Pico module`.
4. `Light theme` is now based on the newly selected color.
![image](https://user-images.githubusercontent.com/114006998/217054331-20f17b22-4d46-4b0e-8ac4-077502fb1cc7.png)

## Setting the value of primary
1. Go to `Settings` -> `Body Colors & Spacing`
![image](https://user-images.githubusercontent.com/114006998/217230205-8648b469-b2ac-45d0-bf5f-b9bc661fed72.png)
2. Click the `Color picker` icon besides the `@primary` and choose a color -> Click `Ok`.
![image](https://user-images.githubusercontent.com/114006998/217608421-b66cb69e-7a66-4b18-a32b-85a2a1e50c89.png)
3. Click `Save Settings` or `Ctrl + S` -> Preview `Pico module`.
4. Primary elements (eg.buttons, links, etc.) are now based on the newly selected color.
![image](https://user-images.githubusercontent.com/114006998/217054817-b4dc03d8-676f-4392-9f98-6f1614c76743.png)

## Setting the value of secondary
1. Go to `Settings` -> `Body Colors & Spacing`
![image](https://user-images.githubusercontent.com/114006998/217230217-bea029d7-fa9f-42cc-aa65-b9a134a88508.png)
2. Click the `Color picker` icon besides the `@secondary` and choose a color -> Click `Ok`.
![image](https://user-images.githubusercontent.com/114006998/217608580-9852273c-6e9d-4b7b-97bd-b6151a180856.png)
3. Click `Save Settings` or `Ctrl + S` -> Preview `Pico module`.
4. Secondary elements (eg.buttons, links, etc.) are now based on the newly selected color.
![image](https://user-images.githubusercontent.com/114006998/217055075-59f65a07-30bf-43bc-8a2b-7c541d65a29d.png)
![image](https://user-images.githubusercontent.com/114006998/217055134-05e096ce-c215-4961-940a-0d3c0fc66bf7.png)

## Setting the value of paragraph-font-color
1. Go to `Settings` -> `Typography`
![image](https://user-images.githubusercontent.com/114006998/217230685-9725d472-83b3-4cce-9036-da1c3e7965e5.png)
2. Click the `Dropdown` icon besides the `@paragraph-font-color` and choose a color variable -> Click `Ok`.
![image](https://user-images.githubusercontent.com/114006998/217615362-a1a782e0-a58b-4757-925f-7224fa50b78b.png)
3. Click `Save Settings` or `Ctrl + S` -> Preview `Pico module`.
4. Paragraph texts are now based on the newly selected color variable.

## Setting the value of headings-custom-color
1. Go to `Settings` -> `Typography`
![image](https://user-images.githubusercontent.com/114006998/217230695-21ae4688-8bf4-4f89-a47f-5f21bbfc333d.png)
2. Click the `Dropdown` icon besides the `@headings-custom-color` and choose a color variable -> Click `Ok`.
![image](https://user-images.githubusercontent.com/114006998/217615470-0432ea4a-fa6d-408d-9cd4-6836667457d4.png)
3. Click `Save Settings` or `Ctrl + S` -> Preview `Pico module`.
4. Headings text are now based on the newly selected color variable.

## Setting the value of headings-font-base
1. Go to `Settings` -> `Typography`
![image](https://user-images.githubusercontent.com/114006998/217230695-21ae4688-8bf4-4f89-a47f-5f21bbfc333d.png)
2. Click the `Dropdown` icon besides the `@headings-font-base` and choose a font -> Click `Ok`. -> `Save or Ctrl + S`
![image](https://user-images.githubusercontent.com/114006998/217618101-04faa345-835e-4356-a3d3-98aae306a1e3.png)
3. Headings font are now based on the newly selected font-family.
![image](https://user-images.githubusercontent.com/114006998/217619270-f7d8c527-63c6-429a-a195-5cfa2a4ad51b.png)

## Setting the value of font-family-base
1. Go to `Settings` -> `Typography`
![image](https://user-images.githubusercontent.com/114006998/217230695-21ae4688-8bf4-4f89-a47f-5f21bbfc333d.png)
2. Click the `Dropdown` icon besides the `@font-family-base` and choose a font -> Click `Ok`. -> `Save or Ctrl + S`
![image](https://user-images.githubusercontent.com/114006998/217618756-87f90f9c-ab0e-4da4-be01-faf2a4772b5b.png)
3. Texts font are now based on the newly selected font-family.
![image](https://user-images.githubusercontent.com/114006998/217619467-c7f6087e-1501-49ba-951f-2fd7d90a2357.png)

