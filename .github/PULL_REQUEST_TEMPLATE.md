# 🍌 Prompt Contribution

Thank you for contributing to the Prompt Archive! 

## 📝 Description
<!-- Briefly describe the prompt you are adding or the changes you are making. -->


## 🎨 Prompt Details
- **Prompt Type**: <!-- [Text / JSON] -->
- **Model Compatibility**: <!-- e.g., Midjourney v6, DALL-E 3, Stable Diffusion XL -->
- **Has Reference Image?**: <!-- [Yes / No] -->

## ✅ Checklist
Please ensure you have completed the following steps:

- [ ] **Data Entry**: Added the new prompt object to `data.json` with a unique ID (increment the last ID).
- [ ] **Reference Support**: 
    - [ ] If this is a `json` prompt for Midjourney, did you include the standard "Using Reference Photo" instructions in `withReferenceUpload.reference_image.notes`?
    - [ ] Verified that the "Generic" vs "Reference" tabs work correctly for this prompt.
- [ ] **Images**: 
    - [ ] Included at least one example image URL in the `imageUrls` array. 
    - [ ] If hosting locally/in-repo, ensured images are optimized? (External URLs preferred for now).
- [ ] **Twitter/X**: Included the original tweet URL if this is from a specific creator?
- [ ] **Testing**: Verified the prompt displays correctly in the UI grid.

## 📸 Screenshots (Optional)
<!-- If you modified the UI, please include a screenshot here. -->
