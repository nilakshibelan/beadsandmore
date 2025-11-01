# Product Image Organization Guide

## Overview
Your website now has 40 organized folders for systematic product image management. Each folder corresponds to a specific product category in your catalog.

## Folder Structure
All product image folders are located in: `/images/`

### Complete Category List (40 Folders):

#### Religious Items
1. **Laxmi-Paula** - Decorative religious items for Laxmi worship
2. **Gopadma** - Traditional worship accessories
3. **Swastik** - Auspicious symbols and decorations
4. **Niranjan** - Special religious ceremony items
5. **Durva** - Sacred grass arrangements
6. **Paan** - Betel leaf decorations
7. **Belache-Paan** - Decorative betel leaf items
8. **Supari** - Areca nut decorations
9. **Mango-Leaf** - Traditional mango leaf arrangements
10. **Vidyache-Paan** - Educational ceremony betel leaves
11. **Aaptyache-Paan** - Special occasion betel leaves
12. **Tulshi-Vrundavan** - Sacred basil arrangements
13. **Ashtadal** - Eight-petaled religious designs

#### Festival & Ceremony Items
14. **Thali-Mahirap** - Decorative ritual plates
15. **Samai-Mahirap** - Ceremonial arrangements
16. **Niranjan-Mahirap** - Special ceremony plates
17. **Kalash** - Sacred water pots
18. **Kalash-Stand** - Stands for sacred vessels
19. **Samai** - Ceremonial items
20. **Haldi-Kumkum-Set** - Turmeric and vermillion sets
21. **Laxmi-Set** - Complete Laxmi worship sets
22. **Devi-Combo-Set** - Goddess worship combinations
23. **Chourang-Mahirap** - Four-colored ceremonial items

#### Rangoli & Decorative
24. **Rangoli-3-Vari** - Three-tier rangoli designs
25. **Rangoli-Full-Set** - Complete rangoli collections
26. **Haldi-Kumkum-Rangoli** - Turmeric-vermillion rangoli
27. **Rangoli-Ghodi** - Horse-themed rangoli

#### Traditional Textiles
28. **Saree-Khan-Set** - Saree and tray combinations
29. **Khan** - Decorative trays
30. **Moti-Paat** - Pearl decorative strips
31. **Moti-Chourang** - Pearl four-colored items
32. **Laxmi-Aasan** - Goddess seating arrangements

#### Decorative Items
33. **Toran** - Door hangings and decorations
34. **Name-Patti** - Personalized name boards
35. **Flowers** - Artificial and decorative flowers
36. **Haar** - Decorative garlands
37. **Panati** - Traditional panels
38. **Bandhanwar** - Door decorations
39. **Ghodi** - Decorative horses

#### Accessories
40. **Small-Moti-Aasan** - Small pearl seating
41. **Beaded-Keychain** - Decorative keychains
42. **Tea-Coaster** - Decorative coasters

## Image Upload Guidelines

### File Naming Convention
Use descriptive names for easy identification:
- `product-name-color-size.jpg`
- Example: `laxmi-paula-gold-medium.jpg`
- Example: `rangoli-red-blue-large.jpg`

### Image Requirements
- **Format**: JPG, PNG, or WebP
- **Resolution**: Minimum 800x800 pixels for product detail view
- **File Size**: Keep under 2MB for fast loading
- **Quality**: High quality, well-lit product photos

### Organization Tips
1. **Multiple Views**: Upload 3-5 images per product
   - Main product view
   - Close-up details
   - Different angles
   - In-use/styled shots

2. **Consistent Lighting**: Use consistent lighting across all photos in a category

3. **Background**: Use clean, neutral backgrounds for product clarity

## WhatsApp Marketing Integration

### Status Image Strategy
When uploading images for WhatsApp status:
1. Choose your best product photos from each category folder
2. Add your website link in the status text: `beadsandmore.com`
3. Include category name and price in status text
4. Use different products daily to showcase variety

### Link-in-Bio Integration
- Main featured products should be in their respective category folders
- Update `link-in-bio.html` to reference organized image paths
- Use high-quality images for the featured products section

## Website Integration

### Modal System
Your website's modal system will automatically display images from these organized folders. Update the product data in `index.html` to reference the correct folder paths:

```javascript
// Example product data structure
{
    name: "Laxmi Paula Set",
    category: "Religious Items",
    price: "₹299",
    images: [
        "images/Laxmi-Paula/main-view.jpg",
        "images/Laxmi-Paula/detail-view.jpg",
        "images/Laxmi-Paula/styled-view.jpg"
    ],
    description: "Beautiful decorative Laxmi Paula for worship"
}
```

## Quick Upload Checklist
- [ ] Choose appropriate category folder
- [ ] Use descriptive file names
- [ ] Ensure good image quality
- [ ] Upload multiple views of each product
- [ ] Update product data in website if needed
- [ ] Test image display in modal system

## Benefits of This Organization
1. **Easy Management**: Find specific product images quickly
2. **Scalable**: Add new products to appropriate categories
3. **WhatsApp Ready**: Organized images for daily status updates
4. **Website Integration**: Systematic paths for modal system
5. **Professional Presentation**: Consistent organization across all channels

## Next Steps
1. Start uploading your product images to appropriate folders
2. Update any hardcoded image paths in your website
3. Test the modal system with organized images
4. Create a regular schedule for WhatsApp status updates using different category folders

Your product image organization system is now complete and ready to support your growing business and WhatsApp marketing strategy!