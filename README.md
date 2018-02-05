# TransparentColorCode

If you are using below code then it will return you transparent string code:-
    // transparentColor40() method returns you 10% of color transparency
    ColorTransparentUtils.transparentColor10(R.color.colorAccent);

    // transparentColor40() method returns you 40% of color transparency
    ColorTransparentUtils.transparentColor40(R.color.colorAccent);
    
If you want specific transparent code then you have to use below code:-
    // convertIntoColor() method accept color code with transparent code.
    // return you specific(which you pass into method) color transparency 
    ColorTransparentUtils.convertIntoColor(R.color.colorAccent,45);
    
