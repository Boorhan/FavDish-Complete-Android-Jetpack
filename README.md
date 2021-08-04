# FavDish-Complete-Android-Jetpack

For beginners, all about [readme](https://github.com/fefong/markdown_readme#Getting-started-with-Markdown)

## Glide
Third Party Library for media management and image loading framework for Android. It wraps media decoding, memory and disk caching, and resource pooling into a simple and easy to use interface. Its a very powerful tool. I will recommend it if you are working with image and media management.
Click [here](https://github.com/bumptech/glide)

Some key Features Glide's provided that will make your life easier to coding
- Image cropping
- Circle shape for an imgae
- placeholder
- erro placeholder

Glide.with(this)\
&ensp;&ensp;&ensp;&ensp;  .load(thumbnail)      &ensp;                : loading the image from bitmap,uri, url etc.\
&ensp;&ensp;&ensp;&ensp;  .centerCrop()          &ensp;&ensp;&ensp;&ensp;                : keep the center and crop maintaining the x,y\
&ensp;&ensp;&ensp;&ensp;  .circleCrop()         &ensp;&ensp;&ensp;&ensp;&ensp;                 : magic comes here, this will crop your image in rounded figure\
&ensp;&ensp;&ensp;&ensp;  .placeholder(R.drawable.error_image) &ensp;  : placeholder, you can also use errorPlaceholder\
&ensp;&ensp;&ensp;&ensp;  .into(audBinding.ivDishImage) &ensp;&ensp;&ensp;&ensp;         : most important thing, where you want to set you image\



## Dexter
Its a very easy tool for permission checking. Click [here](https://github.com/Karumi/Dexter)
