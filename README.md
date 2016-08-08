# NYProgressHUD
基于MBProgressHUD的封装

使用方法：

+ + (void)showToastText:(NSString *)text;
    单例方法，根据字数隐藏
+ + (void)showToastText:(NSString *)text completion:(void(^)())completionBlock;
    单例方法，根据字数隐藏，同时提供隐藏后的block
- - (void)showAnimationWithText:(NSString *)text;
    实例化hud
- - (void)hide;
    隐藏hud
