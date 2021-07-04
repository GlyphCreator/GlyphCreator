# GlyphCreator Data
<!-- The training dataset is being prepared and will be made public soon... -->

GlyphCreator dataset is a circular glyph dataset generated by D3.js.
The generation is based on a design space concluded from our comprehensive study on all circular glyphs in VisImages, a visualization dataset of images from IEEE VIS proceedings.
The dataset includes two parts: training data (8928 images) and validation data (2232 images).

We used the same metrics as in the Microsoft Common Objects in
COntext (MS COCO) dataset to unify the format of annotations.
Each image is annotated by the types and locations (represented as bounding boxes) of all visual elements included.
Moreover, the center of the glyph is annotated as the "center" type.

## Files
1. train/. - training images
2. val/. - validation images
3. Glyph_train.json - all annotations of training images
4. Glyph_val.json - all annotations of validation images


