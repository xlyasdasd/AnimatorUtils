# 使用  
```  
   new AnimatorUtils().makeAnimation(view)  
                .addTranslate(ANIMATION_TIME, AnimatorUtils.RIGHT_DIRECTION, TRANSLATE_LENGTH, null)  
                .after()  
                .addTranslate(ANIMATION_TIME, AnimatorUtils.UP_DIRECTION, TRANSLATE_LENGTH, null)  
                .addAlphaAnimation(ANIMATION_TIME, FROM_ALPHA, FINAL_ALPHA, null)  
                .after()  
                .addAlphaAnimation(ANIMATION_TIME, FROM_ALPHA, FINAL_ALPHA, null)  
                .addTranslate(ANIMATION_TIME, AnimatorUtils.DOWN_DIRECTION, TRANSLATE_LENGTH, null)  
                .after()  
                .addWidthChangeAnimator(ANIMATION_TIME, FROM_WIDTH, FINAL_WIDTH, null);  

```   
# 效果  
<img src="https://github.com/xlyasdasd/AnimatorUtils/blob/master/demo.gif" width="800" height="800" alt="效果"/>
