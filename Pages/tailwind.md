# Tailwind

Tailwind is CSS framework that I often see Gemini utilized when asked to generate a webpage. I'm still getting familiar with it. Below are some notes about available classes--not a complete list. 

## Classes

- sticky
- top-0
- text-center

### Background

Looks like there are many background options with the option to set the background to any hex code color.

- bg-white
- bg-gray-50
- bg-[#497177]

### Rounded Corners

Different level of roundness from least to most.

- `rounded-sm`
- `rounded`
- `rounded-md`
- `rounded-lg`
- `rounded-xl`
- `rounded-2xl`
- `rounded-3xl`
- `rounded-full`: Set for my navigation header.

### Spacing

If you have a div with containers inside, the space number will determine how much space you want between each container.

- `space-y-16`
- `space-y-8`: Set for the distance between my cards
- `space-y-4`: Set for the distance between the items within my cards.

### Text Color

- `text-white`

Tailwind has a color shading system. The steps are in increments of 100, except for the lightest (50) and darkest (950) shade. 

- `text-blue-600`
- `text-indigo-700`
- `text-gray-500`

### List

- `list-disc`
- `list-decimal`
- `pl-5`: Determine the left padding
- `marker:text-blue-800`: Set's color of the list marker. Allowing it to be separate from the text color. 
