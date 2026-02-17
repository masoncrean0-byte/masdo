void -[ACPanelController viewDidLoad](struct ACPanelController* self, SEL sel)
{
    int64_t x8 = *___stack_chk_guard;
    struct objc_super super;
    super.receiver = self;
    super.super_class = superRef_ACPanelController;
    _objc_msgSendSuper2(&super, "viewDidLoad");
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, "clearColor"));
    id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "view"));
    _objc_msgSend(obj_1, "setBackgroundColor:", obj);
    _objc_release(obj_1);
    _objc_release(obj);
    _objc_msgSend(self, "setSpawnQuantity:", 5);
    _objc_msgSend(self, "setSelectedIndex:", -1);
    _objc_msgSend(self, "setActiveCategory:", 0);
    id obj_2 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:", 0));
    id obj_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "view"));
    _objc_msgSend(obj_2, "setFrame:", _objc_msgSend(obj_3, "bounds"));
    _objc_release(obj_3);
    int64_t x2_2;
    int64_t x3;
    int128_t v0;
    int128_t v1;
    x2_2 = _objc_msgSend(obj_2, "setAutoresizingMask:", 0x12);
    double v15 = 0.5;
    v0 = 0.0;
    v1 = 0.5;
    id obj_4 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithWhite:alpha:", x2_2, x3));
    _objc_msgSend(obj_2, "setBackgroundColor:", obj_4);
    _objc_release(obj_4);
    _objc_msgSend(obj_2, "addTarget:action:forControlEvents:", self, "dismissPanel", 0x40);
    id obj_5 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "view"));
    _objc_msgSend(obj_5, "addSubview:", obj_2);
    _objc_release(obj_5);
    id obj_6 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "view"));
    double v8 = _objc_msgSend(obj_6, "bounds") + -30.0;
    _objc_release(obj_6);
    double temp0 = vmin_f64(v8, 360.0);
    id obj_7 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "view"));
    double width = _objc_msgSend(obj_7, "bounds") + -0x3fb7000000000000;
    _objc_release(obj_7);
    double temp0_1 = vmin_f64(width, 720.0);
    id obj_8 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "view"));
    width = (_objc_msgSend(obj_8, "bounds") - temp0) * v15;
    _objc_release(obj_8);
    id obj_9 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "view"));
    double v10 = (_objc_msgSend(obj_9, "bounds") - temp0_1) * v15;
    _objc_release(obj_9);
    id x0_38;
    int64_t x2_6;
    int128_t v0_5;
    int128_t v1_1;
    int128_t v2_2;
    int128_t v3_2;
    x0_38 = _objc_alloc(clsRef_UIView);
    v0_5 = width;
    v1_1 = v10;
    v2_2 = temp0;
    v3_2 = temp0_1;
    id obj_10 = _objc_msgSend(x0_38, "initWithFrame:", x2_6);
    _objc_msgSend(self, "setPanelView:", obj_10);
    int64_t x2_8;
    int64_t x3_1;
    int64_t x4;
    int64_t x5;
    int128_t v0_6;
    int128_t v1_2;
    int128_t v2_3;
    int128_t v3_3;
    x2_8 = _objc_release(obj_10);
    v0_6 = 0x3f9eb851eb851eb8;
    v1_2 = 0x3f947ae147ae147b;
    v2_3 = 0x3fb47ae147ae147b;
    v3_3 = 0x3fef0a3d70a3d70a;
    id obj_11 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:", x2_8, x3_1, x4, x5));
    id obj_12 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "panelView"));
    _objc_msgSend(obj_12, "setBackgroundColor:", obj_11);
    _objc_release(obj_12);
    _objc_release(obj_11);
    id obj_13 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "panelView"));
    id obj_14;
    int64_t x2_10;
    int128_t v0_7;
    obj_14 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_13, "layer"));
    v0_7 = 20.0;
    _objc_msgSend(obj_14, "setCornerRadius:", x2_10);
    _objc_release(obj_14);
    _objc_release(obj_13);
    id obj_15 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "panelView"));
    id obj_16 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_15, "layer"));
    _objc_msgSend(obj_16, "setMasksToBounds:", 1);
    _objc_release(obj_16);
    int64_t x2_11;
    int64_t x3_2;
    int64_t x4_1;
    int64_t x5_1;
    int128_t v0_8;
    int128_t v1_3;
    int128_t v2_4;
    int128_t v3_4;
    x2_11 = _objc_release(obj_15);
    v0_8 = 0x3fc999999999999a;
    v1_3 = 0x3fe3333333333333;
    v2_4 = 0x3fee666666666666;
    v3_4 = 0x3fd999999999999a;
    id obj_17 = _objc_retainAutorelease(_objc_retainAutoreleasedReturnValue(_objc_msgSend(
        clsRef_UIColor, "colorWithRed:green:blue:alpha:", x2_11, x3_2, x4_1, x5_1)));
    id x0_60 = _objc_msgSend(obj_17, "CGColor");
    id obj_18 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "panelView"));
    id obj_19 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_18, "layer"));
    _objc_msgSend(obj_19, "setBorderColor:", x0_60);
    _objc_release(obj_19);
    _objc_release(obj_18);
    _objc_release(obj_17);
    id obj_20 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "panelView"));
    id obj_21;
    int64_t x2_13;
    int128_t v0_9;
    obj_21 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_20, "layer"));
    v0_9 = 2.0;
    _objc_msgSend(obj_21, "setBorderWidth:", x2_13);
    _objc_release(obj_21);
    _objc_release(obj_20);
    id obj_22 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "view"));
    id obj_23 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "panelView"));
    _objc_msgSend(obj_22, "addSubview:");
    _objc_release(obj_23);
    int64_t x2_15;
    int128_t v0_10;
    int128_t v1_4;
    int128_t v2_5;
    int128_t v3_5;
    x2_15 = _objc_release(obj_22);
    v10 = 0x4040000000000000;
    v0_10 = 8.0;
    v1_4 = 10.0;
    v2_5 = v10;
    v3_5 = v10;
    id obj_24 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "makeCloseButton:", x2_15));
    id obj_25 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "panelView"));
    _objc_msgSend(obj_25, "addSubview:");
    _objc_release(obj_25);
    id x0_85;
    int128_t v1_5;
    int128_t v2_6;
    int128_t v3_6;
    x0_85 = _objc_alloc(clsRef_UIView);
    v1_5 = 12.0;
    v2_6 = 28.0;
    v3_6 = 28.0;
    id obj_26 = _objc_msgSend(x0_85, "initWithFrame:");
    id obj_27 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_CAGradientLayer, "layer"));
    _objc_msgSend(obj_26, "bounds");
    int64_t x2_17;
    int64_t x3_3;
    int64_t x4_2;
    int64_t x5_2;
    int128_t v0_12;
    int128_t v1_6;
    int128_t v2_7;
    int128_t v3_7;
    x2_17 = _objc_msgSend(obj_27, "setFrame:");
    v1_6 = 0.25;
    v3_7 = 1.0;
    v0_12 = 0x3feb333333333333;
    v2_7 = 0x3fe3333333333333;
    id obj_28 = _objc_retainAutorelease(_objc_retainAutoreleasedReturnValue(_objc_msgSend(
        clsRef_UIColor, "colorWithRed:green:blue:alpha:", x2_17, x3_3, x4_2, x5_2)));
    int64_t x0_93;
    int64_t x2_18;
    int64_t x3_4;
    int64_t x4_3;
    int64_t x5_3;
    int128_t v0_13;
    int128_t v1_7;
    int128_t v2_8;
    int128_t v3_8;
    x0_93 = _objc_msgSend(obj_28, "CGColor");
    int64_t var_c0 = x0_93;
    v0_13 = 0x3fc3333333333333;
    v1_7 = 0.5;
    v3_8 = 1.0;
    v2_8 = 0x3fee666666666666;
    id obj_29 = _objc_retainAutorelease(_objc_retainAutoreleasedReturnValue(_objc_msgSend(
        clsRef_UIColor, "colorWithRed:green:blue:alpha:", x2_18, x3_4, x4_3, x5_3)));
    int64_t var_b8 = _objc_msgSend(obj_29, "CGColor");
    id obj_30 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &var_c0, 2));
    _objc_msgSend(obj_27, "setColors:", obj_30);
    _objc_release(obj_30);
    _objc_release(obj_29);
    _objc_release(obj_28);
    int128_t v0_14;
    v0_14 = 14.0;
    _objc_msgSend(obj_27, "setCornerRadius:");
    id obj_31 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_26, "layer"));
    _objc_msgSend(obj_31, "addSublayer:", obj_27);
    _objc_release(obj_31);
    id obj_32;
    int128_t v0_15;
    obj_32 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_26, "layer"));
    v0_15 = 14.0;
    _objc_msgSend(obj_32, "setCornerRadius:");
    int64_t x2_22;
    int64_t x3_5;
    int64_t x4_4;
    int64_t x5_4;
    int128_t v0_16;
    int128_t v1_8;
    int128_t v2_9;
    int128_t v3_9;
    x2_22 = _objc_release(obj_32);
    v2_9 = 1.0;
    v3_9 = 1.0;
    v0_16 = 0x3fd999999999999a;
    v1_8 = 0x3fc999999999999a;
    id obj_33 = _objc_retainAutorelease(_objc_retainAutoreleasedReturnValue(_objc_msgSend(
        clsRef_UIColor, "colorWithRed:green:blue:alpha:", x2_22, x3_5, x4_4, x5_4)));
    int64_t x0_114 = _objc_msgSend(obj_33, "CGColor");
    id obj_34 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_26, "layer"));
    _objc_msgSend(obj_34, "setShadowColor:", x0_114);
    _objc_release(obj_34);
    _objc_release(obj_33);
    id obj_35;
    int64_t x2_24;
    int128_t v0_17;
    obj_35 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_26, "layer"));
    v0_17 = 6.0;
    _objc_msgSend(obj_35, "setShadowRadius:", x2_24);
    _objc_release(obj_35);
    id obj_36;
    int64_t x2_25;
    int128_t v0_18;
    obj_36 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_26, "layer"));
    v0_18 = 0x3f4ccccd;
    _objc_msgSend(obj_36, "setShadowOpacity:", x2_25);
    _objc_release(obj_36);
    width = _CGSizeZero->width;
    double height = _CGSizeZero->height;
    id obj_37;
    int64_t x2_26;
    int128_t v0_19;
    int128_t v1_9;
    obj_37 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_26, "layer"));
    v0_19 = width;
    v1_9 = height;
    _objc_msgSend(obj_37, "setShadowOffset:", x2_26);
    _objc_release(obj_37);
    id obj_38 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "panelView"));
    _objc_msgSend(obj_38, "addSubview:");
    _objc_release(obj_38);
    id x0_132;
    int128_t v0_20;
    int128_t v1_10;
    int128_t v2_10;
    int128_t v3_10;
    x0_132 = _objc_alloc(clsRef_UILabel);
    v0_20 = -0x3f9fc00000000000;
    v2_10 = temp0 + -130.0;
    v0_20 = 0x4054000000000000;
    v1_10 = 8.0;
    v3_10 = v10;
    id obj_39 = _objc_msgSend(x0_132, "initWithFrame:");
    int64_t x2_28;
    int128_t v0_21;
    x2_28 = _objc_msgSend(obj_39, "setText:", &cfstr_Masons_Menu);
    v0_21 = 22.0;
    id obj_40 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
        "boldSystemFontOfSize:", x2_28));
    _objc_msgSend(obj_39, "setFont:", obj_40);
    int64_t x2_30;
    int64_t x3_6;
    int64_t x4_5;
    int64_t x5_5;
    int128_t v0_22;
    int128_t v1_11;
    int128_t v2_11;
    int128_t v3_11;
    x2_30 = _objc_release(obj_40);
    v1_11 = 0x3feccccccccccccd;
    v2_11 = 1.0;
    v3_11 = 1.0;
    v0_22 = 0x3feb333333333333;
    id obj_41 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:", x2_30, x3_6, x4_5, x5_5));
    _objc_msgSend(obj_39, "setTextColor:", obj_41);
    _objc_release(obj_41);
    _objc_msgSend(obj_39, "setTextAlignment:", 1);
    id obj_42 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "panelView"));
    _objc_msgSend(obj_42, "addSubview:");
    int128_t v1_12;
    int128_t v2_12;
    int128_t v3_12;
    v1_12 = _objc_release(obj_42);
    v1_12 = 10.0;
    v2_12 = v10;
    v3_12 = v10;
    id obj_43 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "makeCloseButton:"));
    id obj_44 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "panelView"));
    _objc_msgSend(obj_44, "addSubview:");
    _objc_release(obj_44);
    id obj_45;
    int128_t v1_13;
    int128_t v2_13;
    int128_t v3_13;
    obj_45 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_CAGradientLayer, "layer"));
    v2_13 = temp0 + -28.0;
    v3_13 = 3.0;
    v1_13 = 0x4046000000000000;
    int64_t x2_34;
    int64_t x3_7;
    int64_t x4_6;
    int64_t x5_6;
    int128_t v0_25;
    int128_t v1_14;
    int128_t v2_14;
    int128_t v3_14;
    x2_34 = _objc_msgSend(obj_45, "setFrame:");
    v1_14 = 0.25;
    v3_14 = 1.0;
    v0_25 = 0x3feb333333333333;
    v2_14 = 0x3fe3333333333333;
    id obj_46 = _objc_retainAutorelease(_objc_retainAutoreleasedReturnValue(_objc_msgSend(
        clsRef_UIColor, "colorWithRed:green:blue:alpha:", x2_34, x3_7, x4_6, x5_6)));
    int64_t x0_155;
    int64_t x2_35;
    int64_t x3_8;
    int64_t x4_7;
    int64_t x5_7;
    int128_t v0_26;
    int128_t v1_15;
    int128_t v2_15;
    int128_t v3_15;
    x0_155 = _objc_msgSend(obj_46, "CGColor");
    int64_t var_e0 = x0_155;
    v3_15 = 1.0;
    v0_26 = 0x3fd999999999999a;
    v1_15 = 0x3fc999999999999a;
    v2_15 = 0x3fee666666666666;
    id obj_47 = _objc_retainAutorelease(_objc_retainAutoreleasedReturnValue(_objc_msgSend(
        clsRef_UIColor, "colorWithRed:green:blue:alpha:", x2_35, x3_8, x4_7, x5_7)));
    int64_t x0_159;
    int64_t x2_36;
    int64_t x3_9;
    int64_t x4_8;
    int64_t x5_8;
    int128_t v0_27;
    int128_t v2_16;
    int128_t v3_16;
    x0_159 = _objc_msgSend(obj_47, "CGColor");
    int64_t var_d8 = x0_159;
    v3_16 = 1.0;
    v0_27 = 0x3fb999999999999a;
    v2_16 = 0x3fee666666666666;
    id obj_48 = _objc_retainAutorelease(_objc_retainAutoreleasedReturnValue(_objc_msgSend(
        clsRef_UIColor, "colorWithRed:green:blue:alpha:", x2_36, x3_9, x4_8, x5_8)));
    int64_t x0_163;
    int64_t x2_37;
    int64_t x3_10;
    int64_t x4_9;
    int64_t x5_9;
    int128_t v0_28;
    int128_t v1_16;
    int128_t v2_17;
    int128_t v3_17;
    x0_163 = _objc_msgSend(obj_48, "CGColor");
    int64_t var_d0 = x0_163;
    v0_28 = 1.0;
    v3_17 = 1.0;
    v1_16 = 0x3feb333333333333;
    v2_17 = 0x3fd3333333333333;
    id obj_49 = _objc_retainAutorelease(_objc_retainAutoreleasedReturnValue(_objc_msgSend(
        clsRef_UIColor, "colorWithRed:green:blue:alpha:", x2_37, x3_10, x4_9, x5_9)));
    int64_t var_c8 = _objc_msgSend(obj_49, "CGColor");
    id obj_50 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:"));
    _objc_msgSend(obj_45, "setColors:");
    _objc_release(obj_50);
    _objc_release(obj_49);
    _objc_release(obj_48);
    _objc_release(obj_47);
    int64_t x2_39;
    int128_t v0_29;
    int128_t v1_17;
    x2_39 = _objc_release(obj_46);
    v0_29 = 0.0;
    v1_17 = 0.5;
    int64_t x2_40;
    int128_t v0_30;
    int128_t v1_18;
    x2_40 = _objc_msgSend(obj_45, "setStartPoint:", x2_39);
    v0_30 = 1.0;
    v1_18 = 0.5;
    _objc_msgSend(obj_45, "setEndPoint:", x2_40);
    int128_t v0_31;
    v0_31 = 1.5;
    _objc_msgSend(obj_45, "setCornerRadius:");
    id obj_51 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "panelView"));
    id obj_52 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_51, "layer"));
    _objc_msgSend(obj_52, "addSublayer:");
    _objc_release(obj_52);
    _objc_release(obj_51);
    uint32_t __upper_bound = vcvtd_u32_f64(temp0);
    uint32_t __upper_bound_1 = vcvtd_u32_f64(temp0_1);
    int32_t i_1 = 0x14;
    int64_t x3_12;
    int128_t v2_20;
    int128_t v3_19;
    double v13;
    double v14;
    int32_t i;
    
    do
    {
        id x0_185 = _objc_alloc(clsRef_UIView);
        width = _arc4random_uniform(__upper_bound);
        v13 = _arc4random_uniform(__upper_bound_1);
        v14 = _arc4random_uniform(3) + 1;
        uint32_t x0_191;
        int128_t v0_33;
        int128_t v1_19;
        int128_t v2_18;
        int128_t v3_18;
        x0_191 = _arc4random_uniform(3);
        v3_18 = x0_191 + 1;
        v0_33 = width;
        v1_19 = v13;
        v2_18 = v14;
        id obj_53 = _objc_msgSend(x0_185, "initWithFrame:");
        struct objc_class_t* clsRef_UIColor_1 = clsRef_UIColor;
        uint32_t x0_193;
        double v0_34;
        x0_193 = _arc4random_uniform(0x1e);
        v0_34 = x0_193;
        v0_34 = v0_34 / 0x42c80000;
        id obj_54 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor_1, 
            "colorWithWhite:alpha:"));
        _objc_msgSend(obj_53, "setBackgroundColor:");
        _objc_release(obj_54);
        width = _objc_msgSend(obj_53, "frame") * v15;
        id obj_55;
        int128_t v0_35;
        obj_55 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_53, "layer"));
        v0_35 = width;
        _objc_msgSend(obj_55, "setCornerRadius:");
        _objc_release(obj_55);
        id obj_56 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "panelView"));
        _objc_msgSend(obj_56, "insertSubview:atIndex:", obj_53, 0);
        _objc_release(obj_56);
        x3_12 = _objc_release(obj_53);
        i = i_1;
        i_1 -= 1;
    } while (i != 1);
    v10 = (temp0 + -0x3fba000000000000) / 5.0;
    v13 = 0x4049000000000000;
    v3_19 = 30.0;
    v2_20 = v10;
    id obj_57 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, 
        "tabButtonWithTitle:frame:", &cfstr_Items, x3_12));
    _objc_msgSend(self, "setItemsTabBtn:", obj_57);
    int64_t x3_13;
    int128_t v1_22;
    int128_t v2_21;
    int128_t v3_20;
    x3_13 = _objc_release(obj_57);
    v14 = v10 + 4.0;
    v3_20 = 30.0;
    v1_22 = v13;
    v2_21 = v10;
    id obj_58 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, 
        "tabButtonWithTitle:frame:", &cfstr_Mobs, x3_13));
    _objc_msgSend(self, "setMonstersTabBtn:", obj_58);
    int64_t x3_14;
    int128_t v0_38;
    int128_t v1_23;
    int128_t v2_22;
    int128_t v3_21;
    x3_14 = _objc_release(obj_58);
    width = v14 + v14 + 14.0;
    v3_21 = 30.0;
    v0_38 = width;
    v1_23 = v13;
    v2_22 = v10;
    id obj_59 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, 
        "tabButtonWithTitle:frame:", &cfstr_Exp, x3_14));
    _objc_msgSend(self, "setExperimentTabBtn:", obj_59);
    int64_t x3_15;
    int128_t v0_39;
    int128_t v1_24;
    int128_t v2_23;
    int128_t v3_22;
    x3_15 = _objc_release(obj_59);
    width = v14 + width;
    v3_22 = 30.0;
    v0_39 = width;
    v1_24 = v13;
    v2_23 = v10;
    id obj_60 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, 
        "tabButtonWithTitle:frame:", &cfstr_Settings, x3_15));
    _objc_msgSend(self, "setSettingsTabBtn:", obj_60);
    int64_t x3_16;
    int128_t v0_40;
    int128_t v1_25;
    int128_t v2_24;
    int128_t v3_23;
    x3_16 = _objc_release(obj_60);
    v0_40 = v14 + width;
    v3_23 = 30.0;
    v1_25 = v13;
    v2_24 = v10;
    id obj_61 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, 
        "tabButtonWithTitle:frame:", &cfstr_Admin, x3_16));
    id obj_62 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "itemsTabBtn"));
    _objc_msgSend(obj_62, "addTarget:action:forControlEvents:");
    _objc_release(obj_62);
    id obj_63 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "monstersTabBtn"));
    _objc_msgSend(obj_63, "addTarget:action:forControlEvents:");
    _objc_release(obj_63);
    id obj_64 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "experimentTabBtn"));
    _objc_msgSend(obj_64, "addTarget:action:forControlEvents:");
    _objc_release(obj_64);
    id obj_65 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "settingsTabBtn"));
    _objc_msgSend(obj_65, "addTarget:action:forControlEvents:");
    _objc_release(obj_65);
    _objc_msgSend(obj_61, "addTarget:action:forControlEvents:");
    _objc_msgSend(obj_61, "setTag:", 0x37a);
    id obj_66 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "panelView"));
    id obj_67 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "itemsTabBtn"));
    _objc_msgSend(obj_66, "addSubview:");
    _objc_release(obj_67);
    _objc_release(obj_66);
    id obj_68 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "panelView"));
    id obj_69 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "monstersTabBtn"));
    _objc_msgSend(obj_68, "addSubview:");
    _objc_release(obj_69);
    _objc_release(obj_68);
    id obj_70 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "panelView"));
    id obj_71 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "experimentTabBtn"));
    _objc_msgSend(obj_70, "addSubview:");
    _objc_release(obj_71);
    _objc_release(obj_70);
    id obj_72 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "panelView"));
    id obj_73 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "settingsTabBtn"));
    _objc_msgSend(obj_72, "addSubview:");
    _objc_release(obj_73);
    _objc_release(obj_72);
    id obj_74 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "panelView"));
    _objc_msgSend(obj_74, "addSubview:");
    _objc_release(obj_74);
    v10 = temp0_1 + -94.0;
    id x0_270;
    int128_t v0_41;
    int128_t v1_26;
    int128_t v2_25;
    int128_t v3_24;
    x0_270 = _objc_alloc(clsRef_UIScrollView);
    v0_41 = 0.0;
    v1_26 = 0x4057800000000000;
    v2_25 = temp0;
    v3_24 = v10;
    int64_t obj_75 = _objc_msgSend(x0_270, "initWithFrame:");
    _objc_msgSend(self, "setSpawnerScroll:", obj_75);
    _objc_release(obj_75);
    id obj_76 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnerScroll"));
    _objc_msgSend(obj_76, "setShowsVerticalScrollIndicator:", 1);
    _objc_release(obj_76);
    id obj_77 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "panelView"));
    id obj_78 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnerScroll"));
    _objc_msgSend(obj_77, "addSubview:");
    _objc_release(obj_78);
    _objc_release(obj_77);
    id x0_284;
    int128_t v0_42;
    int128_t v1_27;
    int128_t v2_26;
    int128_t v3_25;
    x0_284 = _objc_alloc(clsRef_UIView);
    v14 = 0x4089000000000000;
    v0_42 = 0.0;
    v1_27 = 0.0;
    v2_26 = temp0;
    v3_25 = v14;
    int64_t obj_79 = _objc_msgSend(x0_284, "initWithFrame:");
    _objc_msgSend(self, "setSpawnerInner:", obj_79);
    _objc_release(obj_79);
    id obj_80 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnerScroll"));
    id obj_81 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnerInner"));
    _objc_msgSend(obj_80, "addSubview:");
    _objc_release(obj_81);
    _objc_release(obj_80);
    _objc_msgSend(self, "buildSpawnerContent");
    id x0_296;
    int128_t v0_43;
    int128_t v1_28;
    int128_t v2_27;
    int128_t v3_26;
    x0_296 = _objc_alloc(clsRef_UIView);
    v0_43 = 0.0;
    v1_28 = 0x4057800000000000;
    v2_27 = temp0;
    v3_26 = v10;
    int64_t obj_82 = _objc_msgSend(x0_296, "initWithFrame:");
    _objc_msgSend(self, "setSettingsContent:", obj_82);
    _objc_release(obj_82);
    id obj_83 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "settingsContent"));
    _objc_msgSend(obj_83, "setHidden:", 1);
    _objc_release(obj_83);
    id obj_84 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "panelView"));
    id obj_85 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "settingsContent"));
    _objc_msgSend(obj_84, "addSubview:");
    _objc_release(obj_85);
    _objc_release(obj_84);
    _objc_msgSend(self, "buildSettingsContent");
    id x0_311;
    int128_t v0_44;
    int128_t v1_29;
    int128_t v2_28;
    int128_t v3_27;
    x0_311 = _objc_alloc(clsRef_UIScrollView);
    v0_44 = 0.0;
    v1_29 = 0x4057800000000000;
    v2_28 = temp0;
    v3_27 = v10;
    int64_t obj_86 = _objc_msgSend(x0_311, "initWithFrame:");
    _objc_msgSend(self, "setExperimentScroll:", obj_86);
    _objc_release(obj_86);
    id obj_87 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "experimentScroll"));
    _objc_msgSend(obj_87, "setShowsVerticalScrollIndicator:", 1);
    _objc_release(obj_87);
    id obj_88 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "experimentScroll"));
    _objc_msgSend(obj_88, "setHidden:", 1);
    _objc_release(obj_88);
    id obj_89 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "panelView"));
    id obj_90 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "experimentScroll"));
    _objc_msgSend(obj_89, "addSubview:");
    _objc_release(obj_90);
    _objc_release(obj_89);
    id x0_328;
    int128_t v0_45;
    int128_t v1_30;
    int128_t v2_29;
    int128_t v3_28;
    x0_328 = _objc_alloc(clsRef_UIView);
    v0_45 = 0.0;
    v1_30 = 0.0;
    v2_29 = temp0;
    v3_28 = v14;
    int64_t obj_91 = _objc_msgSend(x0_328, "initWithFrame:");
    _objc_msgSend(self, "setExperimentInner:", obj_91);
    _objc_release(obj_91);
    id obj_92 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "experimentScroll"));
    id obj_93 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "experimentInner"));
    _objc_msgSend(obj_92, "addSubview:");
    _objc_release(obj_93);
    _objc_release(obj_92);
    _objc_msgSend(self, "buildExperimentContent");
    id x0_340;
    int128_t v0_46;
    int128_t v1_31;
    int128_t v2_30;
    int128_t v3_29;
    x0_340 = _objc_alloc(clsRef_UIScrollView);
    v0_46 = 0.0;
    v1_31 = 0x4057800000000000;
    v2_30 = temp0;
    v3_29 = v10;
    int64_t obj_94 = _objc_msgSend(x0_340, "initWithFrame:");
    _objc_msgSend(self, "setAdminScroll:", obj_94);
    _objc_release(obj_94);
    id obj_95 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminScroll"));
    _objc_msgSend(obj_95, "setShowsVerticalScrollIndicator:", 1);
    _objc_release(obj_95);
    id obj_96 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminScroll"));
    _objc_msgSend(obj_96, "setHidden:", 1);
    _objc_release(obj_96);
    id obj_97 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "panelView"));
    id obj_98 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminScroll"));
    _objc_msgSend(obj_97, "addSubview:");
    _objc_release(obj_98);
    _objc_release(obj_97);
    id x0_357;
    int128_t v0_47;
    int128_t v1_32;
    int128_t v2_31;
    int128_t v3_30;
    x0_357 = _objc_alloc(clsRef_UIView);
    v3_30 = 0x4082c00000000000;
    v0_47 = 0.0;
    v1_32 = 0.0;
    v2_31 = temp0;
    int64_t obj_99 = _objc_msgSend(x0_357, "initWithFrame:");
    _objc_msgSend(self, "setAdminInner:", obj_99);
    _objc_release(obj_99);
    id obj_100 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminScroll"));
    id obj_101 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminInner"));
    _objc_msgSend(obj_100, "addSubview:");
    _objc_release(obj_101);
    _objc_release(obj_100);
    _objc_msgSend(self, "buildAdminContent");
    _objc_msgSend(self, "setActiveTab:", 0);
    _objc_msgSend(self, "updateTabAppearance");
    _objc_msgSend(self, "updateCategoryAppearance");
    _objc_msgSend(self, "updateItemCount");
    _CGAffineTransformMakeScale(0x3feb333333333333, 0x3feb333333333333);
    id obj_102;
    int128_t v0_49;
    int128_t v1_34;
    obj_102 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "panelView"));
    int128_t var_120;
    int128_t var_150 = var_120;
    int128_t var_110;
    int128_t var_140 = var_110;
    int128_t var_100;
    int128_t var_130 = var_100;
    _objc_msgSend(obj_102, "setTransform:", &var_150);
    _objc_release(obj_102);
    id obj_103;
    int64_t x2_73;
    int128_t v0_50;
    obj_103 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "panelView"));
    v0_50 = 0.0;
    _objc_msgSend(obj_103, "setAlpha:", x2_73);
    int64_t x5_10;
    int64_t x6;
    int64_t x7;
    int128_t v0_51;
    int128_t v1_35;
    int128_t v2_32;
    int128_t v3_31;
    x5_10 = _objc_release(obj_103);
    struct objc_class_t* clsRef_UIView_1 = clsRef_UIView;
    void* (* const var_178)[0x20] = __NSConcreteStackBlock;
    v0_51 = 0xc2000000;
    int64_t var_170 = 0xc2000000;
    int64_t (* var_168)(void* arg1) = sub_406e48;
    void* const var_160 = &data_43c090;
    struct ACPanelController* self_1 = self;
    v1_35 = 0.0;
    v3_31 = 0.5;
    v0_51 = 0x3fd3333333333333;
    v2_32 = 0x3fe999999999999a;
    void var_230;
    _objc_msgSend(clsRef_UIView_1, 
        "animateWithDuration:delay:usingSpringWithDamping:initialSpringVelocity:options:animations:"
    "completion:", 
        0, &var_178, 0, x5_10, x6, x7, var_230);
    _objc_release(obj_61);
    _objc_release(obj_45);
    _objc_release(obj_43);
    _objc_release(obj_39);
    _objc_release(obj_27);
    _objc_release(obj_26);
    _objc_release(obj_24);
    _objc_release(obj_2);
    
    if (*___stack_chk_guard == x8)
        return;
    
    ___stack_chk_fail();
    /* no return */
}

int64_t sub_406e48(void* arg1)
{
    id obj;
    int128_t v0;
    int128_t v1;
    obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(*(arg1 + 0x20), "panelView"));
    v1 = _CGAffineTransformIdentity->c;
    int128_t var_60 = _CGAffineTransformIdentity->a;
    int128_t var_50 = v1;
    int128_t var_40 = _CGAffineTransformIdentity->tx;
    _objc_msgSend(obj, "setTransform:", &var_60);
    _objc_release(obj);
    id obj_1;
    int64_t x2_1;
    int128_t v0_1;
    obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(*(arg1 + 0x20), "panelView"));
    v0_1 = 1.0;
    _objc_msgSend(obj_1, "setAlpha:", x2_1);
    return _objc_release(obj_1);
}

int64_t sub_406ef4(int64_t arg1, void* arg2)
{
    /* tailcall */
    return _objc_retain(*(arg2 + 0x20));
}

int64_t sub_406efc(void* arg1)
{
    /* tailcall */
    return _objc_release(*(arg1 + 0x20));
}

void -[ACPanelController buildSpawnerContent](struct ACPanelController* self, SEL sel)
{
    double v15;
    double var_a0 = v15;
    double v14;
    double var_98 = v14;
    double v13;
    double var_90 = v13;
    double v12;
    double var_88 = v12;
    double v11;
    double var_80 = v11;
    double v10;
    double var_78 = v10;
    double v9;
    double var_70 = v9;
    int64_t x8 = *___stack_chk_guard;
    id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnerInner"));
    double v2 = _objc_msgSend(obj_2, "bounds");
    _objc_release(obj_2);
    id x0_3;
    int64_t x2;
    int128_t v0;
    int128_t v1;
    int128_t v2_1;
    int128_t v3;
    x0_3 = _objc_alloc(clsRef_UILabel);
    v2_1 = 0x4054000000000000;
    double v8 = 14.0;
    v0 = 14.0;
    v1 = 0.0;
    v3 = 20.0;
    id obj_3 = _objc_msgSend(x0_3, "initWithFrame:", x2);
    int64_t x2_1;
    int64_t x3;
    int128_t v0_1;
    x2_1 = _objc_msgSend(obj_3, "setText:", &cfstr_Category);
    double v1_1 = *_UIFontWeightMedium;
    v0_1 = 12.0;
    id obj_4 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
        "systemFontOfSize:weight:", x2_1, x3));
    _objc_msgSend(obj_3, "setFont:", obj_4);
    int64_t x2_3;
    int64_t x3_1;
    int64_t x4;
    int64_t x5;
    int128_t v3_1;
    x2_3 = _objc_release(obj_4);
    v3_1 = 1.0;
    id obj_5 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:", x2_3, x3_1, x4, x5));
    _objc_msgSend(obj_3, "setTextColor:", obj_5);
    _objc_release(obj_5);
    _objc_msgSend(obj_3, "setTag:", 0x320);
    id obj_6 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnerInner"));
    _objc_msgSend(obj_6, "addSubview:", obj_3);
    _objc_release(obj_6);
    struct __NSConstantString* const var_d0 = &cfstr_All_Items;
    struct __NSConstantString* const var_c8 = &cfstr_Fishing_Rods;
    struct __NSConstantString* const var_c0 = &cfstr_Fish;
    struct __NSConstantString* const var_b8 = &cfstr_Baits;
    id obj_340 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &var_d0, 4));
    id obj_341 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSMutableArray, "array"));
    id obj_1 = obj_340;
    id obj = obj_341;
    
    if (_objc_msgSend(obj_340, "count") >= 1)
    {
        int64_t x21_1 = 0;
        v9 = *_UIFontWeightSemibold;
        int64_t x0_62;
        
        do
        {
            id obj_7 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_340, 
                "objectAtIndexedSubscript:", x21_1));
            double temp0_1 = vfma_f64(20.0, _objc_msgSend(obj_7, "length"), 8.0);
            _objc_release(obj_7);
            id obj_8;
            int128_t v0_3;
            int128_t v1_3;
            int128_t v2_2;
            int128_t v3_2;
            obj_8 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, 
                "buttonWithType:"));
            v1_3 = 22.0;
            v3_2 = 30.0;
            v0_3 = v8;
            v2_2 = temp0_1;
            _objc_msgSend(obj_8, "setFrame:");
            id obj_9 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_340, 
                "objectAtIndexedSubscript:", x21_1));
            _objc_msgSend(obj_8, "setTitle:forState:");
            int128_t v0_4;
            int128_t v1_4;
            v0_4 = _objc_release(obj_9);
            v0_4 = 11.0;
            v1_4 = v9;
            id obj_10 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
                "systemFontOfSize:weight:"));
            id obj_11 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_8, "titleLabel"));
            _objc_msgSend(obj_11, "setFont:");
            _objc_release(obj_11);
            _objc_release(obj_10);
            id obj_12;
            int128_t v0_5;
            obj_12 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_8, "layer"));
            v0_5 = 15.0;
            _objc_msgSend(obj_12, "setCornerRadius:");
            _objc_release(obj_12);
            id obj_13;
            int128_t v0_6;
            obj_13 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_8, "layer"));
            v0_6 = 1.0;
            _objc_msgSend(obj_13, "setBorderWidth:");
            int128_t v0_7;
            int128_t v1_5;
            int128_t v2_3;
            int128_t v3_3;
            v0_7 = _objc_release(obj_13);
            v3_3 = 0.5;
            v0_7 = 0x3fc999999999999a;
            v1_5 = 0x3fe3333333333333;
            v2_3 = 0x3fee666666666666;
            id obj_14 = _objc_retainAutorelease(_objc_retainAutoreleasedReturnValue(_objc_msgSend(
                clsRef_UIColor, "colorWithRed:green:blue:alpha:")));
            _objc_msgSend(obj_14, "CGColor");
            id obj_15 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_8, "layer"));
            obj_340 = obj_1;
            _objc_msgSend(obj_15, "setBorderColor:");
            _objc_release(obj_15);
            _objc_release(obj_14);
            _objc_msgSend(obj_8, "setTag:");
            _objc_msgSend(obj_8, "addTarget:action:forControlEvents:", self, "categoryTapped:", 
                0x40);
            id obj_16 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnerInner"));
            _objc_msgSend(obj_16, "addSubview:");
            obj_341 = obj;
            _objc_release(obj_16);
            _objc_msgSend(obj_341, "addObject:", obj_8);
            v8 = v8 + temp0_1 + 6.0;
            _objc_release(obj_8);
            x0_62 = _objc_msgSend(obj_340, "count");
            x21_1 += 1;
        } while (x21_1 < x0_62);
    }
    
    id obj_17 = _objc_msgSend(obj_341, "copy");
    _objc_msgSend(self, "setCategoryButtons:", obj_17);
    _objc_release(obj_17);
    id x0_67;
    int128_t v2_4;
    int128_t v3_4;
    x0_67 = _objc_alloc(clsRef_UIView);
    v10 = v2 + -28.0;
    v3_4 = 26.0;
    v2_4 = v10;
    id obj_18 = _objc_msgSend(x0_67, "initWithFrame:");
    _objc_msgSend(obj_18, "setTag:");
    id x0_69;
    int128_t v0_10;
    int128_t v1_7;
    int128_t v2_5;
    int128_t v3_5;
    x0_69 = _objc_alloc(clsRef_UILabel);
    v8 = 0x4064000000000000;
    v0_10 = 0.0;
    v1_7 = 0.0;
    v3_5 = 26.0;
    v2_5 = v8;
    id obj_19 = _objc_msgSend(x0_69, "initWithFrame:");
    int64_t x2_20;
    int128_t v0_11;
    x2_20 = _objc_msgSend(obj_19, "setText:");
    v0_11 = 16.0;
    id obj_20 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
        "boldSystemFontOfSize:", x2_20));
    _objc_msgSend(obj_19, "setFont:");
    int128_t v1_8;
    int128_t v3_6;
    v1_8 = _objc_release(obj_20);
    v3_6 = 1.0;
    v1_8 = 0x3fc999999999999a;
    id obj_21 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_19, "setTextColor:");
    _objc_release(obj_21);
    _objc_msgSend(obj_19, "setTag:");
    _objc_msgSend(obj_18, "addSubview:");
    id x0_81;
    int128_t v1_9;
    int128_t v2_6;
    int128_t v3_7;
    x0_81 = _objc_alloc(clsRef_UILabel);
    v2_6 = v10 + -0x3f9c000000000000;
    v1_9 = 0.0;
    v3_7 = 26.0;
    int64_t obj_22 = _objc_msgSend(x0_81, "initWithFrame:");
    _objc_msgSend(self, "setItemCountLabel:", obj_22);
    int64_t x2_26;
    int128_t v0_13;
    x2_26 = _objc_release(obj_22);
    v0_13 = 12.0;
    id obj_23 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
        "systemFontOfSize:", x2_26));
    id obj_24 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "itemCountLabel"));
    _objc_msgSend(obj_24, "setFont:");
    _objc_release(obj_24);
    int128_t v0_14;
    int128_t v1_10;
    int128_t v2_7;
    int128_t v3_8;
    v0_14 = _objc_release(obj_23);
    v3_8 = 1.0;
    v0_14 = 0x3fdccccccccccccd;
    v1_10 = 0x3fe199999999999a;
    v2_7 = 0x3fe6666666666666;
    id obj_25 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    id obj_26 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "itemCountLabel"));
    _objc_msgSend(obj_26, "setTextColor:");
    _objc_release(obj_26);
    _objc_release(obj_25);
    id obj_27 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "itemCountLabel"));
    _objc_msgSend(obj_27, "setTextAlignment:", 2);
    _objc_release(obj_27);
    id obj_28 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "itemCountLabel"));
    _objc_msgSend(obj_18, "addSubview:");
    _objc_release(obj_28);
    id obj_29 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnerInner"));
    _objc_msgSend(obj_29, "addSubview:");
    _objc_release(obj_29);
    id x0_107;
    int128_t v0_15;
    int128_t v1_11;
    int128_t v2_8;
    int128_t v3_9;
    x0_107 = _objc_alloc(clsRef_UITextField);
    v1_11 = 0x4057000000000000;
    v15 = 0x4042000000000000;
    v0_15 = 14.0;
    v2_8 = v10;
    v3_9 = v15;
    int64_t obj_30 = _objc_msgSend(x0_107, "initWithFrame:");
    _objc_msgSend(self, "setSearchField:", obj_30);
    int128_t v0_16;
    int128_t v1_12;
    int128_t v2_9;
    int128_t v3_10;
    v0_16 = _objc_release(obj_30);
    v2_9 = 0x3fbeb851eb851eb8;
    v3_10 = 1.0;
    v0_16 = 0x3fa47ae147ae147b;
    v1_12 = 0x3fa47ae147ae147b;
    id obj_31 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    id obj_32 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "searchField"));
    _objc_msgSend(obj_32, "setBackgroundColor:", obj_31);
    _objc_release(obj_32);
    _objc_release(obj_31);
    id obj_33 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "searchField"));
    id obj_34;
    int64_t x2_33;
    int128_t v0_17;
    obj_34 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_33, "layer"));
    v12 = 10.0;
    v0_17 = 10.0;
    _objc_msgSend(obj_34, "setCornerRadius:", x2_33);
    _objc_release(obj_34);
    _objc_release(obj_33);
    id obj_35 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "searchField"));
    id obj_36;
    int64_t x2_34;
    int128_t v0_18;
    obj_36 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_35, "layer"));
    v0_18 = 1.0;
    _objc_msgSend(obj_36, "setBorderWidth:", x2_34);
    _objc_release(obj_36);
    int64_t x2_35;
    int64_t x3_3;
    int128_t v0_19;
    int128_t v1_13;
    x2_35 = _objc_release(obj_35);
    v1_13 = 1.0;
    v0_19 = 0x3fc999999999999a;
    id obj_37 = _objc_retainAutorelease(_objc_retainAutoreleasedReturnValue(_objc_msgSend(
        clsRef_UIColor, "colorWithWhite:alpha:", x2_35, x3_3)));
    id x0_129 = _objc_msgSend(obj_37, "CGColor");
    id obj_38 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "searchField"));
    id obj_39 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_38, "layer"));
    _objc_msgSend(obj_39, "setBorderColor:", x0_129);
    _objc_release(obj_39);
    _objc_release(obj_38);
    int128_t v2_10;
    int128_t v3_11;
    v2_10 = _objc_release(obj_37);
    v2_10 = 1.0;
    v3_11 = 1.0;
    id obj_40 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    id obj_41 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "searchField"));
    _objc_msgSend(obj_41, "setTextColor:");
    _objc_release(obj_41);
    _objc_release(obj_40);
    int128_t v0_20;
    v0_20 = 13.0;
    id obj_42 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "systemFontOfSize:"));
    id obj_43 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "searchField"));
    _objc_msgSend(obj_43, "setFont:");
    _objc_release(obj_43);
    _objc_release(obj_42);
    id x0_149;
    int128_t v0_21;
    int128_t v1_14;
    int128_t v2_11;
    int128_t v3_12;
    x0_149 = _objc_alloc(clsRef_NSAttributedString);
    struct objc_class* var_e0 = *_NSForegroundColorAttributeName;
    v3_12 = 1.0;
    v0_21 = 0x3fdccccccccccccd;
    v1_14 = 0x3fe199999999999a;
    v2_11 = 0x3fe6666666666666;
    id obj_44 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    id obj_339 = obj_44;
    id obj_45 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSDictionary, 
        "dictionaryWithObjects:forKeys:count:", &obj_339, &var_e0, 1));
    id obj_46 = _objc_msgSend(x0_149, "initWithString:attributes:", &cfstr_Search_items..., obj_45);
    id obj_47 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "searchField"));
    _objc_msgSend(obj_47, "setAttributedPlaceholder:", obj_46);
    _objc_release(obj_47);
    _objc_release(obj_46);
    _objc_release(obj_45);
    _objc_release(obj_44);
    id x0_162;
    int128_t v0_22;
    int128_t v1_15;
    int128_t v2_12;
    int128_t v3_13;
    x0_162 = _objc_alloc(clsRef_UIView);
    v0_22 = 0.0;
    v1_15 = 0.0;
    v2_12 = 12.0;
    v3_13 = v15;
    int64_t obj_48 = _objc_msgSend(x0_162, "initWithFrame:");
    id obj_49 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "searchField"));
    _objc_msgSend(obj_49, "setLeftView:", obj_48);
    _objc_release(obj_49);
    _objc_release(obj_48);
    id obj_50 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "searchField"));
    _objc_msgSend(obj_50, "setLeftViewMode:", 3);
    _objc_release(obj_50);
    id obj_51 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "searchField"));
    _objc_msgSend(obj_51, "setReturnKeyType:", 9);
    _objc_release(obj_51);
    id obj_52 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "searchField"));
    _objc_msgSend(obj_52, "setDelegate:", self);
    _objc_release(obj_52);
    id obj_53 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "searchField"));
    _objc_msgSend(obj_53, "addTarget:action:forControlEvents:", self, "searchChanged", 0x20000);
    _objc_release(obj_53);
    id obj_54 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnerInner"));
    id obj_55 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "searchField"));
    _objc_msgSend(obj_54, "addSubview:");
    _objc_release(obj_55);
    _objc_release(obj_54);
    id x0_187;
    int64_t x3_6;
    int128_t v0_23;
    int128_t v1_16;
    int128_t v2_13;
    int128_t v3_14;
    x0_187 = _objc_alloc(clsRef_UITableView);
    v1_16 = 0x4061000000000000;
    v0_23 = 14.0;
    v2_13 = v10;
    v3_14 = v8;
    id obj_56 = _objc_msgSend(x0_187, "initWithFrame:style:", 0, x3_6);
    _objc_msgSend(self, "setTableView:", obj_56);
    int128_t v0_24;
    int128_t v1_17;
    int128_t v2_14;
    int128_t v3_15;
    v0_24 = _objc_release(obj_56);
    v3_15 = 1.0;
    v0_24 = 0x3fa999999999999a;
    v1_17 = 0x3fa47ae147ae147b;
    v2_14 = 0x3fc1eb851eb851ec;
    id obj_57 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    id obj_58 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "tableView"));
    _objc_msgSend(obj_58, "setBackgroundColor:");
    _objc_release(obj_58);
    _objc_release(obj_57);
    id obj_59 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "tableView"));
    id obj_60;
    int128_t v0_25;
    obj_60 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_59, "layer"));
    v0_25 = 12.0;
    _objc_msgSend(obj_60, "setCornerRadius:");
    _objc_release(obj_60);
    _objc_release(obj_59);
    id obj_61 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "tableView"));
    _objc_msgSend(obj_61, "setSeparatorStyle:", 0);
    _objc_release(obj_61);
    id obj_62 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "tableView"));
    _objc_msgSend(obj_62, "setDelegate:", self);
    _objc_release(obj_62);
    id obj_63 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "tableView"));
    _objc_msgSend(obj_63, "setDataSource:", self);
    _objc_release(obj_63);
    id obj_64 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "tableView"));
    _objc_msgSend(obj_64, "setShowsVerticalScrollIndicator:", 0);
    _objc_release(obj_64);
    id obj_65 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnerInner"));
    id obj_66 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "tableView"));
    _objc_msgSend(obj_65, "addSubview:");
    _objc_release(obj_66);
    _objc_release(obj_65);
    id x0_221;
    int128_t v0_26;
    int128_t v1_18;
    int128_t v2_15;
    int128_t v3_16;
    x0_221 = _objc_alloc(clsRef_UIView);
    v1_18 = 0x4073200000000000;
    v13 = 0x4046000000000000;
    v0_26 = 14.0;
    v2_15 = v10;
    v3_16 = v13;
    id obj_67;
    int128_t v0_27;
    int128_t v1_19;
    int128_t v2_16;
    int128_t v3_17;
    obj_67 = _objc_msgSend(x0_221, "initWithFrame:");
    v3_17 = 1.0;
    v0_27 = 0x3fa999999999999a;
    v1_19 = 0x3fa47ae147ae147b;
    v2_16 = 0x3fc1eb851eb851ec;
    id obj_68 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_67, "setBackgroundColor:");
    _objc_release(obj_68);
    id obj_69;
    int128_t v0_28;
    obj_69 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_67, "layer"));
    v0_28 = 12.0;
    _objc_msgSend(obj_69, "setCornerRadius:");
    _objc_release(obj_69);
    id obj_70;
    int128_t v0_29;
    obj_70 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_67, "layer"));
    v0_29 = 1.0;
    _objc_msgSend(obj_70, "setBorderWidth:");
    _objc_release(obj_70);
    int128_t v1_20;
    v1_20 = 1.0;
    id obj_71 = _objc_retainAutorelease(_objc_retainAutoreleasedReturnValue(_objc_msgSend(
        clsRef_UIColor, "colorWithWhite:alpha:")));
    _objc_msgSend(obj_71, "CGColor");
    id obj_72 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_67, "layer"));
    _objc_msgSend(obj_72, "setBorderColor:");
    _objc_release(obj_72);
    _objc_release(obj_71);
    id x0_241;
    int128_t v0_30;
    int128_t v1_21;
    int128_t v3_18;
    x0_241 = _objc_alloc(clsRef_UILabel);
    double v2_17 = 0x4054000000000000;
    v0_30 = 14.0;
    v1_21 = 0.0;
    v3_18 = v13;
    id obj_73 = _objc_msgSend(x0_241, "initWithFrame:");
    int128_t v0_31;
    int128_t v1_22;
    v0_31 = _objc_msgSend(obj_73, "setText:");
    v0_31 = 14.0;
    v1_22 = v1_1;
    id obj_74 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
        "systemFontOfSize:weight:"));
    _objc_msgSend(obj_73, "setFont:");
    int128_t v0_32;
    int128_t v1_23;
    int128_t v2_18;
    int128_t v3_19;
    v0_32 = _objc_release(obj_74);
    v2_18 = 1.0;
    v3_19 = 1.0;
    v0_32 = 0x3feb333333333333;
    v1_23 = 0x3feccccccccccccd;
    id obj_75 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_73, "setTextColor:");
    _objc_release(obj_75);
    _objc_msgSend(obj_67, "addSubview:");
    id x0_252;
    int128_t v0_33;
    int128_t v1_24;
    int128_t v2_19;
    int128_t v3_20;
    x0_252 = _objc_alloc(clsRef_UILabel);
    v0_33 = 0x4057800000000000;
    v2_19 = 0x404e000000000000;
    v1_24 = 0.0;
    v3_20 = v13;
    int64_t obj_76 = _objc_msgSend(x0_252, "initWithFrame:");
    _objc_msgSend(self, "setQuantityLabel:", obj_76);
    _objc_release(obj_76);
    struct objc_class_t* clsRef_NSString_1 = clsRef_NSString;
    id var_480 = _objc_msgSend(self, "spawnQuantity");
    id obj_77 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString_1, 
        "stringWithFormat:", &cfstr_%ld));
    id obj_78 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "quantityLabel"));
    _objc_msgSend(obj_78, "setText:");
    _objc_release(obj_78);
    _objc_release(obj_77);
    int128_t v0_34;
    v0_34 = 18.0;
    id obj_79 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    id obj_80 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "quantityLabel"));
    _objc_msgSend(obj_80, "setFont:");
    _objc_release(obj_80);
    int128_t v2_20;
    int128_t v3_21;
    v2_20 = _objc_release(obj_79);
    v3_21 = 1.0;
    v2_20 = 0x3fee666666666666;
    id obj_81 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    id obj_82 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "quantityLabel"));
    _objc_msgSend(obj_82, "setTextColor:");
    _objc_release(obj_82);
    _objc_release(obj_81);
    id obj_83 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "quantityLabel"));
    _objc_msgSend(obj_83, "setTextAlignment:");
    _objc_release(obj_83);
    id obj_84 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "quantityLabel"));
    _objc_msgSend(obj_67, "addSubview:");
    _objc_release(obj_84);
    id obj_85;
    int64_t x2_62;
    int128_t v1_25;
    int128_t v2_21;
    int128_t v3_22;
    obj_85 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:", 0));
    v8 = 0x4040000000000000;
    v1_25 = 6.0;
    v2_21 = v13;
    v3_22 = v8;
    int128_t v0_36;
    int128_t v1_26;
    v0_36 = _objc_msgSend(obj_85, "setFrame:", x2_62);
    v1_26 = 1.0;
    v0_36 = 0x3fc999999999999a;
    id obj_86 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, "colorWithWhite:alpha:"));
    _objc_msgSend(obj_85, "setBackgroundColor:");
    _objc_release(obj_86);
    id obj_87;
    int128_t v0_37;
    obj_87 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_85, "layer"));
    v0_37 = 8.0;
    _objc_msgSend(obj_87, "setCornerRadius:");
    _objc_release(obj_87);
    int128_t v0_38;
    int128_t v1_27;
    int128_t v2_22;
    int128_t v3_23;
    v0_38 = _objc_msgSend(obj_85, "setTitle:forState:", &cfstr_?, 0);
    v2_22 = 1.0;
    v3_23 = 1.0;
    v0_38 = 0x3feb333333333333;
    v1_27 = 0x3feccccccccccccd;
    id obj_88 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_85, "setTitleColor:forState:", obj_88, 0);
    _objc_release(obj_88);
    int128_t v0_39;
    v0_39 = 18.0;
    id obj_89 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    id obj_90 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_85, "titleLabel"));
    _objc_msgSend(obj_90, "setFont:");
    _objc_release(obj_90);
    _objc_release(obj_89);
    _objc_msgSend(obj_85, "addTarget:action:forControlEvents:");
    _objc_msgSend(obj_67, "addSubview:");
    id obj_91;
    int128_t v1_28;
    int128_t v2_23;
    int128_t v3_24;
    obj_91 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:"));
    v1_28 = 6.0;
    v2_23 = v13;
    v3_24 = v8;
    int128_t v0_41;
    int128_t v1_29;
    v0_41 = _objc_msgSend(obj_91, "setFrame:");
    v1_29 = 1.0;
    v0_41 = 0x3fc999999999999a;
    id obj_92 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, "colorWithWhite:alpha:"));
    _objc_msgSend(obj_91, "setBackgroundColor:");
    _objc_release(obj_92);
    id obj_93;
    int128_t v0_42;
    obj_93 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_91, "layer"));
    v0_42 = 8.0;
    _objc_msgSend(obj_93, "setCornerRadius:");
    _objc_release(obj_93);
    int128_t v0_43;
    int128_t v1_30;
    int128_t v2_24;
    int128_t v3_25;
    v0_43 = _objc_msgSend(obj_91, "setTitle:forState:");
    v2_24 = 1.0;
    v3_25 = 1.0;
    v0_43 = 0x3feb333333333333;
    v1_30 = 0x3feccccccccccccd;
    id obj_94 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_91, "setTitleColor:forState:");
    _objc_release(obj_94);
    int128_t v0_44;
    v0_44 = 18.0;
    id obj_95 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    id obj_96 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_91, "titleLabel"));
    _objc_msgSend(obj_96, "setFont:");
    _objc_release(obj_96);
    _objc_release(obj_95);
    _objc_msgSend(obj_91, "addTarget:action:forControlEvents:");
    _objc_msgSend(obj_67, "addSubview:");
    id obj_97 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnerInner"));
    _objc_msgSend(obj_97, "addSubview:");
    _objc_release(obj_97);
    id x0_330;
    int128_t v0_45;
    int128_t v1_31;
    int128_t v2_25;
    int128_t v3_26;
    x0_330 = _objc_alloc(clsRef_UIView);
    v1_31 = 0x4076400000000000;
    v0_45 = 14.0;
    v2_25 = v10;
    v3_26 = v15;
    id obj_98 = _objc_msgSend(x0_330, "initWithFrame:");
    id x0_332;
    int128_t v0_46;
    int128_t v1_32;
    int128_t v3_27;
    x0_332 = _objc_alloc(clsRef_UILabel);
    v0_46 = 0.0;
    v1_32 = 0.0;
    v3_27 = v15;
    id obj_99 = _objc_msgSend(x0_332, "initWithFrame:");
    int128_t v0_47;
    int128_t v1_33;
    v0_47 = _objc_msgSend(obj_99, "setText:");
    v0_47 = 14.0;
    v1_33 = v1_1;
    id obj_100 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
        "systemFontOfSize:weight:"));
    _objc_msgSend(obj_99, "setFont:");
    int128_t v0_48;
    int128_t v1_34;
    int128_t v2_27;
    int128_t v3_28;
    v0_48 = _objc_release(obj_100);
    v2_27 = 1.0;
    v3_28 = 1.0;
    v0_48 = 0x3feb333333333333;
    v1_34 = 0x3feccccccccccccd;
    id obj_101 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_99, "setTextColor:");
    _objc_release(obj_101);
    _objc_msgSend(obj_98, "addSubview:");
    id x0_343;
    int128_t v2_28;
    int128_t v3_29;
    x0_343 = _objc_alloc(clsRef_UISwitch);
    v3_29 = 31.0;
    v2_28 = 0x4049800000000000;
    int64_t obj_102 = _objc_msgSend(x0_343, "initWithFrame:");
    _objc_msgSend(self, "setLoopSwitch:", obj_102);
    int128_t v0_50;
    int128_t v1_36;
    int128_t v2_29;
    int128_t v3_30;
    v0_50 = _objc_release(obj_102);
    v3_30 = 1.0;
    v0_50 = 0x3fd999999999999a;
    v1_36 = 0x3fc999999999999a;
    v2_29 = 0x3fee666666666666;
    id obj_103 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    id obj_104 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "loopSwitch"));
    _objc_msgSend(obj_104, "setOnTintColor:", obj_103);
    _objc_release(obj_104);
    _objc_release(obj_103);
    id obj_105 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "loopSwitch"));
    _objc_msgSend(obj_98, "addSubview:");
    _objc_release(obj_105);
    id obj_106 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnerInner"));
    _objc_msgSend(obj_106, "addSubview:");
    _objc_release(obj_106);
    id x0_360;
    int128_t v0_51;
    int128_t v2_30;
    x0_360 = _objc_alloc(clsRef_UIView);
    v0_51 = 14.0;
    v2_30 = v10;
    id obj_107;
    int128_t v0_52;
    int128_t v2_31;
    int128_t v3_31;
    obj_107 = _objc_msgSend(x0_360, "initWithFrame:");
    v0_52 = 0x3fb70a3d70a3d70a;
    v2_31 = 0x3fc47ae147ae147b;
    v3_31 = 1.0;
    id obj_108 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_107, "setBackgroundColor:");
    _objc_release(obj_108);
    id obj_109;
    int128_t v0_53;
    obj_109 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_107, "layer"));
    v0_53 = 12.0;
    _objc_msgSend(obj_109, "setCornerRadius:");
    _objc_release(obj_109);
    id obj_110;
    int128_t v0_54;
    obj_110 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_107, "layer"));
    v0_54 = 1.0;
    _objc_msgSend(obj_110, "setBorderWidth:");
    int128_t v0_55;
    int128_t v1_37;
    v0_55 = _objc_release(obj_110);
    v1_37 = 1.0;
    v0_55 = 0x3fc3333333333333;
    id obj_111 = _objc_retainAutorelease(_objc_retainAutoreleasedReturnValue(_objc_msgSend(
        clsRef_UIColor, "colorWithWhite:alpha:")));
    _objc_msgSend(obj_111, "CGColor");
    id obj_112 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_107, "layer"));
    _objc_msgSend(obj_112, "setBorderColor:");
    _objc_release(obj_112);
    _objc_release(obj_111);
    _objc_msgSend(obj_107, "setTag:");
    id x0_381;
    int128_t v0_56;
    int128_t v1_38;
    int128_t v2_32;
    int128_t v3_32;
    x0_381 = _objc_alloc(clsRef_UILabel);
    v0_56 = 10.0;
    v1_38 = 4.0;
    v3_32 = 24.0;
    v2_32 = v2_17;
    id obj_113 = _objc_msgSend(x0_381, "initWithFrame:");
    _objc_msgSend(obj_113, "setText:");
    int128_t v0_57;
    v0_57 = 13.0;
    id obj_114 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    _objc_msgSend(obj_113, "setFont:");
    int128_t v0_58;
    int128_t v1_39;
    int128_t v2_33;
    int128_t v3_33;
    v0_58 = _objc_release(obj_114);
    v3_33 = 1.0;
    v0_58 = 0x3fd999999999999a;
    v1_39 = 0x3fc999999999999a;
    v2_33 = 0x3fee666666666666;
    id obj_115 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_113, "setTextColor:");
    _objc_release(obj_115);
    _objc_msgSend(obj_107, "addSubview:");
    id x0_392;
    int128_t v0_59;
    int128_t v1_40;
    int128_t v2_34;
    int128_t v3_34;
    x0_392 = _objc_alloc(clsRef_UISwitch);
    v1_40 = 2.0;
    v3_34 = 26.0;
    v0_59 = v2_17;
    v2_34 = 0x4049800000000000;
    id obj_116;
    int128_t v0_60;
    int128_t v1_41;
    int128_t v2_35;
    int128_t v3_35;
    obj_116 = _objc_msgSend(x0_392, "initWithFrame:");
    v3_35 = 1.0;
    v0_60 = 0x3fd999999999999a;
    v1_41 = 0x3fc999999999999a;
    v2_35 = 0x3fee666666666666;
    id obj_117 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_116, "setOnTintColor:");
    _objc_release(obj_117);
    _objc_msgSend(obj_116, "setOn:", data_446ac0);
    _objc_msgSend(obj_116, "setTag:");
    _objc_msgSend(obj_116, "addTarget:action:forControlEvents:");
    _objc_msgSend(obj_107, "addSubview:");
    id x0_402;
    int128_t v1_42;
    int128_t v2_36;
    int128_t v3_36;
    x0_402 = _objc_alloc(clsRef_UIView);
    v1_42 = 4.0;
    v2_36 = 30.0;
    v3_36 = 30.0;
    int64_t obj_118 = _objc_msgSend(x0_402, "initWithFrame:");
    _objc_msgSend(self, "setColorPreview:", obj_118);
    int64_t x2_97;
    int64_t x3_12;
    int64_t x4_4;
    int64_t x5_1;
    int128_t v2_37;
    int128_t v3_37;
    x2_97 = _objc_release(obj_118);
    data_446ac4;
    data_446760;
    v2_37 = 0x406fe00000000000;
    v2_37 = 1.0;
    v3_37 = 1.0;
    id obj_119 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithHue:saturation:brightness:alpha:", x2_97, x3_12, x4_4, x5_1));
    id obj_120 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "colorPreview"));
    _objc_msgSend(obj_120, "setBackgroundColor:");
    _objc_release(obj_120);
    _objc_release(obj_119);
    id obj_121 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "colorPreview"));
    id obj_122;
    int128_t v0_63;
    obj_122 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_121, "layer"));
    v0_63 = 6.0;
    _objc_msgSend(obj_122, "setCornerRadius:");
    _objc_release(obj_122);
    _objc_release(obj_121);
    id obj_123 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "colorPreview"));
    id obj_124;
    int128_t v0_64;
    obj_124 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_123, "layer"));
    v0_64 = 1.5;
    _objc_msgSend(obj_124, "setBorderWidth:");
    _objc_release(obj_124);
    _objc_release(obj_123);
    id obj_125 = _objc_retainAutorelease(_objc_retainAutoreleasedReturnValue(_objc_msgSend(
        clsRef_UIColor, "whiteColor")));
    _objc_msgSend(obj_125, "CGColor");
    id obj_126 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "colorPreview"));
    id obj_127 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_126, "layer"));
    _objc_msgSend(obj_127, "setBorderColor:");
    _objc_release(obj_127);
    _objc_release(obj_126);
    _objc_release(obj_125);
    id obj_128 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "colorPreview"));
    _objc_msgSend(obj_107, "addSubview:");
    _objc_release(obj_128);
    v11 = v10 + -0x3fb2000000000000;
    id x0_436;
    int128_t v0_66;
    int128_t v1_44;
    int128_t v2_38;
    int128_t v3_38;
    x0_436 = _objc_alloc(clsRef_UILabel);
    v9 = 0x4041000000000000;
    v0_66 = 10.0;
    v2_38 = 30.0;
    v3_38 = 20.0;
    v1_44 = v9;
    id obj_129 = _objc_msgSend(x0_436, "initWithFrame:");
    _objc_msgSend(obj_129, "setText:");
    int128_t v0_67;
    v0_67 = 10.0;
    id obj_130 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    _objc_msgSend(obj_129, "setFont:");
    int128_t v0_68;
    int128_t v1_45;
    int128_t v2_39;
    int128_t v3_39;
    v0_68 = _objc_release(obj_130);
    v3_39 = 1.0;
    v0_68 = 0x3fb999999999999a;
    v1_45 = 0x3fe999999999999a;
    v2_39 = 0x3fee666666666666;
    id obj_131 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_129, "setTextColor:");
    _objc_release(obj_131);
    _objc_msgSend(obj_107, "addSubview:");
    id x0_447;
    int128_t v1_46;
    int128_t v3_40;
    x0_447 = _objc_alloc(clsRef_UISlider);
    double var_440 = v11;
    double v2_40 = v11 + -14.0;
    v3_40 = 20.0;
    v1_46 = v9;
    int64_t obj_132 = _objc_msgSend(x0_447, "initWithFrame:");
    _objc_msgSend(self, "setRedSlider:", obj_132);
    _objc_release(obj_132);
    id obj_133;
    int64_t x2_106;
    int128_t v0_70;
    obj_133 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "redSlider"));
    v0_70 = 0f;
    _objc_msgSend(obj_133, "setMinimumValue:", x2_106);
    _objc_release(obj_133);
    id obj_134;
    int64_t x2_107;
    int128_t v0_71;
    obj_134 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "redSlider"));
    v0_71 = 0x43b40000;
    _objc_msgSend(obj_134, "setMaximumValue:", x2_107);
    _objc_release(obj_134);
    v8 = data_446ac4;
    id obj_135;
    int64_t x2_108;
    int128_t v0_73;
    obj_135 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "redSlider"));
    v0_73 = v8;
    _objc_msgSend(obj_135, "setValue:", x2_108);
    _objc_release(obj_135);
    id obj_136 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, "orangeColor"));
    id obj_137 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "redSlider"));
    _objc_msgSend(obj_137, "setMinimumTrackTintColor:", obj_136);
    _objc_release(obj_137);
    _objc_release(obj_136);
    id obj_138 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "redSlider"));
    _objc_msgSend(obj_138, "addTarget:action:forControlEvents:");
    _objc_release(obj_138);
    id obj_139 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "redSlider"));
    _objc_msgSend(obj_107, "addSubview:");
    _objc_release(obj_139);
    id x0_473;
    int128_t v1_47;
    int128_t v2_41;
    int128_t v3_41;
    x0_473 = _objc_alloc(clsRef_UILabel);
    v3_41 = 20.0;
    v1_47 = v9;
    v2_41 = v15;
    id obj_140 = _objc_msgSend(x0_473, "initWithFrame:");
    uint64_t var_480_1 = data_446ac4;
    id obj_141 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, "stringWithFormat:"));
    _objc_msgSend(obj_140, "setText:");
    int64_t x2_114;
    int64_t x3_13;
    int128_t v0_75;
    int128_t v1_48;
    x2_114 = _objc_release(obj_141);
    v11 = *_UIFontWeightBold;
    v0_75 = 10.0;
    v1_48 = v11;
    id obj_142 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
        "monospacedDigitSystemFontOfSize:weight:", x2_114, x3_13));
    _objc_msgSend(obj_140, "setFont:");
    int128_t v0_76;
    int128_t v1_49;
    int128_t v2_42;
    int128_t v3_42;
    v0_76 = _objc_release(obj_142);
    v2_42 = 1.0;
    v3_42 = 1.0;
    v0_76 = 0x3feb333333333333;
    v1_49 = 0x3feccccccccccccd;
    id obj_143 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_140, "setTextColor:");
    _objc_release(obj_143);
    _objc_msgSend(obj_140, "setTextAlignment:");
    _objc_msgSend(obj_140, "setTag:");
    _objc_msgSend(obj_107, "addSubview:");
    id x0_490;
    int128_t v0_77;
    int128_t v1_50;
    int128_t v2_43;
    int128_t v3_43;
    x0_490 = _objc_alloc(clsRef_UILabel);
    v9 = 0x404d000000000000;
    v0_77 = 10.0;
    v2_43 = 30.0;
    v3_43 = 20.0;
    v1_50 = v9;
    id obj_144 = _objc_msgSend(x0_490, "initWithFrame:");
    _objc_msgSend(obj_144, "setText:");
    int128_t v0_78;
    v0_78 = 10.0;
    id obj_145 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    _objc_msgSend(obj_144, "setFont:");
    _objc_release(obj_145);
    id obj_146 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, "cyanColor"));
    _objc_msgSend(obj_144, "setTextColor:");
    _objc_release(obj_146);
    _objc_msgSend(obj_107, "addSubview:");
    id x0_501;
    int128_t v0_79;
    int128_t v1_51;
    int128_t v2_44;
    int128_t v3_44;
    x0_501 = _objc_alloc(clsRef_UISlider);
    v3_44 = 20.0;
    v0_79 = 0x4045000000000000;
    v1_51 = v9;
    v2_44 = v2_40;
    int64_t obj_147 = _objc_msgSend(x0_501, "initWithFrame:");
    _objc_msgSend(self, "setGreenSlider:", obj_147);
    _objc_release(obj_147);
    id obj_148;
    int128_t v0_80;
    obj_148 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "greenSlider"));
    v0_80 = 0f;
    _objc_msgSend(obj_148, "setMinimumValue:");
    _objc_release(obj_148);
    id obj_149;
    int128_t v0_81;
    obj_149 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "greenSlider"));
    v0_81 = 0x437f0000;
    _objc_msgSend(obj_149, "setMaximumValue:");
    _objc_release(obj_149);
    v13 = data_446760;
    id obj_150;
    int128_t v0_83;
    obj_150 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "greenSlider"));
    v0_83 = v13;
    _objc_msgSend(obj_150, "setValue:");
    _objc_release(obj_150);
    id obj_151 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, "cyanColor"));
    id obj_152 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "greenSlider"));
    _objc_msgSend(obj_152, "setMinimumTrackTintColor:");
    _objc_release(obj_152);
    _objc_release(obj_151);
    id obj_153 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "greenSlider"));
    _objc_msgSend(obj_153, "addTarget:action:forControlEvents:");
    _objc_release(obj_153);
    id obj_154 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "greenSlider"));
    _objc_msgSend(obj_107, "addSubview:");
    _objc_release(obj_154);
    id x0_527;
    int128_t v0_84;
    int128_t v1_52;
    int128_t v2_45;
    int128_t v3_45;
    x0_527 = _objc_alloc(clsRef_UILabel);
    v3_45 = 20.0;
    v0_84 = v10 + -0x3fbb000000000000;
    v1_52 = v9;
    v2_45 = v15;
    id obj_155 = _objc_msgSend(x0_527, "initWithFrame:");
    uint64_t var_480_2 = data_446760;
    id obj_156 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, "stringWithFormat:"));
    _objc_msgSend(obj_155, "setText:");
    int128_t v0_85;
    int128_t v1_53;
    v0_85 = _objc_release(obj_156);
    v0_85 = 10.0;
    v1_53 = v11;
    id obj_157 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
        "monospacedDigitSystemFontOfSize:weight:"));
    _objc_msgSend(obj_155, "setFont:");
    int128_t v0_86;
    int128_t v1_54;
    int128_t v2_46;
    int128_t v3_46;
    v0_86 = _objc_release(obj_157);
    v2_46 = 1.0;
    v3_46 = 1.0;
    v0_86 = 0x3feb333333333333;
    v1_54 = 0x3feccccccccccccd;
    id obj_158 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_155, "setTextColor:");
    _objc_release(obj_158);
    _objc_msgSend(obj_155, "setTextAlignment:");
    _objc_msgSend(obj_155, "setTag:");
    _objc_msgSend(obj_107, "addSubview:");
    id x0_544;
    int128_t v0_87;
    int128_t v1_55;
    int128_t v2_47;
    int128_t v3_47;
    x0_544 = _objc_alloc(clsRef_UILabel);
    v8 = 0x4055000000000000;
    v0_87 = 10.0;
    v3_47 = 26.0;
    v1_55 = v8;
    v2_47 = 0x4059000000000000;
    id obj_159 = _objc_msgSend(x0_544, "initWithFrame:");
    int128_t v0_88;
    int128_t v1_56;
    v0_88 = _objc_msgSend(obj_159, "setText:");
    v0_88 = 12.0;
    v1_56 = v1_1;
    id obj_160 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
        "systemFontOfSize:weight:"));
    _objc_msgSend(obj_159, "setFont:");
    int128_t v0_89;
    int128_t v1_57;
    int128_t v2_48;
    int128_t v3_48;
    v0_89 = _objc_release(obj_160);
    v2_48 = 1.0;
    v3_48 = 1.0;
    v0_89 = 0x3feb333333333333;
    v1_57 = 0x3feccccccccccccd;
    id obj_161 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_159, "setTextColor:");
    _objc_release(obj_161);
    _objc_msgSend(obj_107, "addSubview:");
    id x0_555;
    int128_t v1_58;
    int128_t v2_49;
    int128_t v3_49;
    x0_555 = _objc_alloc(clsRef_UISwitch);
    v3_49 = 26.0;
    v1_58 = v8;
    v2_49 = 0x4049800000000000;
    int64_t obj_162 = _objc_msgSend(x0_555, "initWithFrame:");
    _objc_msgSend(self, "setRandomColorSwitch:", obj_162);
    int128_t v0_90;
    int128_t v1_59;
    int128_t v2_50;
    int128_t v3_50;
    v0_90 = _objc_release(obj_162);
    v3_50 = 1.0;
    v0_90 = 0x3fb999999999999a;
    v1_59 = 0x3fe999999999999a;
    v2_50 = 0x3fee666666666666;
    id obj_163 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    id obj_164 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "randomColorSwitch"));
    _objc_msgSend(obj_164, "setOnTintColor:");
    _objc_release(obj_164);
    _objc_release(obj_163);
    data_446ac8;
    id obj_165 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "randomColorSwitch"));
    _objc_msgSend(obj_165, "setOn:");
    _objc_release(obj_165);
    id obj_166 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "randomColorSwitch"));
    _objc_msgSend(obj_166, "addTarget:action:forControlEvents:");
    _objc_release(obj_166);
    id obj_167 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "randomColorSwitch"));
    _objc_msgSend(obj_107, "addSubview:");
    _objc_release(obj_167);
    id obj_168;
    int128_t v0_91;
    int128_t v1_60;
    int128_t v2_51;
    int128_t v3_51;
    obj_168 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:"));
    v0_91 = -0x3fa9800000000000;
    v0_91 = v10 + -90.0;
    v3_51 = 28.0;
    v1_60 = v8;
    v2_51 = v2_17;
    int128_t v0_92;
    int128_t v1_61;
    int128_t v2_52;
    int128_t v3_52;
    v0_92 = _objc_msgSend(obj_168, "setFrame:");
    v3_52 = 1.0;
    v0_92 = 0x3fb999999999999a;
    v1_61 = 0x3fe999999999999a;
    v2_52 = 0x3fee666666666666;
    id obj_169 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_168, "setBackgroundColor:");
    _objc_release(obj_169);
    id obj_170;
    int128_t v0_93;
    obj_170 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_168, "layer"));
    v0_93 = 8.0;
    _objc_msgSend(obj_170, "setCornerRadius:");
    _objc_release(obj_170);
    int128_t v0_94;
    int128_t v1_62;
    int128_t v2_53;
    int128_t v3_53;
    v0_94 = _objc_msgSend(obj_168, "setTitle:forState:");
    v2_53 = 1.0;
    v3_53 = 1.0;
    v0_94 = 0x3feb333333333333;
    v1_62 = 0x3feccccccccccccd;
    id obj_171 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_168, "setTitleColor:forState:");
    _objc_release(obj_171);
    int128_t v0_95;
    v0_95 = 11.0;
    id obj_172 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    id obj_173 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_168, "titleLabel"));
    _objc_msgSend(obj_173, "setFont:");
    _objc_release(obj_173);
    _objc_release(obj_172);
    _objc_msgSend(obj_168, "addTarget:action:forControlEvents:");
    _objc_msgSend(obj_107, "addSubview:");
    struct __NSConstantString* const var_110 = &cfstr_Red;
    struct __NSConstantString* const var_108 = &cfstr_Blue;
    struct __NSConstantString* const var_100 = &cfstr_Green;
    struct __NSConstantString* const var_f8 = &cfstr_Gold;
    struct __NSConstantString* const var_f0 = &cfstr_Pink;
    struct __NSConstantString* const var_e8 = &cfstr_Cyan;
    id obj_174 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:"));
    id obj_175 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, "numberWithInt:", 0));
    id obj_333 = obj_175;
    id obj_176 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, "numberWithInt:", 0xf0));
    id obj_334 = obj_176;
    id obj_177 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, "numberWithInt:", 0x78));
    id obj_335 = obj_177;
    id obj_178 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, "numberWithInt:", 0x2d));
    id obj_336 = obj_178;
    id obj_179 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithInt:", 0x14a));
    id obj_337 = obj_179;
    id obj_180 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, "numberWithInt:", 0xb4));
    id obj_338 = obj_180;
    id obj_181 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:"));
    _objc_release(obj_180);
    _objc_release(obj_179);
    _objc_release(obj_178);
    _objc_release(obj_177);
    _objc_release(obj_176);
    _objc_release(obj_175);
    v13 = v10 + -20.0;
    
    if (_objc_msgSend(obj_174, "count") >= 1)
    {
        int64_t x19_80 = 0;
        v8 = (v13 + -25.0) / 6.0;
        int64_t x0_651;
        
        do
        {
            id obj_182;
            int128_t v0_97;
            int128_t v1_64;
            int128_t v2_54;
            int128_t v3_54;
            obj_182 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, 
                "buttonWithType:"));
            v3_54 = 24.0;
            v0_97 = v12;
            v1_64 = 0x405d800000000000;
            v2_54 = v8;
            _objc_msgSend(obj_182, "setFrame:");
            struct objc_class_t* clsRef_UIColor_1 = clsRef_UIColor;
            id obj_183 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_181, 
                "objectAtIndexedSubscript:"));
            double v0_98;
            int128_t v1_65;
            int128_t v2_55;
            int128_t v3_55;
            v0_98 = _objc_msgSend(obj_183, "floatValue");
            v2_55 = 1.0;
            v3_55 = 1.0;
            v1_65 = 0x3fe999999999999a;
            id obj_184 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor_1, 
                "colorWithHue:saturation:brightness:alpha:"));
            _objc_msgSend(obj_182, "setBackgroundColor:");
            _objc_release(obj_184);
            _objc_release(obj_183);
            id obj_185;
            int128_t v0_99;
            obj_185 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_182, "layer"));
            v0_99 = 6.0;
            _objc_msgSend(obj_185, "setCornerRadius:");
            _objc_release(obj_185);
            id obj_186 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_174, 
                "objectAtIndexedSubscript:"));
            _objc_msgSend(obj_182, "setTitle:forState:");
            _objc_release(obj_186);
            int128_t v0_100;
            v0_100 = 8.0;
            id obj_187 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
                "boldSystemFontOfSize:"));
            id obj_188 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_182, "titleLabel"));
            _objc_msgSend(obj_188, "setFont:");
            _objc_release(obj_188);
            _objc_release(obj_187);
            id obj_189 =
                _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, "whiteColor"));
            _objc_msgSend(obj_182, "setTitleColor:forState:");
            _objc_release(obj_189);
            _objc_msgSend(obj_182, "setTag:");
            _objc_msgSend(obj_182, "addTarget:action:forControlEvents:");
            _objc_msgSend(obj_107, "addSubview:");
            v12 = v8 + 5.0 + v12;
            _objc_release(obj_182);
            x0_651 = _objc_msgSend(obj_174, "count");
            x19_80 += 1;
        } while (x19_80 < x0_651);
    }
    
    id x0_653;
    int128_t v0_101;
    int128_t v1_66;
    int128_t v2_56;
    int128_t v3_56;
    x0_653 = _objc_alloc(clsRef_UILabel);
    v1_66 = 0x4062400000000000;
    v0_101 = 10.0;
    v3_56 = 16.0;
    v2_56 = v13;
    id obj_190 = _objc_msgSend(x0_653, "initWithFrame:");
    uint64_t var_480_3 = data_446ac4;
    uint64_t var_478 = data_446760;
    id obj_191 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, "stringWithFormat:"));
    _objc_msgSend(obj_190, "setText:");
    int64_t x2_163;
    int64_t x3_24;
    int128_t v0_102;
    x2_163 = _objc_release(obj_191);
    double v1_67 = *_UIFontWeightRegular;
    v0_102 = 9.0;
    id obj_192 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
        "monospacedSystemFontOfSize:weight:", x2_163, x3_24));
    _objc_msgSend(obj_190, "setFont:");
    int128_t v0_103;
    int128_t v1_68;
    int128_t v2_57;
    int128_t v3_57;
    v0_103 = _objc_release(obj_192);
    v3_57 = 1.0;
    v0_103 = 0x3fdccccccccccccd;
    v1_68 = 0x3fe199999999999a;
    v2_57 = 0x3fe6666666666666;
    id obj_193 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_190, "setTextColor:");
    _objc_release(obj_193);
    _objc_msgSend(obj_190, "setTag:");
    int128_t v0_104;
    int128_t v1_69;
    int128_t v2_58;
    int128_t v3_58;
    v0_104 = _objc_msgSend(obj_107, "addSubview:");
    v3_58 = 0x406b800000000000;
    v0_104 = 14.0;
    v1_69 = 0x4078e00000000000;
    v2_58 = v10;
    _objc_msgSend(obj_107, "setFrame:");
    id x0_670;
    int128_t v0_105;
    int128_t v1_70;
    int128_t v2_59;
    int128_t v3_59;
    x0_670 = _objc_alloc(clsRef_UIView);
    v1_70 = 0x4064c00000000000;
    v0_105 = 10.0;
    v3_59 = 1.0;
    v2_59 = v13;
    id obj_194;
    int128_t v0_106;
    int128_t v1_71;
    obj_194 = _objc_msgSend(x0_670, "initWithFrame:");
    v1_71 = 1.0;
    v0_106 = 0x3fc999999999999a;
    id obj_195 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, "colorWithWhite:alpha:"));
    _objc_msgSend(obj_194, "setBackgroundColor:");
    _objc_release(obj_195);
    _objc_msgSend(obj_107, "addSubview:");
    id x0_677;
    int128_t v0_107;
    int128_t v1_72;
    int128_t v2_60;
    int128_t v3_60;
    x0_677 = _objc_alloc(clsRef_UILabel);
    v2_60 = 0x4049000000000000;
    v0_107 = 10.0;
    v3_60 = 20.0;
    v1_72 = 0x4065400000000000;
    id obj_196 = _objc_msgSend(x0_677, "initWithFrame:");
    _objc_msgSend(obj_196, "setText:");
    int128_t v0_108;
    v0_108 = 11.0;
    id obj_197 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    _objc_msgSend(obj_196, "setFont:");
    int128_t v0_109;
    int128_t v1_73;
    int128_t v2_61;
    int128_t v3_61;
    v0_109 = _objc_release(obj_197);
    v3_61 = 1.0;
    v0_109 = 0x3fb999999999999a;
    v1_73 = 0x3fe999999999999a;
    v2_61 = 0x3fee666666666666;
    id obj_198 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_196, "setTextColor:");
    _objc_release(obj_198);
    _objc_msgSend(obj_107, "addSubview:");
    id x0_688;
    int128_t v0_110;
    int128_t v1_74;
    int128_t v2_62;
    int128_t v3_62;
    x0_688 = _objc_alloc(clsRef_UISwitch);
    v0_110 = 0x404e000000000000;
    v1_74 = 0x4065000000000000;
    v2_62 = 0x4045000000000000;
    v3_62 = 22.0;
    id obj_199;
    int128_t v0_111;
    int128_t v1_75;
    int128_t v2_63;
    int128_t v3_63;
    obj_199 = _objc_msgSend(x0_688, "initWithFrame:");
    v3_63 = 1.0;
    v0_111 = 0x3fb999999999999a;
    v1_75 = 0x3fe999999999999a;
    v2_63 = 0x3fee666666666666;
    id obj_200 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_199, "setOnTintColor:");
    _objc_release(obj_200);
    data_446ac9;
    _objc_msgSend(obj_199, "setOn:");
    int128_t v0_113;
    int128_t v1_77;
    v0_113 = _CGAffineTransformMakeScale(0x3fe6666666666666, 0x3fe6666666666666);
    int128_t var_180;
    int128_t var_1b0 = var_180;
    int128_t var_170;
    int128_t var_1a0 = var_170;
    int128_t var_160;
    int128_t var_190 = var_160;
    _objc_msgSend(obj_199, "setTransform:", &var_1b0);
    _objc_msgSend(obj_199, "setTag:");
    _objc_msgSend(obj_199, "addTarget:action:forControlEvents:");
    _objc_msgSend(obj_107, "addSubview:");
    id x0_699;
    int128_t v0_114;
    int128_t v1_78;
    int128_t v2_64;
    int128_t v3_64;
    x0_699 = _objc_alloc(clsRef_UISlider);
    v0_114 = -0x3f9ac00000000000;
    v2_64 = v10 + -170.0;
    v3_64 = 20.0;
    v0_114 = 0x405b800000000000;
    v1_78 = 0x4065400000000000;
    id obj_201;
    int128_t v0_115;
    obj_201 = _objc_msgSend(x0_699, "initWithFrame:");
    v0_115 = -5f;
    _objc_msgSend(obj_201, "setMinimumValue:");
    int128_t v0_116;
    v0_116 = 10f;
    _objc_msgSend(obj_201, "setMaximumValue:");
    data_446acc;
    int128_t v0_118;
    int128_t v1_79;
    int128_t v2_65;
    int128_t v3_65;
    v0_118 = _objc_msgSend(obj_201, "setValue:");
    v3_65 = 1.0;
    v0_118 = 0x3fb999999999999a;
    v1_79 = 0x3fe999999999999a;
    v2_65 = 0x3fee666666666666;
    id obj_202 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_201, "setMinimumTrackTintColor:");
    _objc_release(obj_202);
    _objc_msgSend(obj_201, "setTag:");
    _objc_msgSend(obj_201, "addTarget:action:forControlEvents:");
    _objc_msgSend(obj_107, "addSubview:");
    id x0_710;
    int128_t v0_119;
    int128_t v1_80;
    int128_t v2_66;
    int128_t v3_66;
    x0_710 = _objc_alloc(clsRef_UILabel);
    v2_66 = 0x4046000000000000;
    v3_66 = 20.0;
    v0_119 = v10 + -0x3fb7000000000000;
    v1_80 = 0x4065400000000000;
    id obj_203 = _objc_msgSend(x0_710, "initWithFrame:");
    uint64_t var_480_4 = data_446acc;
    id obj_204 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, "stringWithFormat:"));
    _objc_msgSend(obj_203, "setText:");
    int128_t v0_120;
    int128_t v1_81;
    v0_120 = _objc_release(obj_204);
    v0_120 = 11.0;
    v1_81 = v11;
    id obj_205 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
        "monospacedDigitSystemFontOfSize:weight:"));
    _objc_msgSend(obj_203, "setFont:");
    int128_t v1_82;
    int128_t v2_67;
    int128_t v3_67;
    v1_82 = _objc_release(obj_205);
    v2_67 = 1.0;
    v3_67 = 1.0;
    v1_82 = 0x3feccccccccccccd;
    id obj_206 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_203, "setTextColor:");
    _objc_release(obj_206);
    _objc_msgSend(obj_203, "setTextAlignment:");
    _objc_msgSend(obj_203, "setTag:");
    _objc_msgSend(obj_107, "addSubview:");
    id x0_727;
    int128_t v0_121;
    int128_t v1_83;
    int128_t v2_68;
    int128_t v3_68;
    x0_727 = _objc_alloc(clsRef_UILabel);
    v1_83 = 0x4068400000000000;
    v0_121 = 10.0;
    v3_68 = 16.0;
    v2_68 = v13;
    id obj_207 = _objc_msgSend(x0_727, "initWithFrame:");
    _objc_msgSend(obj_207, "setText:");
    int128_t v0_122;
    v0_122 = 9.0;
    id obj_208 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "systemFontOfSize:"));
    _objc_msgSend(obj_207, "setFont:");
    int128_t v0_123;
    int128_t v1_84;
    int128_t v2_69;
    int128_t v3_69;
    v0_123 = _objc_release(obj_208);
    v3_69 = 1.0;
    v0_123 = 0x3fdccccccccccccd;
    v1_84 = 0x3fe199999999999a;
    v2_69 = 0x3fe6666666666666;
    id obj_209 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_207, "setTextColor:");
    _objc_release(obj_209);
    _objc_msgSend(obj_107, "addSubview:");
    id obj_210 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnerInner"));
    _objc_msgSend(obj_210, "addSubview:");
    _objc_release(obj_210);
    id obj_211 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:"));
    _objc_msgSend(self, "setSpawnBtn:", obj_211);
    _objc_release(obj_211);
    id obj_212;
    int128_t v0_124;
    int128_t v1_85;
    int128_t v2_70;
    int128_t v3_70;
    obj_212 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnBtn"));
    v1_85 = 0x4083900000000000;
    v8 = 0x4048000000000000;
    v0_124 = 14.0;
    v2_70 = v10;
    v3_70 = v8;
    _objc_msgSend(obj_212, "setFrame:");
    _objc_release(obj_212);
    id obj_213 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnBtn"));
    id obj_214;
    int128_t v0_125;
    obj_214 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_213, "layer"));
    v0_125 = 14.0;
    _objc_msgSend(obj_214, "setCornerRadius:");
    _objc_release(obj_214);
    _objc_release(obj_213);
    id obj_215 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_CAGradientLayer, "layer"));
    id obj_216 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnBtn"));
    int128_t v0_126;
    int128_t v1_86;
    double v2_71;
    int128_t v3_71;
    v0_126 = _objc_msgSend(obj_216, "bounds");
    v0_126 = 0x4074c00000000000;
    v0_126 = 0.0;
    v1_86 = 0.0;
    v3_71 = v8;
    _objc_msgSend(obj_215, "setFrame:");
    int128_t v0_127;
    int128_t v1_87;
    int128_t v2_72;
    int128_t v3_72;
    v0_127 = _objc_release(obj_216);
    v3_72 = 1.0;
    v0_127 = 0x3fc3333333333333;
    v1_87 = 0x3fd999999999999a;
    v2_72 = 0x3feccccccccccccd;
    id obj_217 = _objc_retainAutorelease(_objc_retainAutoreleasedReturnValue(_objc_msgSend(
        clsRef_UIColor, "colorWithRed:green:blue:alpha:")));
    int64_t x0_761;
    int128_t v0_128;
    int128_t v1_88;
    int128_t v2_73;
    int128_t v3_73;
    x0_761 = _objc_msgSend(obj_217, "CGColor");
    int64_t var_150 = x0_761;
    v0_128 = 0.5;
    v3_73 = 1.0;
    v1_88 = 0x3fc999999999999a;
    v2_73 = 0x3feb333333333333;
    id obj_218 = _objc_retainAutorelease(_objc_retainAutoreleasedReturnValue(_objc_msgSend(
        clsRef_UIColor, "colorWithRed:green:blue:alpha:")));
    int64_t var_148 = _objc_msgSend(obj_218, "CGColor");
    id obj_219 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:"));
    _objc_msgSend(obj_215, "setColors:", obj_219);
    _objc_release(obj_219);
    _objc_release(obj_218);
    _objc_release(obj_217);
    int128_t v0_129;
    v0_129 = 14.0;
    _objc_msgSend(obj_215, "setCornerRadius:");
    id obj_220 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnBtn"));
    id obj_221 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_220, "layer"));
    _objc_msgSend(obj_221, "insertSublayer:atIndex:", obj_215, 0);
    _objc_release(obj_221);
    _objc_release(obj_220);
    id obj_222 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnBtn"));
    _objc_msgSend(obj_222, "setTitle:forState:");
    _objc_release(obj_222);
    id obj_223;
    int128_t v0_130;
    int128_t v1_89;
    int128_t v2_74;
    int128_t v3_74;
    obj_223 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnBtn"));
    v2_74 = 1.0;
    v3_74 = 1.0;
    v0_130 = 0x3feb333333333333;
    v1_89 = 0x3feccccccccccccd;
    id obj_224 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_223, "setTitleColor:forState:");
    _objc_release(obj_224);
    _objc_release(obj_223);
    int128_t v0_131;
    v0_131 = 18.0;
    id obj_225 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    id obj_226 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnBtn"));
    id obj_227 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_226, "titleLabel"));
    _objc_msgSend(obj_227, "setFont:");
    _objc_release(obj_227);
    _objc_release(obj_226);
    _objc_release(obj_225);
    id obj_228 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnBtn"));
    _objc_msgSend(obj_228, "addTarget:action:forControlEvents:");
    _objc_release(obj_228);
    id obj_229 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnerInner"));
    id obj_230 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnBtn"));
    _objc_msgSend(obj_229, "addSubview:");
    _objc_release(obj_230);
    _objc_release(obj_229);
    id obj_231 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:"));
    _objc_msgSend(self, "setHeartBtn:", obj_231);
    _objc_release(obj_231);
    v14 = (v10 + -8.0) * 0.5;
    id obj_232;
    int128_t v0_133;
    int128_t v1_90;
    int128_t v2_75;
    int128_t v3_75;
    obj_232 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "heartBtn"));
    v13 = 0x4044000000000000;
    v0_133 = 14.0;
    v1_90 = 0x4085500000000000;
    v2_75 = v14;
    v3_75 = v13;
    _objc_msgSend(obj_232, "setFrame:");
    int128_t v0_134;
    int128_t v1_91;
    int128_t v3_76;
    v0_134 = _objc_release(obj_232);
    v1_91 = 0.25;
    v3_76 = 1.0;
    v0_134 = 0x3feb333333333333;
    id obj_233 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    id obj_234 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "heartBtn"));
    _objc_msgSend(obj_234, "setBackgroundColor:");
    _objc_release(obj_234);
    _objc_release(obj_233);
    id obj_235 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "heartBtn"));
    id obj_236;
    int128_t v0_135;
    obj_236 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_235, "layer"));
    v0_135 = 12.0;
    _objc_msgSend(obj_236, "setCornerRadius:");
    _objc_release(obj_236);
    _objc_release(obj_235);
    id obj_237 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "heartBtn"));
    _objc_msgSend(obj_237, "setTitle:forState:");
    _objc_release(obj_237);
    id obj_238;
    int128_t v0_136;
    int128_t v1_92;
    int128_t v2_76;
    int128_t v3_77;
    obj_238 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "heartBtn"));
    v2_76 = 1.0;
    v3_77 = 1.0;
    v0_136 = 0x3feb333333333333;
    v1_92 = 0x3feccccccccccccd;
    id obj_239 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_238, "setTitleColor:forState:");
    _objc_release(obj_239);
    _objc_release(obj_238);
    int128_t v0_137;
    v0_137 = 14.0;
    id obj_240 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    id obj_241 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "heartBtn"));
    id obj_242 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_241, "titleLabel"));
    _objc_msgSend(obj_242, "setFont:");
    _objc_release(obj_242);
    _objc_release(obj_241);
    _objc_release(obj_240);
    id obj_243 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "heartBtn"));
    _objc_msgSend(obj_243, "addTarget:action:forControlEvents:");
    _objc_release(obj_243);
    id obj_244 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnerInner"));
    id obj_245 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "heartBtn"));
    _objc_msgSend(obj_244, "addSubview:");
    _objc_release(obj_245);
    _objc_release(obj_244);
    id obj_246 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:"));
    _objc_msgSend(self, "setRainBtn:", obj_246);
    _objc_release(obj_246);
    id obj_247;
    int128_t v0_139;
    int128_t v1_94;
    int128_t v2_77;
    int128_t v3_78;
    obj_247 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "rainBtn"));
    v0_139 = v14 + 14.0 + 8.0;
    v1_94 = 0x4085500000000000;
    v2_77 = v14;
    v3_78 = v13;
    _objc_msgSend(obj_247, "setFrame:");
    int128_t v0_140;
    int128_t v1_95;
    int128_t v2_78;
    int128_t v3_79;
    v0_140 = _objc_release(obj_247);
    v1_95 = 0.5;
    v3_79 = 1.0;
    v0_140 = 0x3fc3333333333333;
    v2_78 = 0x3fee666666666666;
    id obj_248 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    id obj_249 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "rainBtn"));
    _objc_msgSend(obj_249, "setBackgroundColor:");
    _objc_release(obj_249);
    _objc_release(obj_248);
    id obj_250 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "rainBtn"));
    id obj_251;
    int128_t v0_141;
    obj_251 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_250, "layer"));
    v0_141 = 12.0;
    _objc_msgSend(obj_251, "setCornerRadius:");
    _objc_release(obj_251);
    _objc_release(obj_250);
    id obj_252 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "rainBtn"));
    _objc_msgSend(obj_252, "setTitle:forState:");
    _objc_release(obj_252);
    id obj_253;
    int128_t v0_142;
    int128_t v1_96;
    int128_t v2_79;
    int128_t v3_80;
    obj_253 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "rainBtn"));
    v2_79 = 1.0;
    v3_80 = 1.0;
    v0_142 = 0x3feb333333333333;
    v1_96 = 0x3feccccccccccccd;
    id obj_254 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_253, "setTitleColor:forState:");
    _objc_release(obj_254);
    _objc_release(obj_253);
    int128_t v0_143;
    v0_143 = 13.0;
    id obj_255 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    id obj_256 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "rainBtn"));
    id obj_257 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_256, "titleLabel"));
    _objc_msgSend(obj_257, "setFont:");
    _objc_release(obj_257);
    _objc_release(obj_256);
    _objc_release(obj_255);
    id obj_258 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "rainBtn"));
    _objc_msgSend(obj_258, "addTarget:action:forControlEvents:");
    _objc_release(obj_258);
    id obj_259 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnerInner"));
    id obj_260 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "rainBtn"));
    _objc_msgSend(obj_259, "addSubview:");
    _objc_release(obj_260);
    _objc_release(obj_259);
    id x0_899;
    int128_t v0_144;
    int128_t v1_97;
    int128_t v2_80;
    int128_t v3_81;
    x0_899 = _objc_alloc(clsRef_UIView);
    v1_97 = 0x4086d00000000000;
    v9 = 0x4042000000000000;
    v0_144 = 14.0;
    v2_80 = v10;
    v3_81 = v9;
    id obj_261 = _objc_msgSend(x0_899, "initWithFrame:");
    _objc_msgSend(obj_261, "setTag:");
    id x0_901;
    int128_t v0_145;
    int128_t v1_98;
    int128_t v2_81;
    int128_t v3_82;
    x0_901 = _objc_alloc(clsRef_UILabel);
    v2_81 = 0x4061800000000000;
    v0_145 = 0.0;
    v1_98 = 0.0;
    v3_82 = v9;
    id obj_262 = _objc_msgSend(x0_901, "initWithFrame:");
    int128_t v0_146;
    int128_t v1_99;
    v0_146 = _objc_msgSend(obj_262, "setText:");
    v0_146 = 14.0;
    v1_99 = v1_1;
    id obj_263 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
        "systemFontOfSize:weight:"));
    _objc_msgSend(obj_262, "setFont:");
    int128_t v0_147;
    int128_t v1_100;
    int128_t v2_82;
    int128_t v3_83;
    v0_147 = _objc_release(obj_263);
    v2_82 = 1.0;
    v3_83 = 1.0;
    v0_147 = 0x3feb333333333333;
    v1_100 = 0x3feccccccccccccd;
    id obj_264 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_262, "setTextColor:");
    _objc_release(obj_264);
    _objc_msgSend(obj_261, "addSubview:");
    id x0_912;
    int128_t v0_148;
    int128_t v1_101;
    int128_t v2_83;
    int128_t v3_84;
    x0_912 = _objc_alloc(clsRef_UISwitch);
    v1_101 = 3.0;
    v3_84 = 31.0;
    v0_148 = var_440;
    v2_83 = 0x4049800000000000;
    int64_t obj_265 = _objc_msgSend(x0_912, "initWithFrame:");
    _objc_msgSend(self, "setHeartLoopSwitch:", obj_265);
    int128_t v0_149;
    int128_t v1_102;
    int128_t v2_84;
    int128_t v3_85;
    v0_149 = _objc_release(obj_265);
    v3_85 = 1.0;
    v0_149 = 0x3fe999999999999a;
    v1_102 = 0x3fc999999999999a;
    v2_84 = 0x3fd999999999999a;
    id obj_266 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    id obj_267 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "heartLoopSwitch"));
    _objc_msgSend(obj_267, "setOnTintColor:");
    _objc_release(obj_267);
    _objc_release(obj_266);
    id obj_268 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "heartLoopSwitch"));
    _objc_msgSend(obj_268, "addTarget:action:forControlEvents:");
    _objc_release(obj_268);
    id obj_269 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "heartLoopSwitch"));
    _objc_msgSend(obj_261, "addSubview:");
    _objc_release(obj_269);
    id obj_270 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnerInner"));
    _objc_msgSend(obj_270, "addSubview:");
    _objc_release(obj_270);
    id obj_271 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:"));
    _objc_msgSend(self, "setJsonBtn:", obj_271);
    _objc_release(obj_271);
    id obj_272;
    int128_t v0_150;
    int128_t v1_103;
    int128_t v2_85;
    int128_t v3_86;
    obj_272 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "jsonBtn"));
    v1_103 = 0x4088200000000000;
    v0_150 = 14.0;
    v2_85 = v10;
    v3_86 = v13;
    _objc_msgSend(obj_272, "setFrame:");
    int128_t v0_151;
    int128_t v1_104;
    int128_t v2_86;
    int128_t v3_87;
    v0_151 = _objc_release(obj_272);
    v3_87 = 1.0;
    v0_151 = 0x3fc999999999999a;
    v1_104 = 0x3fe3333333333333;
    v2_86 = 0x3fd3333333333333;
    id obj_273 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    id obj_274 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "jsonBtn"));
    _objc_msgSend(obj_274, "setBackgroundColor:");
    _objc_release(obj_274);
    _objc_release(obj_273);
    id obj_275 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "jsonBtn"));
    id obj_276;
    int128_t v0_152;
    obj_276 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_275, "layer"));
    v0_152 = 12.0;
    _objc_msgSend(obj_276, "setCornerRadius:");
    _objc_release(obj_276);
    _objc_release(obj_275);
    id obj_277 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "jsonBtn"));
    _objc_msgSend(obj_277, "setTitle:forState:");
    _objc_release(obj_277);
    id obj_278;
    int128_t v0_153;
    int128_t v1_105;
    int128_t v2_87;
    int128_t v3_88;
    obj_278 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "jsonBtn"));
    v2_87 = 1.0;
    v3_88 = 1.0;
    v0_153 = 0x3feb333333333333;
    v1_105 = 0x3feccccccccccccd;
    id obj_279 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_278, "setTitleColor:forState:");
    _objc_release(obj_279);
    _objc_release(obj_278);
    int128_t v0_154;
    v0_154 = 14.0;
    id obj_280 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    id obj_281 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "jsonBtn"));
    id obj_282 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_281, "titleLabel"));
    _objc_msgSend(obj_282, "setFont:");
    _objc_release(obj_282);
    _objc_release(obj_281);
    _objc_release(obj_280);
    id obj_283 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "jsonBtn"));
    _objc_msgSend(obj_283, "addTarget:action:forControlEvents:");
    _objc_release(obj_283);
    id obj_284 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnerInner"));
    id obj_285 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "jsonBtn"));
    _objc_msgSend(obj_284, "addSubview:");
    _objc_release(obj_285);
    _objc_release(obj_284);
    id x0_978;
    int128_t v0_155;
    int128_t v1_106;
    int128_t v2_88;
    int128_t v3_89;
    x0_978 = _objc_alloc(clsRef_UILabel);
    v1_106 = 0x4089a00000000000;
    v0_155 = 14.0;
    v3_89 = 18.0;
    v2_88 = v10;
    int64_t obj_286 = _objc_msgSend(x0_978, "initWithFrame:");
    _objc_msgSend(self, "setLocationLabel:", obj_286);
    _objc_release(obj_286);
    id obj_287 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "locationLabel"));
    _objc_msgSend(obj_287, "setText:");
    _objc_release(obj_287);
    int128_t v0_156;
    v0_156 = 11.0;
    id obj_288 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "systemFontOfSize:"));
    id obj_289 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "locationLabel"));
    _objc_msgSend(obj_289, "setFont:");
    _objc_release(obj_289);
    int128_t v0_157;
    int128_t v1_107;
    int128_t v2_89;
    int128_t v3_90;
    v0_157 = _objc_release(obj_288);
    v3_90 = 1.0;
    v0_157 = 0x3fdccccccccccccd;
    v2_89 = 0x3fe6666666666666;
    v1_107 = 0x3fe199999999999a;
    id obj_290 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    id obj_291 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "locationLabel"));
    _objc_msgSend(obj_291, "setTextColor:");
    _objc_release(obj_291);
    _objc_release(obj_290);
    id obj_292 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "locationLabel"));
    _objc_msgSend(obj_292, "setTextAlignment:");
    _objc_release(obj_292);
    id obj_293 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnerInner"));
    id obj_294 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "locationLabel"));
    _objc_msgSend(obj_293, "addSubview:");
    _objc_release(obj_294);
    _objc_release(obj_293);
    id x0_1007;
    int128_t v0_158;
    int128_t v1_108;
    int128_t v2_90;
    int128_t v3_91;
    x0_1007 = _objc_alloc(clsRef_UITextView);
    v1_108 = 0x408a500000000000;
    v3_91 = 0x4056800000000000;
    v0_158 = 14.0;
    v2_90 = v10;
    int64_t obj_295 = _objc_msgSend(x0_1007, "initWithFrame:");
    _objc_msgSend(self, "setLogView:", obj_295);
    int128_t v1_109;
    int128_t v2_91;
    int128_t v3_92;
    v1_109 = _objc_release(obj_295);
    v3_92 = 1.0;
    v1_109 = 0x3f947ae147ae147b;
    v2_91 = 0x3faeb851eb851eb8;
    id obj_296 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    id obj_297 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "logView"));
    _objc_msgSend(obj_297, "setBackgroundColor:");
    _objc_release(obj_297);
    _objc_release(obj_296);
    id obj_298 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "logView"));
    id obj_299;
    int128_t v0_159;
    obj_299 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_298, "layer"));
    v0_159 = 10.0;
    _objc_msgSend(obj_299, "setCornerRadius:");
    _objc_release(obj_299);
    _objc_release(obj_298);
    id obj_300 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "logView"));
    id obj_301;
    int128_t v0_160;
    obj_301 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_300, "layer"));
    v0_160 = 1.0;
    _objc_msgSend(obj_301, "setBorderWidth:");
    _objc_release(obj_301);
    int128_t v0_161;
    int128_t v1_110;
    v0_161 = _objc_release(obj_300);
    v1_110 = 1.0;
    v0_161 = 0x3fc3333333333333;
    id obj_302 = _objc_retainAutorelease(_objc_retainAutoreleasedReturnValue(_objc_msgSend(
        clsRef_UIColor, "colorWithWhite:alpha:")));
    _objc_msgSend(obj_302, "CGColor");
    id obj_303 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "logView"));
    id obj_304 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_303, "layer"));
    _objc_msgSend(obj_304, "setBorderColor:");
    _objc_release(obj_304);
    _objc_release(obj_303);
    int128_t v0_162;
    int128_t v1_111;
    int128_t v2_92;
    int128_t v3_93;
    v0_162 = _objc_release(obj_302);
    v3_93 = 1.0;
    v0_162 = 0x3fd3333333333333;
    v1_111 = 0x3feb333333333333;
    v2_92 = 0x3fee666666666666;
    id obj_305 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    id obj_306 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "logView"));
    _objc_msgSend(obj_306, "setTextColor:");
    _objc_release(obj_306);
    int64_t x3_41;
    int128_t v0_163;
    x3_41 = _objc_release(obj_305);
    v0_163 = 9.0;
    id obj_307 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
        "fontWithName:size:", &cfstr_Menlo, x3_41));
    id obj_308 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "logView"));
    _objc_msgSend(obj_308, "setFont:");
    _objc_release(obj_308);
    _objc_release(obj_307);
    id obj_309 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "logView"));
    id obj_310 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_309, "font"));
    _objc_release(obj_310);
    int128_t v0_164;
    int128_t v1_112;
    v0_164 = _objc_release(obj_309);
    
    if (!obj_310)
    {
        v0_164 = 9.0;
        v1_112 = v1_67;
        id obj_311 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
            "monospacedSystemFontOfSize:weight:"));
        id obj_312 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "logView"));
        _objc_msgSend(obj_312, "setFont:");
        _objc_release(obj_312);
        _objc_release(obj_311);
    }
    
    id obj_313 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "logView"));
    _objc_msgSend(obj_313, "setEditable:", 0);
    _objc_release(obj_313);
    data_446a78;
    id obj_314 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "logView"));
    _objc_msgSend(obj_314, "setText:");
    _objc_release(obj_314);
    id obj_315 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "logView"));
    _objc_storeWeak(&data_446a80, obj_315);
    _objc_release(obj_315);
    id obj_316 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnerInner"));
    id obj_317 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "logView"));
    _objc_msgSend(obj_316, "addSubview:");
    _objc_release(obj_317);
    _objc_release(obj_316);
    id x0_1075;
    int128_t v0_165;
    int128_t v1_113;
    int128_t v2_93;
    int128_t v3_94;
    x0_1075 = _objc_alloc(clsRef_UILabel);
    v1_113 = 0x408d500000000000;
    v0_165 = 14.0;
    v3_94 = 18.0;
    v2_93 = v10;
    id obj_318 = _objc_msgSend(x0_1075, "initWithFrame:");
    int128_t v0_166;
    int128_t v1_114;
    v0_166 = _objc_msgSend(obj_318, "setText:");
    v0_166 = 11.0;
    v1_114 = v1_1;
    id obj_319 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
        "systemFontOfSize:weight:"));
    _objc_msgSend(obj_318, "setFont:");
    int128_t v0_167;
    int128_t v1_115;
    int128_t v2_94;
    int128_t v3_95;
    v0_167 = _objc_release(obj_319);
    v1_115 = 0.5;
    v2_94 = 1.0;
    v3_95 = 1.0;
    v0_167 = 0x3fc999999999999a;
    id obj_320 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_318, "setTextColor:");
    _objc_release(obj_320);
    _objc_msgSend(obj_318, "setTextAlignment:");
    id obj_321 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnerInner"));
    _objc_msgSend(obj_321, "addSubview:");
    _objc_release(obj_321);
    id x0_1089;
    int128_t v0_168;
    int128_t v1_116;
    int128_t v2_95;
    int128_t v3_96;
    x0_1089 = _objc_alloc(clsRef_UILabel);
    v1_116 = 0x408e000000000000;
    v0_168 = 14.0;
    v3_96 = 16.0;
    v2_95 = v10;
    id obj_322 = _objc_msgSend(x0_1089, "initWithFrame:");
    int128_t v0_169;
    int128_t v1_117;
    v0_169 = _objc_msgSend(obj_322, "setText:");
    v0_169 = 10.0;
    v1_117 = v1_1;
    id obj_323 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
        "systemFontOfSize:weight:"));
    _objc_msgSend(obj_322, "setFont:");
    int128_t v0_170;
    int128_t v1_118;
    int128_t v2_96;
    int128_t v3_97;
    v0_170 = _objc_release(obj_323);
    v1_118 = 0.5;
    v3_97 = 1.0;
    v0_170 = 0x3fdccccccccccccd;
    v2_96 = 0x3fee666666666666;
    id obj_324 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_322, "setTextColor:");
    _objc_release(obj_324);
    _objc_msgSend(obj_322, "setTextAlignment:");
    id obj_325 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnerInner"));
    _objc_msgSend(obj_325, "addSubview:");
    _objc_release(obj_325);
    id obj_326;
    int128_t v0_171;
    int128_t v1_119;
    int128_t v2_97;
    int128_t v3_98;
    obj_326 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:"));
    v1_119 = 0x408e800000000000;
    v0_171 = 14.0;
    v3_98 = 18.0;
    v2_97 = v10;
    _objc_msgSend(obj_326, "setFrame:");
    int128_t v0_172;
    int128_t v1_120;
    int128_t v2_98;
    int128_t v3_99;
    v0_172 = _objc_msgSend(obj_326, "setTitle:forState:");
    v0_172 = 0x3fd6666666666666;
    v2_98 = 1.0;
    v3_99 = 1.0;
    v1_120 = 0x3fd999999999999a;
    id obj_327 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_326, "setTitleColor:forState:");
    int128_t v0_173;
    int128_t v1_121;
    v0_173 = _objc_release(obj_327);
    v0_173 = 11.0;
    v1_121 = v11;
    id obj_328 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
        "systemFontOfSize:weight:"));
    id obj_329 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_326, "titleLabel"));
    _objc_msgSend(obj_329, "setFont:");
    _objc_release(obj_329);
    _objc_release(obj_328);
    _objc_msgSend(obj_326, "addTarget:action:forControlEvents:");
    id obj_330 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnerInner"));
    _objc_msgSend(obj_330, "addSubview:");
    _objc_release(obj_330);
    id obj_331;
    int128_t v0_174;
    int128_t v1_122;
    int128_t v2_99;
    int128_t v3_100;
    obj_331 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnerInner"));
    v0_174 = 0.0;
    v1_122 = 0.0;
    v2_99 = v2;
    v3_100 = 0x408f500000000000;
    _objc_msgSend(obj_331, "setFrame:");
    _objc_release(obj_331);
    id obj_332;
    int64_t x2_269;
    int128_t v0_175;
    int128_t v1_123;
    obj_332 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnerScroll"));
    v0_175 = v2;
    v1_123 = 0x408f500000000000;
    _objc_msgSend(obj_332, "setContentSize:", x2_269);
    _objc_release(obj_332);
    _objc_release(obj_326);
    _objc_release(obj_322);
    _objc_release(obj_318);
    _objc_release(obj_262);
    _objc_release(obj_261);
    _objc_release(obj_215);
    _objc_release(obj_207);
    _objc_release(obj_203);
    _objc_release(obj_201);
    _objc_release(obj_199);
    _objc_release(obj_196);
    _objc_release(obj_194);
    _objc_release(obj_190);
    _objc_release(obj_181);
    _objc_release(obj_174);
    _objc_release(obj_168);
    _objc_release(obj_159);
    _objc_release(obj_155);
    _objc_release(obj_144);
    _objc_release(obj_140);
    _objc_release(obj_129);
    _objc_release(obj_116);
    _objc_release(obj_113);
    _objc_release(obj_107);
    _objc_release(obj_99);
    _objc_release(obj_98);
    _objc_release(obj_91);
    _objc_release(obj_85);
    _objc_release(obj_73);
    _objc_release(obj_67);
    _objc_release(obj_19);
    _objc_release(obj_18);
    _objc_release(obj);
    _objc_release(obj_1);
    _objc_release(obj_3);
    
    if (*___stack_chk_guard == x8)
        return;
    
    ___stack_chk_fail();
    /* no return */
}

void -[ACPanelController buildSettingsContent](struct ACPanelController* self, SEL sel)
{
    double v15;
    double var_a0 = v15;
    double v14;
    double var_98 = v14;
    double v12;
    double var_88 = v12;
    double v11;
    double var_80 = v11;
    double v10;
    double var_78 = v10;
    double v9;
    double var_70 = v9;
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "settingsContent"));
    double v2 = _objc_msgSend(obj, "bounds");
    _objc_release(obj);
    id x0_3;
    int64_t x2;
    int128_t v1;
    int128_t v3;
    x0_3 = _objc_alloc(clsRef_UILabel);
    double v2_1 = v2 + -28.0;
    v1 = 10.0;
    v3 = 26.0;
    id x0_4 = _objc_msgSend(x0_3, "initWithFrame:", x2);
    int64_t x2_1;
    int128_t v0_1;
    x2_1 = _objc_msgSend(x0_4, "setText:", &cfstr_Preset_Locations);
    v0_1 = 16.0;
    id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
        "boldSystemFontOfSize:", x2_1));
    _objc_msgSend(x0_4, "setFont:", obj_1);
    int64_t x2_3;
    int64_t x3;
    int64_t x4;
    int64_t x5;
    int128_t v3_1;
    x2_3 = _objc_release(obj_1);
    v3_1 = 1.0;
    id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:", x2_3, x3, x4, x5));
    _objc_msgSend(x0_4, "setTextColor:", obj_2);
    _objc_release(obj_2);
    id obj_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "settingsContent"));
    _objc_msgSend(obj_3, "addSubview:", x0_4);
    _objc_release(obj_3);
    double v8;
    
    if (_objc_msgSend(data_4469d0, "count") <= 0)
        v8 = 0x404a000000000000;
    else
    {
        int64_t x27_1 = 0;
        v9 = *_UIFontWeightMedium;
        v10 = 0x4045000000000000;
        int64_t x0_48;
        
        do
        {
            id obj_4;
            int128_t v0_2;
            int128_t v1_1;
            int128_t v2_2;
            int128_t v3_2;
            obj_4 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, 
                "buttonWithType:"));
            v3_2 = 0x4043000000000000;
            v0_2 = 14.0;
            v1_1 = v10;
            v2_2 = v2_1;
            int64_t x2_7;
            int64_t x3_1;
            int64_t x4_1;
            int64_t x5_1;
            int128_t v0_3;
            int128_t v1_2;
            int128_t v2_3;
            int128_t v3_3;
            x2_7 = _objc_msgSend(obj_4, "setFrame:");
            
            if (x27_1 != data_446768)
            {
                v3_3 = 1.0;
                v1_2 = 0x3fa47ae147ae147b;
                v0_3 = 0x3fa999999999999a;
                v2_3 = 0x3fc1eb851eb851ec;
            }
            else
            {
                v1_2 = 0.25;
                v3_3 = 1.0;
                v0_3 = 0x3fb999999999999a;
                v2_3 = 0x3fe199999999999a;
            }
            
            id obj_5 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
                "colorWithRed:green:blue:alpha:", x2_7, x3_1, x4_1, x5_1));
            _objc_msgSend(obj_4, "setBackgroundColor:");
            _objc_release(obj_5);
            id obj_6;
            int128_t v0_4;
            obj_6 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_4, "layer"));
            v0_4 = 10.0;
            _objc_msgSend(obj_6, "setCornerRadius:");
            _objc_release(obj_6);
            id obj_7 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(data_4469d0, 
                "objectAtIndexedSubscript:"));
            _objc_msgSend(obj_4, "setTitle:forState:");
            int64_t x2_11;
            int64_t x3_3;
            int64_t x4_2;
            int64_t x5_2;
            int128_t v0_5;
            int128_t v1_3;
            int128_t v2_4;
            int128_t v3_4;
            x2_11 = _objc_release(obj_7);
            
            if (x27_1 != data_446768)
            {
                v2_4 = 1.0;
                v3_4 = 1.0;
                v0_5 = 0x3feb333333333333;
                v1_3 = 0x3feccccccccccccd;
            }
            else
            {
                v3_4 = 1.0;
                v0_5 = 0x3fb999999999999a;
                v1_3 = 0x3fe999999999999a;
                v2_4 = 0x3fee666666666666;
            }
            
            id obj_8 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
                "colorWithRed:green:blue:alpha:", x2_11, x3_3, x4_2, x5_2));
            _objc_msgSend(obj_4, "setTitleColor:forState:");
            int128_t v0_6;
            int128_t v1_4;
            v0_6 = _objc_release(obj_8);
            v0_6 = 13.0;
            v1_4 = v9;
            id obj_9 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
                "systemFontOfSize:weight:"));
            id obj_10 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_4, "titleLabel"));
            _objc_msgSend(obj_10, "setFont:");
            _objc_release(obj_10);
            _objc_release(obj_9);
            _objc_msgSend(obj_4, "setTag:", x27_1 + 0x7d0);
            _objc_msgSend(obj_4, "addTarget:action:forControlEvents:", self, "presetTapped:", 0x40);
            id obj_11 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "settingsContent"));
            _objc_msgSend(obj_11, "addSubview:");
            _objc_release(obj_11);
            v10 = v10 + 0x4045000000000000;
            _objc_release(obj_4);
            x0_48 = _objc_msgSend(data_4469d0, "count");
            x27_1 += 1;
        } while (x27_1 < x0_48);
        v8 = v10 + 10.0;
    }
    
    id obj_12;
    int128_t v0_9;
    int128_t v1_5;
    int128_t v2_5;
    int128_t v3_5;
    obj_12 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:"));
    v11 = 0x4045000000000000;
    v0_9 = 14.0;
    v1_5 = v8;
    v2_5 = v2_1;
    v3_5 = v11;
    double var_1b0 = v11;
    int64_t x2_18;
    int64_t x3_5;
    int64_t x4_3;
    int64_t x5_3;
    int128_t v1_6;
    int128_t v2_6;
    int128_t v3_6;
    x2_18 = _objc_msgSend(obj_12, "setFrame:");
    v3_6 = 1.0;
    v1_6 = 0x3fd999999999999a;
    v2_6 = 0x3feccccccccccccd;
    id obj_13 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:", x2_18, x3_5, x4_3, x5_3));
    _objc_msgSend(obj_12, "setBackgroundColor:");
    _objc_release(obj_13);
    id obj_14;
    int128_t v0_10;
    obj_14 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_12, "layer"));
    v0_10 = 12.0;
    _objc_msgSend(obj_14, "setCornerRadius:");
    _objc_release(obj_14);
    int64_t x2_21;
    int64_t x3_7;
    int64_t x4_4;
    int64_t x5_4;
    int128_t v0_11;
    int128_t v1_7;
    int128_t v2_7;
    int128_t v3_7;
    x2_21 = _objc_msgSend(obj_12, "setTitle:forState:");
    v2_7 = 1.0;
    v3_7 = 1.0;
    v0_11 = 0x3feb333333333333;
    v1_7 = 0x3feccccccccccccd;
    id obj_15 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:", x2_21, x3_7, x4_4, x5_4));
    _objc_msgSend(obj_12, "setTitleColor:forState:");
    _objc_release(obj_15);
    int128_t v0_12;
    v0_12 = 14.0;
    id obj_16 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    id obj_17 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_12, "titleLabel"));
    _objc_msgSend(obj_17, "setFont:");
    _objc_release(obj_17);
    _objc_release(obj_16);
    int64_t self_1 = self;
    _objc_msgSend(obj_12, "addTarget:action:forControlEvents:", self_1, "usePlayerPosition", 0x40);
    id obj_18 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self_1, "settingsContent"));
    _objc_msgSend(obj_18, "addSubview:");
    _objc_release(obj_18);
    v10 = 0x4049000000000000;
    v8 = v8 + v10;
    id x0_74;
    int128_t v0_13;
    int128_t v1_8;
    int128_t v2_8;
    int128_t v3_8;
    x0_74 = _objc_alloc(clsRef_UILabel);
    v0_13 = 14.0;
    v3_8 = 26.0;
    v1_8 = v8;
    v2_8 = v2_1;
    id obj_19 = _objc_msgSend(x0_74, "initWithFrame:");
    _objc_msgSend(obj_19, "setText:");
    int128_t v0_14;
    v0_14 = 16.0;
    id obj_20 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    _objc_msgSend(obj_19, "setFont:");
    int64_t x2_28;
    int64_t x3_9;
    int64_t x4_5;
    int64_t x5_5;
    int128_t v0_15;
    int128_t v1_9;
    int128_t v2_9;
    int128_t v3_9;
    x2_28 = _objc_release(obj_20);
    v3_9 = 1.0;
    v0_15 = 0x3fd999999999999a;
    v1_9 = 0x3fc999999999999a;
    v2_9 = 0x3fee666666666666;
    id obj_21 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:", x2_28, x3_9, x4_5, x5_5));
    _objc_msgSend(obj_19, "setTextColor:");
    _objc_release(obj_21);
    id obj_22 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self_1, "settingsContent"));
    _objc_msgSend(obj_22, "addSubview:");
    _objc_release(obj_22);
    v8 = v8 + 30.0;
    id obj_23;
    int128_t v0_17;
    int128_t v1_10;
    int128_t v2_10;
    int128_t v3_10;
    obj_23 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:"));
    v0_17 = 14.0;
    v1_10 = v8;
    v2_10 = v2_1;
    v3_10 = v11;
    int64_t x2_32;
    int64_t x3_10;
    int64_t x4_6;
    int64_t x5_6;
    int128_t v0_18;
    int128_t v1_11;
    int128_t v2_11;
    int128_t v3_11;
    x2_32 = _objc_msgSend(obj_23, "setFrame:");
    v1_11 = 0.5;
    v3_11 = 1.0;
    v0_18 = 0x3fc999999999999a;
    v2_11 = 0x3fe6666666666666;
    id obj_24 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:", x2_32, x3_10, x4_6, x5_6));
    _objc_msgSend(obj_23, "setBackgroundColor:");
    _objc_release(obj_24);
    id obj_25;
    int128_t v0_19;
    obj_25 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_23, "layer"));
    v0_19 = 12.0;
    _objc_msgSend(obj_25, "setCornerRadius:");
    _objc_release(obj_25);
    int64_t x2_35;
    int64_t x3_12;
    int64_t x4_7;
    int64_t x5_7;
    int128_t v0_20;
    int128_t v1_12;
    int128_t v2_12;
    int128_t v3_12;
    x2_35 = _objc_msgSend(obj_23, "setTitle:forState:");
    v2_12 = 1.0;
    v3_12 = 1.0;
    v0_20 = 0x3feb333333333333;
    v1_12 = 0x3feccccccccccccd;
    id obj_26 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:", x2_35, x3_12, x4_7, x5_7));
    _objc_msgSend(obj_23, "setTitleColor:forState:");
    _objc_release(obj_26);
    int128_t v0_21;
    v0_21 = 13.0;
    id obj_27 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    id obj_28 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_23, "titleLabel"));
    _objc_msgSend(obj_28, "setFont:");
    _objc_release(obj_28);
    _objc_release(obj_27);
    _objc_msgSend(obj_23, "addTarget:action:forControlEvents:");
    id obj_29 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "settingsContent"));
    _objc_msgSend(obj_29, "addSubview:");
    _objc_release(obj_29);
    v14 = v8 + v10;
    id x0_111;
    int128_t v0_22;
    int128_t v1_13;
    int128_t v2_13;
    int128_t v3_13;
    x0_111 = _objc_alloc(clsRef_UILabel);
    v0_22 = 14.0;
    v3_13 = 22.0;
    v1_13 = v14;
    v2_13 = v2_1;
    id obj_30 = _objc_msgSend(x0_111, "initWithFrame:");
    int64_t x2_41;
    int64_t x3_15;
    int128_t v0_23;
    int128_t v1_14;
    x2_41 = _objc_msgSend(obj_30, "setText:");
    v11 = *_UIFontWeightMedium;
    v0_23 = 12.0;
    v1_14 = v11;
    id obj_31 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
        "systemFontOfSize:weight:", x2_41, x3_15));
    _objc_msgSend(obj_30, "setFont:");
    int64_t x2_43;
    int64_t x3_16;
    int64_t x4_9;
    int64_t x5_8;
    int128_t v0_24;
    int128_t v1_15;
    int128_t v2_14;
    int128_t v3_14;
    x2_43 = _objc_release(obj_31);
    v3_14 = 1.0;
    v0_24 = 0x3fdccccccccccccd;
    v1_15 = 0x3fe199999999999a;
    v2_14 = 0x3fe6666666666666;
    id obj_32 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:", x2_43, x3_16, x4_9, x5_8));
    _objc_msgSend(obj_30, "setTextColor:");
    _objc_release(obj_32);
    _objc_msgSend(obj_30, "setTag:", 0x834);
    id obj_33 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "settingsContent"));
    _objc_msgSend(obj_33, "addSubview:");
    _objc_release(obj_33);
    v12 = 24.0;
    v14 = v14 + v12;
    id x0_125;
    int128_t v0_25;
    int128_t v1_16;
    int128_t v2_15;
    int128_t v3_15;
    x0_125 = _objc_alloc(clsRef_UIView);
    v15 = 0x4069000000000000;
    v0_25 = 14.0;
    v1_16 = v14;
    v2_15 = v2_1;
    v3_15 = v15;
    id obj_34 = _objc_msgSend(x0_125, "initWithFrame:");
    _objc_msgSend(obj_34, "setTag:", 0x898);
    id obj_35 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "settingsContent"));
    _objc_msgSend(obj_35, "addSubview:");
    _objc_release(obj_35);
    v14 = v14 + v15;
    id x0_130;
    int128_t v0_26;
    int128_t v1_17;
    int128_t v2_16;
    int128_t v3_16;
    x0_130 = _objc_alloc(clsRef_UILabel);
    v0_26 = 14.0;
    v3_16 = 26.0;
    v1_17 = v14;
    v2_16 = v2_1;
    id obj_36 = _objc_msgSend(x0_130, "initWithFrame:");
    _objc_msgSend(obj_36, "setText:");
    int128_t v0_27;
    v0_27 = 16.0;
    id obj_37 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    _objc_msgSend(obj_36, "setFont:");
    int64_t x2_49;
    int64_t x3_17;
    int64_t x4_10;
    int64_t x5_9;
    int128_t v0_28;
    int128_t v1_18;
    int128_t v2_17;
    int128_t v3_17;
    x2_49 = _objc_release(obj_37);
    v3_17 = 1.0;
    v0_28 = 0x3fd999999999999a;
    v1_18 = 0x3fc999999999999a;
    v2_17 = 0x3fee666666666666;
    id obj_38 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:", x2_49, x3_17, x4_10, x5_9));
    _objc_msgSend(obj_36, "setTextColor:");
    _objc_release(obj_38);
    id obj_39 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "settingsContent"));
    _objc_msgSend(obj_39, "addSubview:");
    _objc_release(obj_39);
    v14 = v14 + 30.0;
    id x0_143;
    int128_t v0_30;
    int128_t v1_19;
    int128_t v2_18;
    int128_t v3_18;
    x0_143 = _objc_alloc(clsRef_UILabel);
    v0_30 = 14.0;
    v3_18 = 20.0;
    v1_19 = v14;
    v2_18 = v2_1;
    id obj_40 = _objc_msgSend(x0_143, "initWithFrame:");
    int128_t v0_31;
    int128_t v1_20;
    v0_31 = _objc_msgSend(obj_40, "setText:");
    v0_31 = 11.0;
    v1_20 = v11;
    id obj_41 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
        "systemFontOfSize:weight:"));
    _objc_msgSend(obj_40, "setFont:");
    int128_t v0_32;
    int128_t v1_21;
    int128_t v2_19;
    int128_t v3_19;
    v0_32 = _objc_release(obj_41);
    v3_19 = 1.0;
    v0_32 = 0x3fdccccccccccccd;
    v1_21 = 0x3fe199999999999a;
    v2_19 = 0x3fe6666666666666;
    id obj_42 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_40, "setTextColor:");
    _objc_release(obj_42);
    _objc_msgSend(obj_40, "setTag:");
    id obj_43 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "settingsContent"));
    _objc_msgSend(obj_43, "addSubview:");
    _objc_release(obj_43);
    v8 = v14 + v12;
    id obj_44;
    int128_t v0_33;
    int128_t v1_22;
    int128_t v2_20;
    int128_t v3_20;
    obj_44 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:"));
    v0_33 = 14.0;
    v1_22 = v8;
    v2_20 = v2_1;
    v3_20 = var_1b0;
    int128_t v0_34;
    int128_t v1_23;
    int128_t v2_21;
    int128_t v3_21;
    v0_34 = _objc_msgSend(obj_44, "setFrame:");
    v1_23 = 0.5;
    v3_21 = 1.0;
    v0_34 = 0x3fc999999999999a;
    v2_21 = 0x3fe6666666666666;
    id obj_45 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_44, "setBackgroundColor:");
    _objc_release(obj_45);
    id obj_46;
    int128_t v0_35;
    obj_46 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_44, "layer"));
    v0_35 = 12.0;
    _objc_msgSend(obj_46, "setCornerRadius:");
    _objc_release(obj_46);
    int128_t v0_36;
    int128_t v1_24;
    int128_t v2_22;
    int128_t v3_22;
    v0_36 = _objc_msgSend(obj_44, "setTitle:forState:");
    v2_22 = 1.0;
    v3_22 = 1.0;
    v0_36 = 0x3feb333333333333;
    v1_24 = 0x3feccccccccccccd;
    id obj_47 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_44, "setTitleColor:forState:");
    _objc_release(obj_47);
    int128_t v0_37;
    v0_37 = 13.0;
    id obj_48 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    id obj_49 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_44, "titleLabel"));
    _objc_msgSend(obj_49, "setFont:");
    _objc_release(obj_49);
    _objc_release(obj_48);
    _objc_msgSend(obj_44, "addTarget:action:forControlEvents:");
    id obj_50 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "settingsContent"));
    _objc_msgSend(obj_50, "addSubview:");
    _objc_release(obj_50);
    v9 = 0x4048000000000000;
    v8 = v8 + v9;
    id obj_51;
    int128_t v0_38;
    int128_t v1_25;
    int128_t v2_23;
    int128_t v3_23;
    obj_51 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:"));
    v0_38 = 14.0;
    v1_25 = v8;
    v2_23 = v2_1;
    v3_23 = var_1b0;
    int128_t v0_39;
    int128_t v1_26;
    int128_t v2_24;
    int128_t v3_24;
    v0_39 = _objc_msgSend(obj_51, "setFrame:");
    v2_24 = 0x3fd3333333333333;
    v3_24 = 1.0;
    v0_39 = 0x3fc3333333333333;
    v1_26 = 0x3fe199999999999a;
    id obj_52 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_51, "setBackgroundColor:");
    _objc_release(obj_52);
    id obj_53;
    int128_t v0_40;
    obj_53 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_51, "layer"));
    v0_40 = 12.0;
    _objc_msgSend(obj_53, "setCornerRadius:");
    _objc_release(obj_53);
    int128_t v0_41;
    int128_t v1_27;
    int128_t v2_25;
    int128_t v3_25;
    v0_41 = _objc_msgSend(obj_51, "setTitle:forState:");
    v2_25 = 1.0;
    v3_25 = 1.0;
    v0_41 = 0x3feb333333333333;
    v1_27 = 0x3feccccccccccccd;
    id obj_54 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_51, "setTitleColor:forState:");
    _objc_release(obj_54);
    int128_t v0_42;
    v0_42 = 13.0;
    id obj_55 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    id obj_56 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_51, "titleLabel"));
    _objc_msgSend(obj_56, "setFont:");
    _objc_release(obj_56);
    _objc_release(obj_55);
    _objc_msgSend(obj_51, "addTarget:action:forControlEvents:");
    id obj_57 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "settingsContent"));
    _objc_msgSend(obj_57, "addSubview:");
    _objc_release(obj_57);
    v8 = v8 + v9;
    id obj_58;
    int128_t v0_43;
    int128_t v1_28;
    int128_t v2_26;
    int128_t v3_26;
    obj_58 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:"));
    v0_43 = 14.0;
    v1_28 = v8;
    v2_26 = v2_1;
    v3_26 = var_1b0;
    int128_t v0_44;
    int128_t v1_29;
    int128_t v2_27;
    int128_t v3_27;
    v0_44 = _objc_msgSend(obj_58, "setFrame:");
    v0_44 = 0x3fe3333333333333;
    v2_27 = 0x3fb999999999999a;
    v1_29 = 0.25;
    v3_27 = 1.0;
    id obj_59 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_58, "setBackgroundColor:");
    _objc_release(obj_59);
    id obj_60;
    int128_t v0_45;
    obj_60 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_58, "layer"));
    v0_45 = 12.0;
    _objc_msgSend(obj_60, "setCornerRadius:");
    _objc_release(obj_60);
    int128_t v0_46;
    int128_t v1_30;
    int128_t v2_28;
    int128_t v3_28;
    v0_46 = _objc_msgSend(obj_58, "setTitle:forState:");
    v2_28 = 1.0;
    v3_28 = 1.0;
    v0_46 = 0x3feb333333333333;
    v1_30 = 0x3feccccccccccccd;
    id obj_61 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_58, "setTitleColor:forState:");
    _objc_release(obj_61);
    int128_t v0_47;
    v0_47 = 13.0;
    id obj_62 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    id obj_63 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_58, "titleLabel"));
    _objc_msgSend(obj_63, "setFont:");
    _objc_release(obj_63);
    _objc_release(obj_62);
    _objc_msgSend(obj_58, "addTarget:action:forControlEvents:");
    id obj_64 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "settingsContent"));
    _objc_msgSend(obj_64, "addSubview:");
    _objc_release(obj_64);
    v8 = v8 + 0x404c000000000000;
    id x0_229;
    int128_t v0_49;
    int128_t v1_31;
    int128_t v2_29;
    int128_t v3_29;
    x0_229 = _objc_alloc(clsRef_UILabel);
    v0_49 = 14.0;
    v3_29 = 18.0;
    v1_31 = v8;
    v2_29 = v2_1;
    id obj_65 = _objc_msgSend(x0_229, "initWithFrame:");
    int128_t v0_50;
    int128_t v1_32;
    v0_50 = _objc_msgSend(obj_65, "setText:");
    v0_50 = 11.0;
    v1_32 = v11;
    id obj_66 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
        "systemFontOfSize:weight:"));
    _objc_msgSend(obj_65, "setFont:");
    int128_t v0_51;
    int128_t v1_33;
    int128_t v2_30;
    int128_t v3_30;
    v0_51 = _objc_release(obj_66);
    v1_33 = 0.5;
    v2_30 = 1.0;
    v3_30 = 1.0;
    v0_51 = 0x3fc999999999999a;
    id obj_67 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_65, "setTextColor:");
    _objc_release(obj_67);
    _objc_msgSend(obj_65, "setTextAlignment:", 1);
    id obj_68 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "settingsContent"));
    _objc_msgSend(obj_68, "addSubview:");
    _objc_release(obj_68);
    id obj_69;
    int128_t v0_52;
    int128_t v1_34;
    int128_t v2_31;
    int128_t v3_31;
    obj_69 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:"));
    v0_52 = 14.0;
    v3_31 = 18.0;
    v1_34 = v8 + 18.0;
    v2_31 = v2_1;
    _objc_msgSend(obj_69, "setFrame:");
    int128_t v0_53;
    int128_t v1_35;
    int128_t v2_32;
    int128_t v3_32;
    v0_53 = _objc_msgSend(obj_69, "setTitle:forState:");
    v0_53 = 0x3fd6666666666666;
    v2_32 = 1.0;
    v3_32 = 1.0;
    v1_35 = 0x3fd999999999999a;
    id obj_70 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_69, "setTitleColor:forState:");
    int128_t v0_54;
    int128_t v1_36;
    v0_54 = _objc_release(obj_70);
    v1_36 = *_UIFontWeightBold;
    v0_54 = 11.0;
    id obj_71 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
        "systemFontOfSize:weight:"));
    id obj_72 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_69, "titleLabel"));
    _objc_msgSend(obj_72, "setFont:");
    _objc_release(obj_72);
    _objc_release(obj_71);
    _objc_msgSend(obj_69, "addTarget:action:forControlEvents:");
    id obj_73 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "settingsContent"));
    _objc_msgSend(obj_73, "addSubview:");
    _objc_release(obj_73);
    _objc_release(obj_69);
    _objc_release(obj_65);
    _objc_release(obj_58);
    _objc_release(obj_51);
    _objc_release(obj_44);
    _objc_release(obj_40);
    _objc_release(obj_36);
    _objc_release(obj_34);
    _objc_release(obj_30);
    _objc_release(obj_23);
    _objc_release(obj_19);
    _objc_release(obj_12);
    /* tailcall */
    return _objc_release(x0_4);
}

void -[ACPanelController buildAdminContent](struct ACPanelController* self, SEL sel)
{
    int64_t x8 = *___stack_chk_guard;
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminInner"));
    double v2 = _objc_msgSend(obj, "bounds");
    _objc_release(obj);
    id x0_3;
    int64_t x2;
    int128_t v1;
    int128_t v2_1;
    int128_t v3;
    x0_3 = _objc_alloc(clsRef_UILabel);
    double v9 = v2 + -28.0;
    v1 = 10.0;
    v3 = 26.0;
    v2_1 = v9;
    id obj_1 = _objc_msgSend(x0_3, "initWithFrame:", x2);
    int64_t x2_1;
    int128_t v0_1;
    x2_1 = _objc_msgSend(obj_1, "setText:", &cfstr_??_Admin_Panel);
    v0_1 = 16.0;
    id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
        "boldSystemFontOfSize:", x2_1));
    _objc_msgSend(obj_1, "setFont:", obj_2);
    int64_t x2_3;
    int64_t x3;
    int64_t x4;
    int64_t x5;
    int128_t v1_1;
    int128_t v2_2;
    int128_t v3_1;
    x2_3 = _objc_release(obj_2);
    v3_1 = 1.0;
    v1_1 = 0x3fc999999999999a;
    v2_2 = 0x3fc999999999999a;
    id obj_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:", x2_3, x3, x4, x5));
    _objc_msgSend(obj_1, "setTextColor:", obj_3);
    _objc_release(obj_3);
    id obj_4 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminInner"));
    _objc_msgSend(obj_4, "addSubview:", obj_1);
    _objc_release(obj_4);
    id x0_16;
    int64_t x2_6;
    int128_t v0_2;
    int128_t v1_2;
    int128_t v2_3;
    int128_t v3_2;
    x0_16 = _objc_alloc(clsRef_UILabel);
    v1_2 = 0x4045000000000000;
    v0_2 = 14.0;
    v3_2 = 22.0;
    v2_3 = v9;
    id obj_5 = _objc_msgSend(x0_16, "initWithFrame:", x2_6);
    int64_t x2_7;
    int64_t x3_1;
    int128_t v0_3;
    x2_7 = _objc_msgSend(obj_5, "setText:", &cfstr_Welcome,_Admin!);
    double v1_3 = *_UIFontWeightMedium;
    v0_3 = 14.0;
    id obj_6 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
        "systemFontOfSize:weight:", x2_7, x3_1));
    _objc_msgSend(obj_5, "setFont:", obj_6);
    int64_t x2_9;
    int64_t x3_2;
    int64_t x4_1;
    int64_t x5_1;
    int128_t v2_4;
    int128_t v3_3;
    x2_9 = _objc_release(obj_6);
    v3_3 = 1.0;
    v2_4 = 0x3fee666666666666;
    id obj_7 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:", x2_9, x3_2, x4_1, x5_1));
    _objc_msgSend(obj_5, "setTextColor:", obj_7);
    _objc_release(obj_7);
    _objc_msgSend(obj_5, "setTag:", 0x37b);
    id obj_8 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminInner"));
    _objc_msgSend(obj_8, "addSubview:", obj_5);
    _objc_release(obj_8);
    id x0_30;
    int64_t x2_12;
    int128_t v0_4;
    int128_t v1_4;
    int128_t v2_5;
    int128_t v3_4;
    x0_30 = _objc_alloc(clsRef_UILabel);
    v1_4 = 0x4052000000000000;
    v0_4 = 14.0;
    v3_4 = 22.0;
    v2_5 = v9;
    id obj_9 = _objc_msgSend(x0_30, "initWithFrame:", x2_12);
    _objc_msgSend(obj_9, "setText:", &cfstr_??_AI_Spawn_Assistant);
    int128_t v0_5;
    v0_5 = 14.0;
    id obj_10 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    _objc_msgSend(obj_9, "setFont:", obj_10);
    int64_t x2_14;
    int64_t x3_3;
    int64_t x4_2;
    int64_t x5_2;
    int128_t v0_6;
    int128_t v1_5;
    int128_t v2_6;
    int128_t v3_5;
    x2_14 = _objc_release(obj_10);
    v3_5 = 1.0;
    v0_6 = 0x3fd999999999999a;
    v1_5 = 0x3fc999999999999a;
    v2_6 = 0x3fee666666666666;
    id obj_11 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:", x2_14, x3_3, x4_2, x5_2));
    _objc_msgSend(obj_9, "setTextColor:", obj_11);
    _objc_release(obj_11);
    id obj_12 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminInner"));
    _objc_msgSend(obj_12, "addSubview:", obj_9);
    _objc_release(obj_12);
    id x0_43;
    int128_t v0_7;
    int128_t v1_6;
    int128_t v2_7;
    int128_t v3_6;
    x0_43 = _objc_alloc(clsRef_UILabel);
    v1_6 = 0x4058800000000000;
    v3_6 = 0x4042000000000000;
    v0_7 = 14.0;
    v2_7 = v9;
    int64_t obj_13 = _objc_msgSend(x0_43, "initWithFrame:");
    int64_t x2_17;
    int128_t v0_8;
    x2_17 = _objc_msgSend(obj_13, "setText:", 
        &cfstr_Type:_Hey_AI_spawn_[item]_[quantity]\nExample:_Hey_AI_spawn_item_goldbar_10);
    v0_8 = 10.0;
    id obj_14 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
        "systemFontOfSize:", x2_17));
    _objc_msgSend(obj_13, "setFont:", obj_14);
    int64_t x2_19;
    int64_t x3_4;
    int64_t x4_3;
    int64_t x5_3;
    int128_t v0_9;
    int128_t v1_7;
    int128_t v2_8;
    int128_t v3_7;
    x2_19 = _objc_release(obj_14);
    v3_7 = 1.0;
    v0_9 = 0x3fdccccccccccccd;
    v1_7 = 0x3fe199999999999a;
    v2_8 = 0x3fe6666666666666;
    id obj_15 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:", x2_19, x3_4, x4_3, x5_3));
    _objc_msgSend(obj_13, "setTextColor:", obj_15);
    _objc_release(obj_15);
    _objc_msgSend(obj_13, "setNumberOfLines:", 2);
    id obj_16 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminInner"));
    _objc_msgSend(obj_16, "addSubview:", obj_13);
    _objc_release(obj_16);
    id x0_57;
    int128_t v0_10;
    int128_t v1_8;
    int128_t v2_9;
    int128_t v3_8;
    x0_57 = _objc_alloc(clsRef_UITextField);
    v1_8 = 0x4061400000000000;
    double v15 = 0x4044000000000000;
    v0_10 = 14.0;
    v2_9 = v9;
    v3_8 = v15;
    id obj_17;
    int64_t x2_22;
    int64_t x3_5;
    int64_t x4_4;
    int64_t x5_4;
    int128_t v1_9;
    int128_t v3_9;
    obj_17 = _objc_msgSend(x0_57, "initWithFrame:");
    v3_9 = 1.0;
    v1_9 = 0x3fa47ae147ae147b;
    id obj_18 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:", x2_22, x3_5, x4_4, x5_4));
    _objc_msgSend(obj_17, "setBackgroundColor:", obj_18);
    _objc_release(obj_18);
    id obj_19;
    int64_t x2_24;
    int128_t v0_11;
    obj_19 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_17, "layer"));
    v0_11 = 10.0;
    _objc_msgSend(obj_19, "setCornerRadius:", x2_24);
    _objc_release(obj_19);
    id obj_20;
    int64_t x2_25;
    int128_t v0_12;
    obj_20 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_17, "layer"));
    v0_12 = 1.0;
    _objc_msgSend(obj_20, "setBorderWidth:", x2_25);
    int64_t x2_26;
    int64_t x3_6;
    int64_t x4_5;
    int64_t x5_5;
    int128_t v0_13;
    int128_t v1_10;
    int128_t v2_10;
    int128_t v3_10;
    x2_26 = _objc_release(obj_20);
    v3_10 = 1.0;
    v0_13 = 0x3fd999999999999a;
    v1_10 = 0x3fc999999999999a;
    v2_10 = 0x3fee666666666666;
    id obj_21 = _objc_retainAutorelease(_objc_retainAutoreleasedReturnValue(_objc_msgSend(
        clsRef_UIColor, "colorWithRed:green:blue:alpha:", x2_26, x3_6, x4_5, x5_5)));
    id x0_71 = _objc_msgSend(obj_21, "CGColor");
    id obj_22 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_17, "layer"));
    _objc_msgSend(obj_22, "setBorderColor:", x0_71);
    _objc_release(obj_22);
    int64_t x2_28;
    int64_t x3_7;
    int64_t x4_6;
    int64_t x5_6;
    int128_t v0_14;
    int128_t v1_11;
    int128_t v2_11;
    int128_t v3_11;
    x2_28 = _objc_release(obj_21);
    v2_11 = 1.0;
    v3_11 = 1.0;
    v0_14 = 0x3feb333333333333;
    v1_11 = 0x3feccccccccccccd;
    id obj_23 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:", x2_28, x3_7, x4_6, x5_6));
    _objc_msgSend(obj_17, "setTextColor:", obj_23);
    _objc_release(obj_23);
    int128_t v0_15;
    v0_15 = 13.0;
    id obj_24 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "systemFontOfSize:"));
    _objc_msgSend(obj_17, "setFont:", obj_24);
    _objc_release(obj_24);
    id x0_85;
    int64_t x2_31;
    int64_t x3_8;
    int64_t x4_7;
    int64_t x5_7;
    int128_t v0_16;
    int128_t v1_12;
    int128_t v2_12;
    int128_t v3_12;
    x0_85 = _objc_alloc(clsRef_NSAttributedString);
    struct objc_class* x8_1 = *_NSForegroundColorAttributeName;
    struct objc_class* var_c0 = x8_1;
    v3_12 = 1.0;
    v0_16 = 0x3fdccccccccccccd;
    v1_12 = 0x3fe199999999999a;
    v2_12 = 0x3fe6666666666666;
    id obj_25 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:", x2_31, x3_8, x4_7, x5_7));
    id obj_193 = obj_25;
    id obj_26 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSDictionary, 
        "dictionaryWithObjects:forKeys:count:", &obj_193, &var_c0, 1));
    id obj_27 = _objc_msgSend(x0_85, "initWithString:attributes:", 
        &cfstr_Hey_AI_spawn_item_goldbar_10, obj_26);
    _objc_msgSend(obj_17, "setAttributedPlaceholder:", obj_27);
    _objc_release(obj_27);
    _objc_release(obj_26);
    _objc_release(obj_25);
    id x0_96;
    int128_t v0_17;
    int128_t v1_13;
    int128_t v2_13;
    int128_t v3_13;
    x0_96 = _objc_alloc(clsRef_UIView);
    v0_17 = 0.0;
    v1_13 = 0.0;
    v2_13 = 12.0;
    v3_13 = v15;
    int64_t obj_28 = _objc_msgSend(x0_96, "initWithFrame:");
    _objc_msgSend(obj_17, "setLeftView:", obj_28);
    _objc_release(obj_28);
    _objc_msgSend(obj_17, "setLeftViewMode:", 3);
    _objc_msgSend(obj_17, "setReturnKeyType:", 1);
    _objc_msgSend(obj_17, "setTag:");
    _objc_msgSend(obj_17, "setDelegate:", self);
    id obj_29 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminInner"));
    _objc_msgSend(obj_29, "addSubview:", obj_17);
    _objc_release(obj_29);
    id obj_30;
    int64_t x2_38;
    int128_t v0_18;
    int128_t v1_14;
    int128_t v2_14;
    int128_t v3_14;
    obj_30 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:", 0));
    v1_14 = 0x4067400000000000;
    double v8 = 0x4046000000000000;
    v0_18 = 14.0;
    v2_14 = v9;
    v3_14 = v8;
    int64_t x2_39;
    int64_t x3_11;
    int64_t x4_8;
    int64_t x5_8;
    int128_t v0_19;
    int128_t v1_15;
    int128_t v3_15;
    x2_39 = _objc_msgSend(obj_30, "setFrame:", x2_38);
    v3_15 = 1.0;
    v0_19 = 0x3fc999999999999a;
    v1_15 = 0x3fe6666666666666;
    id obj_31 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:", x2_39, x3_11, x4_8, x5_8));
    _objc_msgSend(obj_30, "setBackgroundColor:");
    _objc_release(obj_31);
    id obj_32;
    int128_t v0_20;
    obj_32 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_30, "layer"));
    v0_20 = 12.0;
    _objc_msgSend(obj_32, "setCornerRadius:");
    _objc_release(obj_32);
    int64_t x2_41;
    int64_t x3_12;
    int64_t x4_9;
    int64_t x5_9;
    int128_t v0_21;
    int128_t v1_16;
    int128_t v2_15;
    int128_t v3_16;
    x2_41 = _objc_msgSend(obj_30, "setTitle:forState:", &cfstr_??_Execute_AI_Command, 0);
    v2_15 = 1.0;
    v3_16 = 1.0;
    v0_21 = 0x3feb333333333333;
    v1_16 = 0x3feccccccccccccd;
    id obj_33 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:", x2_41, x3_12, x4_9, x5_9));
    _objc_msgSend(obj_30, "setTitleColor:forState:", obj_33, 0);
    _objc_release(obj_33);
    int128_t v0_22;
    v0_22 = 14.0;
    id obj_34 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    id obj_35 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_30, "titleLabel"));
    _objc_msgSend(obj_35, "setFont:");
    _objc_release(obj_35);
    _objc_release(obj_34);
    _objc_msgSend(obj_30, "addTarget:action:forControlEvents:", self, "aiCommandTapped", 0x40);
    id obj_36 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminInner"));
    _objc_msgSend(obj_36, "addSubview:", obj_30);
    _objc_release(obj_36);
    id obj_37;
    int64_t x2_47;
    int128_t v0_23;
    int128_t v1_17;
    int128_t v2_16;
    int128_t v3_17;
    obj_37 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:"));
    v1_17 = 0x406dc00000000000;
    v0_23 = 14.0;
    v2_16 = v9;
    v3_17 = v8;
    int128_t v0_24;
    int128_t v1_18;
    int128_t v2_17;
    int128_t v3_18;
    v0_24 = _objc_msgSend(obj_37, "setFrame:", x2_47);
    v3_18 = 1.0;
    v0_24 = 0x3fe999999999999a;
    v1_18 = 0x3fc999999999999a;
    v2_17 = 0x3fc999999999999a;
    id obj_38 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_37, "setBackgroundColor:");
    _objc_release(obj_38);
    id obj_39;
    int128_t v0_25;
    obj_39 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_37, "layer"));
    v0_25 = 12.0;
    _objc_msgSend(obj_39, "setCornerRadius:");
    _objc_release(obj_39);
    _objc_msgSend(obj_37, "setTag:");
    int128_t v0_26;
    int128_t v1_19;
    int128_t v2_18;
    int128_t v3_19;
    v0_26 = _objc_msgSend(obj_37, "setTitle:forState:");
    v2_18 = 1.0;
    v3_19 = 1.0;
    v0_26 = 0x3feb333333333333;
    v1_19 = 0x3feccccccccccccd;
    id obj_40 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_37, "setTitleColor:forState:");
    _objc_release(obj_40);
    int128_t v0_27;
    v0_27 = 12.0;
    id obj_41 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    id obj_42 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_37, "titleLabel"));
    _objc_msgSend(obj_42, "setFont:");
    _objc_release(obj_42);
    _objc_release(obj_41);
    id obj_43 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_37, "titleLabel"));
    _objc_msgSend(obj_43, "setAdjustsFontSizeToFitWidth:", 1);
    _objc_release(obj_43);
    _objc_msgSend(obj_37, "addTarget:action:forControlEvents:");
    _objc_msgSend(obj_37, "addTarget:action:forControlEvents:");
    id obj_44 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminInner"));
    _objc_msgSend(obj_44, "addSubview:", obj_37);
    _objc_release(obj_44);
    id x0_160;
    int128_t v0_28;
    int128_t v1_20;
    int128_t v2_19;
    int128_t v3_20;
    x0_160 = _objc_alloc(clsRef_UILabel);
    v1_20 = 0x4072200000000000;
    v0_28 = 14.0;
    v3_20 = 22.0;
    v2_19 = v9;
    int64_t obj_45 = _objc_msgSend(x0_160, "initWithFrame:");
    _objc_msgSend(obj_45, "setText:");
    int128_t v0_29;
    v0_29 = 14.0;
    id obj_46 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    _objc_msgSend(obj_45, "setFont:");
    int128_t v0_30;
    int128_t v1_21;
    int128_t v2_20;
    int128_t v3_21;
    v0_30 = _objc_release(obj_46);
    v3_21 = 1.0;
    v0_30 = 0x3fd999999999999a;
    v1_21 = 0x3fc999999999999a;
    v2_20 = 0x3fee666666666666;
    id obj_47 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_45, "setTextColor:");
    _objc_release(obj_47);
    id obj_48 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminInner"));
    _objc_msgSend(obj_48, "addSubview:", obj_45);
    _objc_release(obj_48);
    id obj_49;
    int128_t v0_31;
    int128_t v1_22;
    int128_t v2_21;
    int128_t v3_22;
    obj_49 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:"));
    v1_22 = 0x4073e00000000000;
    v0_31 = 14.0;
    v2_21 = v9;
    v3_22 = v15;
    int128_t v1_23;
    int128_t v2_22;
    int128_t v3_23;
    v1_23 = _objc_msgSend(obj_49, "setFrame:");
    v3_23 = 1.0;
    v1_23 = 0x3fb999999999999a;
    v2_22 = 0x3fe3333333333333;
    id obj_50 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_49, "setBackgroundColor:");
    _objc_release(obj_50);
    id obj_51;
    int128_t v0_32;
    obj_51 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_49, "layer"));
    v0_32 = 10.0;
    _objc_msgSend(obj_51, "setCornerRadius:");
    _objc_release(obj_51);
    int128_t v0_33;
    int128_t v1_24;
    int128_t v2_23;
    int128_t v3_24;
    v0_33 = _objc_msgSend(obj_49, "setTitle:forState:");
    v2_23 = 1.0;
    v3_24 = 1.0;
    v0_33 = 0x3feb333333333333;
    v1_24 = 0x3feccccccccccccd;
    id obj_52 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_49, "setTitleColor:forState:");
    _objc_release(obj_52);
    int128_t v0_34;
    v0_34 = 13.0;
    id obj_53 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    id obj_54 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_49, "titleLabel"));
    _objc_msgSend(obj_54, "setFont:");
    _objc_release(obj_54);
    _objc_release(obj_53);
    _objc_msgSend(obj_49, "addTarget:action:forControlEvents:");
    id obj_55 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminInner"));
    _objc_msgSend(obj_55, "addSubview:", obj_49);
    _objc_release(obj_55);
    id obj_56;
    int128_t v0_35;
    int128_t v1_25;
    int128_t v2_24;
    int128_t v3_25;
    obj_56 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:"));
    v1_25 = 0x4076e00000000000;
    v0_35 = 14.0;
    v2_24 = v9;
    v3_25 = v15;
    int128_t v0_36;
    int128_t v1_26;
    int128_t v2_25;
    int128_t v3_26;
    v0_36 = _objc_msgSend(obj_56, "setFrame:");
    v3_26 = 1.0;
    v0_36 = 0x3fe999999999999a;
    v1_26 = 0x3fb999999999999a;
    v2_25 = 0x3fb999999999999a;
    id obj_57 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_56, "setBackgroundColor:");
    _objc_release(obj_57);
    id obj_58;
    int128_t v0_37;
    obj_58 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_56, "layer"));
    v0_37 = 10.0;
    _objc_msgSend(obj_58, "setCornerRadius:");
    _objc_release(obj_58);
    int128_t v0_38;
    int128_t v1_27;
    int128_t v2_26;
    int128_t v3_27;
    v0_38 = _objc_msgSend(obj_56, "setTitle:forState:");
    v2_26 = 1.0;
    v3_27 = 1.0;
    v0_38 = 0x3feb333333333333;
    v1_27 = 0x3feccccccccccccd;
    id obj_59 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_56, "setTitleColor:forState:");
    _objc_release(obj_59);
    int128_t v0_39;
    v0_39 = 13.0;
    id obj_60 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    id obj_61 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_56, "titleLabel"));
    _objc_msgSend(obj_61, "setFont:");
    _objc_release(obj_61);
    _objc_release(obj_60);
    _objc_msgSend(obj_56, "addTarget:action:forControlEvents:");
    id obj_62 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminInner"));
    _objc_msgSend(obj_62, "addSubview:", obj_56);
    _objc_release(obj_62);
    id x0_221;
    int128_t v0_40;
    int128_t v1_28;
    int128_t v2_27;
    int128_t v3_28;
    x0_221 = _objc_alloc(clsRef_UILabel);
    v1_28 = 0x4079e00000000000;
    v0_40 = 14.0;
    v3_28 = 22.0;
    v2_27 = v9;
    int64_t obj_63 = _objc_msgSend(x0_221, "initWithFrame:");
    _objc_msgSend(obj_63, "setText:");
    int128_t v0_41;
    v0_41 = 14.0;
    id obj_64 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    _objc_msgSend(obj_63, "setFont:");
    int128_t v0_42;
    int128_t v1_29;
    int128_t v2_28;
    int128_t v3_29;
    v0_42 = _objc_release(obj_64);
    v3_29 = 1.0;
    v0_42 = 0x3fd999999999999a;
    v1_29 = 0x3fc999999999999a;
    v2_28 = 0x3fee666666666666;
    id obj_65 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_63, "setTextColor:");
    _objc_release(obj_65);
    id obj_66 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminInner"));
    _objc_msgSend(obj_66, "addSubview:", obj_63);
    _objc_release(obj_66);
    id x0_234;
    int128_t v0_43;
    int128_t v1_30;
    int128_t v2_29;
    int128_t v3_30;
    x0_234 = _objc_alloc(clsRef_UITextField);
    v1_30 = 0x407b800000000000;
    v0_43 = 14.0;
    v2_29 = v9;
    v3_30 = v15;
    id obj_67;
    int128_t v1_31;
    int128_t v2_30;
    int128_t v3_31;
    obj_67 = _objc_msgSend(x0_234, "initWithFrame:");
    v3_31 = 1.0;
    v1_31 = 0x3fa47ae147ae147b;
    v2_30 = 0x3fbeb851eb851eb8;
    id obj_68 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_67, "setBackgroundColor:");
    _objc_release(obj_68);
    id obj_69;
    int128_t v0_44;
    obj_69 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_67, "layer"));
    v0_44 = 10.0;
    _objc_msgSend(obj_69, "setCornerRadius:");
    _objc_release(obj_69);
    id obj_70;
    int128_t v0_45;
    obj_70 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_67, "layer"));
    v0_45 = 1.0;
    _objc_msgSend(obj_70, "setBorderWidth:");
    int128_t v0_46;
    int128_t v1_32;
    int128_t v2_31;
    int128_t v3_32;
    v0_46 = _objc_release(obj_70);
    v3_32 = 1.0;
    v0_46 = 0x3fd999999999999a;
    v1_32 = 0x3fc999999999999a;
    v2_31 = 0x3fee666666666666;
    id obj_71 = _objc_retainAutorelease(_objc_retainAutoreleasedReturnValue(_objc_msgSend(
        clsRef_UIColor, "colorWithRed:green:blue:alpha:")));
    _objc_msgSend(obj_71, "CGColor");
    id obj_72 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_67, "layer"));
    _objc_msgSend(obj_72, "setBorderColor:");
    _objc_release(obj_72);
    int128_t v0_47;
    int128_t v1_33;
    int128_t v2_32;
    int128_t v3_33;
    v0_47 = _objc_release(obj_71);
    v2_32 = 1.0;
    v3_33 = 1.0;
    v0_47 = 0x3feb333333333333;
    v1_33 = 0x3feccccccccccccd;
    id obj_73 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_67, "setTextColor:");
    _objc_release(obj_73);
    int128_t v0_48;
    v0_48 = 13.0;
    id obj_74 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "systemFontOfSize:"));
    _objc_msgSend(obj_67, "setFont:");
    _objc_release(obj_74);
    id x0_262;
    int128_t v0_49;
    int128_t v1_34;
    int128_t v2_33;
    int128_t v3_34;
    x0_262 = _objc_alloc(clsRef_NSAttributedString);
    struct objc_class* var_d0 = x8_1;
    v3_34 = 1.0;
    v1_34 = 0x3fe199999999999a;
    v0_49 = 0x3fdccccccccccccd;
    v2_33 = 0x3fe6666666666666;
    id obj_75 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    id obj_192 = obj_75;
    id obj_76 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSDictionary, 
        "dictionaryWithObjects:forKeys:count:"));
    id obj_77 = _objc_msgSend(x0_262, "initWithString:attributes:");
    _objc_msgSend(obj_67, "setAttributedPlaceholder:");
    _objc_release(obj_77);
    _objc_release(obj_76);
    _objc_release(obj_75);
    id x0_273;
    int128_t v0_50;
    int128_t v1_35;
    int128_t v2_34;
    int128_t v3_35;
    x0_273 = _objc_alloc(clsRef_UIView);
    v0_50 = 0.0;
    v1_35 = 0.0;
    v2_34 = 12.0;
    v3_35 = v15;
    id obj_78 = _objc_msgSend(x0_273, "initWithFrame:");
    _objc_msgSend(obj_67, "setLeftView:");
    _objc_release(obj_78);
    _objc_msgSend(obj_67, "setLeftViewMode:");
    _objc_msgSend(obj_67, "setReturnKeyType:");
    _objc_msgSend(obj_67, "setTag:");
    _objc_msgSend(obj_67, "setDelegate:");
    
    if (data_446a60)
        _objc_msgSend(obj_67, "setText:");
    
    id obj_79 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminInner"));
    _objc_msgSend(obj_79, "addSubview:", obj_67);
    _objc_release(obj_79);
    id obj_80;
    int128_t v0_51;
    int128_t v1_36;
    int128_t v2_35;
    int128_t v3_36;
    obj_80 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:"));
    v1_36 = 0x407e800000000000;
    v3_36 = 0x4043000000000000;
    v0_51 = 14.0;
    v2_35 = v9;
    int128_t v0_52;
    int128_t v1_37;
    int128_t v2_36;
    int128_t v3_37;
    v0_52 = _objc_msgSend(obj_80, "setFrame:");
    v3_37 = 1.0;
    v0_52 = 0x3fc999999999999a;
    v1_37 = 0x3fe3333333333333;
    v2_36 = 0x3fe999999999999a;
    id obj_81 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_80, "setBackgroundColor:");
    _objc_release(obj_81);
    id obj_82;
    int128_t v0_53;
    obj_82 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_80, "layer"));
    v0_53 = 10.0;
    _objc_msgSend(obj_82, "setCornerRadius:");
    _objc_release(obj_82);
    int128_t v0_54;
    int128_t v1_38;
    int128_t v2_37;
    int128_t v3_38;
    v0_54 = _objc_msgSend(obj_80, "setTitle:forState:");
    v2_37 = 1.0;
    v3_38 = 1.0;
    v0_54 = 0x3feb333333333333;
    v1_38 = 0x3feccccccccccccd;
    id obj_83 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_80, "setTitleColor:forState:");
    _objc_release(obj_83);
    int128_t v0_55;
    v0_55 = 13.0;
    id obj_84 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    id obj_85 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_80, "titleLabel"));
    _objc_msgSend(obj_85, "setFont:");
    _objc_release(obj_85);
    _objc_release(obj_84);
    _objc_msgSend(obj_80, "addTarget:action:forControlEvents:");
    id obj_86 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminInner"));
    _objc_msgSend(obj_86, "addSubview:", obj_80);
    _objc_release(obj_86);
    id x0_309;
    int128_t v0_56;
    int128_t v1_39;
    int128_t v2_38;
    int128_t v3_39;
    x0_309 = _objc_alloc(clsRef_UILabel);
    v1_39 = 0x4080b00000000000;
    v0_56 = 14.0;
    v3_39 = 22.0;
    v2_38 = v9;
    int64_t obj_87 = _objc_msgSend(x0_309, "initWithFrame:");
    _objc_msgSend(obj_87, "setText:");
    int128_t v0_57;
    v0_57 = 14.0;
    id obj_88 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    _objc_msgSend(obj_87, "setFont:");
    int128_t v0_58;
    int128_t v1_40;
    int128_t v2_39;
    int128_t v3_40;
    v0_58 = _objc_release(obj_88);
    v3_40 = 1.0;
    v0_58 = 0x3fd999999999999a;
    v1_40 = 0x3fc999999999999a;
    v2_39 = 0x3fee666666666666;
    id obj_89 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_87, "setTextColor:");
    _objc_release(obj_89);
    id obj_90 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminInner"));
    _objc_msgSend(obj_90, "addSubview:", obj_87);
    _objc_release(obj_90);
    id x0_322;
    int128_t v0_59;
    int128_t v1_41;
    int128_t v2_40;
    int128_t v3_41;
    x0_322 = _objc_alloc(clsRef_UILabel);
    v1_41 = 0x4081800000000000;
    v0_59 = 14.0;
    v3_41 = 30.0;
    v2_40 = v9;
    int64_t obj_91 = _objc_msgSend(x0_322, "initWithFrame:");
    _objc_msgSend(obj_91, "setText:");
    int128_t v0_60;
    v0_60 = 10.0;
    id obj_92 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "systemFontOfSize:"));
    _objc_msgSend(obj_91, "setFont:");
    int128_t v0_61;
    int128_t v1_42;
    int128_t v2_41;
    int128_t v3_42;
    v0_61 = _objc_release(obj_92);
    v3_42 = 1.0;
    v1_42 = 0x3fe199999999999a;
    v0_61 = 0x3fdccccccccccccd;
    v2_41 = 0x3fe6666666666666;
    id obj_93 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_91, "setTextColor:");
    _objc_release(obj_93);
    _objc_msgSend(obj_91, "setNumberOfLines:");
    id obj_94 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminInner"));
    _objc_msgSend(obj_94, "addSubview:", obj_91);
    _objc_release(obj_94);
    struct __NSConstantString* const var_170 = &cfstr_1:_Front_2m,_0.3s;
    struct __NSConstantString* const var_168 = &cfstr_2:_Front_1m,_0.2s;
    struct __NSConstantString* const var_160 = &cfstr_3:_Front_3m,_0.5s;
    struct __NSConstantString* const var_158 = &cfstr_4:_Above_head,_0.3s;
    struct __NSConstantString* const var_150 = &cfstr_5:_Left_side,_0.3s;
    struct __NSConstantString* const var_148 = &cfstr_6:_Right_side,_0.3s;
    struct __NSConstantString* const var_140 = &cfstr_7:_Front_2m,_0.1s;
    struct __NSConstantString* const var_138 = &cfstr_8:_Orbit_CW,_0.3s;
    struct __NSConstantString* const var_130 = &cfstr_9:_Orbit_CCW,_0.3s;
    struct __NSConstantString* const var_128 = &cfstr_10:_Trail_behind,_0.3s;
    struct __NSConstantString* const var_120 = &cfstr_11:_Front_4m,_0.5s;
    struct __NSConstantString* const var_118 = &cfstr_12:_Below_feet,_0.3s;
    struct __NSConstantString* const var_110 = &cfstr_13:_Front_1.5m,_0.15s;
    struct __NSConstantString* const var_108 = &cfstr_14:_Diagonal_L,_0.3s;
    struct __NSConstantString* const var_100 = &cfstr_15:_Diagonal_R,_0.3s;
    struct __NSConstantString* const var_f8 = &cfstr_16:_Halo_above,_0.4s;
    struct __NSConstantString* const var_f0 = &cfstr_17:_Front_ground,_0.2s;
    struct __NSConstantString* const var_e8 = &cfstr_18:_Shield_front,_0.25s;
    struct __NSConstantString* const var_e0 = &cfstr_19:_Double_stack,_0.3s;
    struct __NSConstantString* const var_d8 = &cfstr_20:_Random_offset,_0.2s;
    id obj_95 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &var_170, 0x14));
    int64_t i = 0;
    double var_370 = v9;
    double v12 = 592.0;
    
    do
    {
        id obj_96;
        int128_t v2_42;
        int128_t v3_43;
        obj_96 =
            _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:"));
        
        if (i & 1)
            v12 = v12 + 0x4045000000000000;
        
        v3_43 = 0x4041000000000000;
        v2_42 = (v9 + -6.0) * 0.5;
        int128_t v0_64;
        int128_t v1_45;
        int128_t v2_43;
        int128_t v3_44;
        v0_64 = _objc_msgSend(obj_96, "setFrame:");
        v3_44 = 1.0;
        v0_64 = 0x3fc3333333333333;
        v1_45 = 0x3fbeb851eb851eb8;
        v2_43 = 0x3fd3333333333333;
        id obj_97 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
            "colorWithRed:green:blue:alpha:"));
        _objc_msgSend(obj_96, "setBackgroundColor:");
        _objc_release(obj_97);
        id obj_98;
        int128_t v0_65;
        obj_98 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_96, "layer"));
        v0_65 = 8.0;
        _objc_msgSend(obj_98, "setCornerRadius:");
        _objc_release(obj_98);
        id obj_99;
        int128_t v0_66;
        obj_99 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_96, "layer"));
        v0_66 = 1.0;
        _objc_msgSend(obj_99, "setBorderWidth:");
        int128_t v0_67;
        int128_t v1_46;
        int128_t v2_44;
        int128_t v3_45;
        v0_67 = _objc_release(obj_99);
        v3_45 = 0.5;
        v0_67 = 0x3fc999999999999a;
        v1_46 = 0x3fe3333333333333;
        v2_44 = 0x3fee666666666666;
        id obj_100 = _objc_retainAutorelease(_objc_retainAutoreleasedReturnValue(_objc_msgSend(
            clsRef_UIColor, "colorWithRed:green:blue:alpha:")));
        _objc_msgSend(obj_100, "CGColor");
        id obj_101 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_96, "layer"));
        _objc_msgSend(obj_101, "setBorderColor:");
        _objc_release(obj_101);
        _objc_release(obj_100);
        id obj_102 =
            _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_95, "objectAtIndexedSubscript:"));
        _objc_msgSend(obj_96, "setTitle:forState:");
        int128_t v0_68;
        int128_t v1_47;
        int128_t v2_45;
        int128_t v3_46;
        v0_68 = _objc_release(obj_102);
        v2_45 = 1.0;
        v3_46 = 1.0;
        v0_68 = 0x3feb333333333333;
        v1_47 = 0x3feccccccccccccd;
        id obj_103 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
            "colorWithRed:green:blue:alpha:"));
        _objc_msgSend(obj_96, "setTitleColor:forState:");
        int128_t v0_69;
        int128_t v1_48;
        v0_69 = _objc_release(obj_103);
        v0_69 = 9.0;
        v1_48 = v1_3;
        id obj_104 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
            "systemFontOfSize:weight:"));
        id obj_105 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_96, "titleLabel"));
        _objc_msgSend(obj_105, "setFont:");
        _objc_release(obj_105);
        _objc_release(obj_104);
        id obj_106 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_96, "titleLabel"));
        _objc_msgSend(obj_106, "setAdjustsFontSizeToFitWidth:");
        _objc_release(obj_106);
        _objc_msgSend(obj_96, "setTag:");
        _objc_msgSend(obj_96, "addTarget:action:forControlEvents:");
        id obj_107 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminInner"));
        _objc_msgSend(obj_107, "addSubview:", obj_96);
        _objc_release(obj_107);
        _objc_release(obj_96);
        i += 1;
    } while (i != 0x14);
    
    v9 = v12 + 8.0;
    id x0_381;
    int128_t v0_71;
    int128_t v1_49;
    int128_t v2_46;
    int128_t v3_47;
    x0_381 = _objc_alloc(clsRef_UILabel);
    v0_71 = 14.0;
    v3_47 = 22.0;
    v1_49 = v9;
    v2_46 = var_370;
    id obj_108 = _objc_msgSend(x0_381, "initWithFrame:");
    _objc_msgSend(obj_108, "setText:");
    int128_t v0_72;
    v0_72 = 14.0;
    id obj_109 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    _objc_msgSend(obj_108, "setFont:");
    int128_t v0_73;
    int128_t v1_50;
    int128_t v2_47;
    int128_t v3_48;
    v0_73 = _objc_release(obj_109);
    v3_48 = 1.0;
    v0_73 = 0x3fd999999999999a;
    v1_50 = 0x3fc999999999999a;
    v2_47 = 0x3fee666666666666;
    id obj_110 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_108, "setTextColor:");
    _objc_release(obj_110);
    id obj_111 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminInner"));
    _objc_msgSend(obj_111, "addSubview:", obj_108);
    _objc_release(obj_111);
    v9 = v9 + 26.0;
    id x0_394;
    int128_t v0_75;
    int128_t v1_51;
    int128_t v2_48;
    int128_t v3_49;
    x0_394 = _objc_alloc(clsRef_UITextField);
    double v10 = 0x4044000000000000;
    v0_75 = 14.0;
    v1_51 = v9;
    v2_48 = var_370;
    v3_49 = v10;
    id obj_112;
    int128_t v1_52;
    int128_t v2_49;
    int128_t v3_50;
    obj_112 = _objc_msgSend(x0_394, "initWithFrame:");
    v3_50 = 1.0;
    v1_52 = 0x3fa47ae147ae147b;
    v2_49 = 0x3fbeb851eb851eb8;
    id obj_113 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_112, "setBackgroundColor:");
    _objc_release(obj_113);
    id obj_114;
    int128_t v0_76;
    obj_114 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_112, "layer"));
    v0_76 = 10.0;
    _objc_msgSend(obj_114, "setCornerRadius:");
    _objc_release(obj_114);
    id obj_115;
    int128_t v0_77;
    obj_115 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_112, "layer"));
    v0_77 = 1.0;
    _objc_msgSend(obj_115, "setBorderWidth:");
    int128_t v0_78;
    int128_t v1_53;
    int128_t v2_50;
    int128_t v3_51;
    v0_78 = _objc_release(obj_115);
    v3_51 = 1.0;
    v0_78 = 0x3fb999999999999a;
    v1_53 = 0x3fe999999999999a;
    v2_50 = 0x3fee666666666666;
    id obj_116 = _objc_retainAutorelease(_objc_retainAutoreleasedReturnValue(_objc_msgSend(
        clsRef_UIColor, "colorWithRed:green:blue:alpha:")));
    _objc_msgSend(obj_116, "CGColor");
    id obj_117 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_112, "layer"));
    _objc_msgSend(obj_117, "setBorderColor:");
    _objc_release(obj_117);
    int128_t v0_79;
    int128_t v1_54;
    int128_t v2_51;
    int128_t v3_52;
    v0_79 = _objc_release(obj_116);
    v2_51 = 1.0;
    v3_52 = 1.0;
    v0_79 = 0x3feb333333333333;
    v1_54 = 0x3feccccccccccccd;
    id obj_118 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_112, "setTextColor:");
    _objc_release(obj_118);
    int128_t v0_80;
    v0_80 = 13.0;
    id obj_119 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "systemFontOfSize:"));
    _objc_msgSend(obj_112, "setFont:");
    _objc_release(obj_119);
    id x0_422;
    int128_t v0_81;
    int128_t v1_55;
    int128_t v2_52;
    int128_t v3_53;
    x0_422 = _objc_alloc(clsRef_NSAttributedString);
    struct objc_class* var_180 = x8_1;
    v3_53 = 1.0;
    v1_55 = 0x3fe199999999999a;
    v0_81 = 0x3fdccccccccccccd;
    v2_52 = 0x3fe6666666666666;
    id obj_120 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    id obj_191 = obj_120;
    id obj_121 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSDictionary, 
        "dictionaryWithObjects:forKeys:count:"));
    id obj_122 = _objc_msgSend(x0_422, "initWithString:attributes:");
    _objc_msgSend(obj_112, "setAttributedPlaceholder:");
    _objc_release(obj_122);
    _objc_release(obj_121);
    _objc_release(obj_120);
    id x0_433;
    int128_t v0_82;
    int128_t v1_56;
    int128_t v2_53;
    int128_t v3_54;
    x0_433 = _objc_alloc(clsRef_UIView);
    v0_82 = 0.0;
    v1_56 = 0.0;
    v2_53 = 12.0;
    v3_54 = v10;
    id obj_123 = _objc_msgSend(x0_433, "initWithFrame:");
    _objc_msgSend(obj_112, "setLeftView:");
    _objc_release(obj_123);
    _objc_msgSend(obj_112, "setLeftViewMode:");
    _objc_msgSend(obj_112, "setReturnKeyType:");
    _objc_msgSend(obj_112, "setTag:");
    _objc_msgSend(obj_112, "setDelegate:");
    id obj_124 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminInner"));
    _objc_msgSend(obj_124, "addSubview:", obj_112);
    _objc_release(obj_124);
    v12 = 0x4048000000000000;
    v9 = v9 + v12;
    id obj_125;
    int128_t v0_83;
    int128_t v1_57;
    int128_t v2_54;
    int128_t v3_55;
    obj_125 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:"));
    v0_83 = 14.0;
    v1_57 = v9;
    v2_54 = var_370;
    v3_55 = v10;
    int128_t v0_84;
    int128_t v1_58;
    int128_t v2_55;
    int128_t v3_56;
    v0_84 = _objc_msgSend(obj_125, "setFrame:");
    v3_56 = 1.0;
    v0_84 = 0x3fb999999999999a;
    v1_58 = 0x3fe999999999999a;
    v2_55 = 0x3fee666666666666;
    id obj_126 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_125, "setBackgroundColor:");
    _objc_release(obj_126);
    id obj_127;
    int128_t v0_85;
    obj_127 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_125, "layer"));
    v0_85 = 10.0;
    _objc_msgSend(obj_127, "setCornerRadius:");
    _objc_release(obj_127);
    int128_t v0_86;
    int128_t v1_59;
    int128_t v2_56;
    int128_t v3_57;
    v0_86 = _objc_msgSend(obj_125, "setTitle:forState:");
    v2_56 = 1.0;
    v3_57 = 1.0;
    v0_86 = 0x3feb333333333333;
    v1_59 = 0x3feccccccccccccd;
    id obj_128 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_125, "setTitleColor:forState:");
    _objc_release(obj_128);
    int128_t v0_87;
    v0_87 = 13.0;
    id obj_129 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    id obj_130 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_125, "titleLabel"));
    _objc_msgSend(obj_130, "setFont:");
    _objc_release(obj_130);
    _objc_release(obj_129);
    _objc_msgSend(obj_125, "addTarget:action:forControlEvents:");
    id obj_131 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminInner"));
    _objc_msgSend(obj_131, "addSubview:", obj_125);
    _objc_release(obj_131);
    v9 = v9 + v12;
    id x0_468;
    int128_t v0_88;
    int128_t v1_60;
    int128_t v2_57;
    int128_t v3_58;
    x0_468 = _objc_alloc(clsRef_UILabel);
    v0_88 = 14.0;
    v3_58 = 22.0;
    v1_60 = v9;
    v2_57 = var_370;
    id obj_132 = _objc_msgSend(x0_468, "initWithFrame:");
    _objc_msgSend(obj_132, "setText:");
    int128_t v0_89;
    v0_89 = 14.0;
    id obj_133 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    _objc_msgSend(obj_132, "setFont:");
    int128_t v0_90;
    int128_t v1_61;
    int128_t v2_58;
    int128_t v3_59;
    v0_90 = _objc_release(obj_133);
    v3_59 = 1.0;
    v0_90 = 0x3fd999999999999a;
    v1_61 = 0x3fc999999999999a;
    v2_58 = 0x3fee666666666666;
    id obj_134 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_132, "setTextColor:");
    _objc_release(obj_134);
    id obj_135 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminInner"));
    _objc_msgSend(obj_135, "addSubview:", obj_132);
    _objc_release(obj_135);
    v8 = v9 + 26.0;
    struct __NSConstantString* const var_1b0 = &cfstr_Spawn_500_Gold_Bars;
    struct __NSConstantString* const var_1a8 = &cfstr_Rain_Jetpacks;
    struct __NSConstantString* const var_1a0 = &cfstr_Spawn_RPG_Arsenal;
    struct __NSConstantString* const var_198 = &cfstr_Diamond_Floor;
    struct __NSConstantString* const var_190 = &cfstr_Weapon_Wall;
    struct __NSConstantString* const var_188 = &cfstr_Reset_Spawn_Approach;
    id obj_136 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:"));
    double v11;
    
    if (_objc_msgSend(obj_136, "count") < 1)
        v11 = 0.84999999999999998;
    else
    {
        int64_t x22_17 = 0;
        v11 = 0.84999999999999998;
        id x0_513;
        
        do
        {
            id obj_137;
            int128_t v0_92;
            int128_t v1_62;
            int128_t v2_59;
            int128_t v3_60;
            obj_137 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, 
                "buttonWithType:"));
            v3_60 = 0x4043000000000000;
            v0_92 = 14.0;
            v1_62 = v8;
            v2_59 = var_370;
            int128_t v0_93;
            int128_t v1_63;
            int128_t v2_60;
            int128_t v3_61;
            v0_93 = _objc_msgSend(obj_137, "setFrame:");
            v2_60 = 0.5;
            v3_61 = 1.0;
            v0_93 = 0x3fd999999999999a;
            v1_63 = 0x3fc3333333333333;
            id obj_138 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
                "colorWithRed:green:blue:alpha:"));
            _objc_msgSend(obj_137, "setBackgroundColor:");
            _objc_release(obj_138);
            id obj_139;
            int128_t v0_94;
            obj_139 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_137, "layer"));
            v0_94 = 10.0;
            _objc_msgSend(obj_139, "setCornerRadius:");
            _objc_release(obj_139);
            id obj_140 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_136, 
                "objectAtIndexedSubscript:"));
            _objc_msgSend(obj_137, "setTitle:forState:");
            int128_t v0_95;
            int128_t v1_64;
            int128_t v2_61;
            int128_t v3_62;
            v0_95 = _objc_release(obj_140);
            v2_61 = 1.0;
            v3_62 = 1.0;
            v0_95 = 0x3feb333333333333;
            v1_64 = 0x3feccccccccccccd;
            id obj_141 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
                "colorWithRed:green:blue:alpha:"));
            _objc_msgSend(obj_137, "setTitleColor:forState:");
            _objc_release(obj_141);
            int128_t v0_96;
            v0_96 = 12.0;
            id obj_142 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
                "boldSystemFontOfSize:"));
            id obj_143 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_137, "titleLabel"));
            _objc_msgSend(obj_143, "setFont:");
            _objc_release(obj_143);
            _objc_release(obj_142);
            _objc_msgSend(obj_137, "setTag:");
            _objc_msgSend(obj_137, "addTarget:action:forControlEvents:");
            id obj_144 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminInner"));
            _objc_msgSend(obj_144, "addSubview:");
            _objc_release(obj_144);
            v8 = v8 + 0x4046000000000000;
            _objc_release(obj_137);
            x0_513 = _objc_msgSend(obj_136, "count");
            x22_17 += 1;
        } while (x22_17 < x0_513);
    }
    
    id x0_515;
    int128_t v0_98;
    int128_t v1_65;
    int128_t v2_62;
    int128_t v3_63;
    x0_515 = _objc_alloc(clsRef_UILabel);
    v0_98 = 14.0;
    v3_63 = 24.0;
    v1_65 = v8;
    v2_62 = var_370;
    id obj_145 = _objc_msgSend(x0_515, "initWithFrame:");
    _objc_msgSend(obj_145, "setText:");
    int128_t v0_99;
    v0_99 = 14.0;
    id obj_146 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    _objc_msgSend(obj_145, "setFont:");
    int128_t v0_100;
    int128_t v1_66;
    int128_t v2_63;
    int128_t v3_64;
    v0_100 = _objc_release(obj_146);
    v3_64 = 1.0;
    v0_100 = 0x3fd999999999999a;
    v1_66 = 0x3fc999999999999a;
    v2_63 = 0x3fee666666666666;
    id obj_147 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_145, "setTextColor:");
    _objc_release(obj_147);
    id obj_148 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminInner"));
    _objc_msgSend(obj_148, "addSubview:");
    _objc_release(obj_148);
    v8 = v8 + 28.0;
    id obj_149;
    int128_t v0_102;
    int128_t v1_67;
    int128_t v2_64;
    int128_t v3_65;
    obj_149 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:"));
    v3_65 = 0x4042000000000000;
    v0_102 = 14.0;
    v1_67 = v8;
    v2_64 = var_370;
    int128_t v0_103;
    int128_t v1_68;
    int128_t v2_65;
    int128_t v3_66;
    v0_103 = _objc_msgSend(obj_149, "setFrame:");
    v1_68 = 0.25;
    v3_66 = 1.0;
    v0_103 = 0x3fb999999999999a;
    v2_65 = 0x3fe199999999999a;
    id obj_150 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_149, "setBackgroundColor:");
    _objc_release(obj_150);
    id obj_151;
    int128_t v0_104;
    obj_151 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_149, "layer"));
    v0_104 = 10.0;
    _objc_msgSend(obj_151, "setCornerRadius:");
    _objc_release(obj_151);
    int128_t v0_105;
    int128_t v1_69;
    int128_t v2_66;
    int128_t v3_67;
    v0_105 = _objc_msgSend(obj_149, "setTitle:forState:");
    v2_66 = 1.0;
    v3_67 = 1.0;
    v0_105 = v11;
    v1_69 = 0x3feccccccccccccd;
    id obj_152 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_149, "setTitleColor:forState:");
    _objc_release(obj_152);
    int128_t v0_106;
    v0_106 = 12.0;
    id obj_153 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    id obj_154 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_149, "titleLabel"));
    _objc_msgSend(obj_154, "setFont:");
    _objc_release(obj_154);
    _objc_release(obj_153);
    _objc_msgSend(obj_149, "addTarget:action:forControlEvents:");
    id obj_155 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminInner"));
    _objc_msgSend(obj_155, "addSubview:");
    _objc_release(obj_155);
    v8 = v8 + 0x4045000000000000;
    id x0_552;
    int128_t v0_108;
    int128_t v1_70;
    int128_t v2_67;
    int128_t v3_68;
    x0_552 = _objc_alloc(clsRef_UIView);
    v0_108 = 14.0;
    v3_68 = 10.0;
    v1_70 = v8;
    v2_67 = var_370;
    int64_t obj_156 = _objc_msgSend(x0_552, "initWithFrame:");
    _objc_msgSend(self, "setConnectedUsersContainer:", obj_156);
    int128_t v0_109;
    int128_t v1_71;
    int128_t v2_68;
    int128_t v3_69;
    v0_109 = _objc_release(obj_156);
    v0_109 = 0x3fa999999999999a;
    v2_68 = 0x3fc1eb851eb851ec;
    v3_69 = 1.0;
    v1_71 = 0x3fa47ae147ae147b;
    id obj_157 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    id obj_158 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "connectedUsersContainer"));
    _objc_msgSend(obj_158, "setBackgroundColor:");
    _objc_release(obj_158);
    _objc_release(obj_157);
    id obj_159 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "connectedUsersContainer"));
    id obj_160;
    int128_t v0_110;
    obj_160 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_159, "layer"));
    v0_110 = 10.0;
    _objc_msgSend(obj_160, "setCornerRadius:");
    _objc_release(obj_160);
    _objc_release(obj_159);
    id obj_161 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "connectedUsersContainer"));
    _objc_msgSend(obj_161, "setTag:");
    _objc_release(obj_161);
    id obj_162 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminInner"));
    id obj_163 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "connectedUsersContainer"));
    _objc_msgSend(obj_162, "addSubview:");
    _objc_release(obj_163);
    _objc_release(obj_162);
    _objc_msgSend(self, "rebuildConnectedUserRows");
    id obj_164 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "connectedUsersContainer"));
    v8 = v8 + _objc_msgSend(obj_164, "frame") + 6.0;
    _objc_release(obj_164);
    id x0_581;
    int128_t v0_112;
    int128_t v1_72;
    int128_t v2_69;
    int128_t v3_71;
    x0_581 = _objc_alloc(clsRef_UILabel);
    v0_112 = 14.0;
    v3_71 = 26.0;
    v1_72 = v8;
    v2_69 = var_370;
    id obj_165 = _objc_msgSend(x0_581, "initWithFrame:");
    _objc_msgSend(obj_165, "setText:");
    int128_t v0_113;
    v0_113 = 8.0;
    id obj_166 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "systemFontOfSize:"));
    _objc_msgSend(obj_165, "setFont:");
    int128_t v0_114;
    int128_t v1_73;
    int128_t v2_70;
    int128_t v3_72;
    v0_114 = _objc_release(obj_166);
    v3_72 = 1.0;
    v0_114 = 0x3fdccccccccccccd;
    v1_73 = 0x3fe199999999999a;
    v2_70 = 0x3fe6666666666666;
    id obj_167 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_165, "setTextColor:");
    _objc_release(obj_167);
    _objc_msgSend(obj_165, "setNumberOfLines:");
    id obj_168 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminInner"));
    _objc_msgSend(obj_168, "addSubview:");
    _objc_release(obj_168);
    v8 = v8 + 30.0;
    id x0_595;
    int128_t v0_116;
    int128_t v1_74;
    int128_t v2_71;
    int128_t v3_73;
    x0_595 = _objc_alloc(clsRef_UITextView);
    v3_73 = 0x4054000000000000;
    v0_116 = 14.0;
    v1_74 = v8;
    v2_71 = var_370;
    id obj_169;
    int128_t v1_75;
    int128_t v2_72;
    int128_t v3_74;
    obj_169 = _objc_msgSend(x0_595, "initWithFrame:");
    v2_72 = 0x3faeb851eb851eb8;
    v3_74 = 1.0;
    v1_75 = 0x3f947ae147ae147b;
    id obj_170 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_169, "setBackgroundColor:");
    _objc_release(obj_170);
    id obj_171;
    int128_t v0_117;
    obj_171 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_169, "layer"));
    v0_117 = 10.0;
    _objc_msgSend(obj_171, "setCornerRadius:");
    _objc_release(obj_171);
    id obj_172;
    int128_t v0_118;
    obj_172 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_169, "layer"));
    v0_118 = 1.0;
    _objc_msgSend(obj_172, "setBorderWidth:");
    int64_t x2_176;
    int64_t x3_41;
    int128_t v0_119;
    int128_t v1_76;
    x2_176 = _objc_release(obj_172);
    v1_76 = 1.0;
    v0_119 = 0x3fc3333333333333;
    id obj_173 = _objc_retainAutorelease(_objc_retainAutoreleasedReturnValue(_objc_msgSend(
        clsRef_UIColor, "colorWithWhite:alpha:", x2_176, x3_41)));
    _objc_msgSend(obj_173, "CGColor");
    id obj_174 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_169, "layer"));
    _objc_msgSend(obj_174, "setBorderColor:");
    _objc_release(obj_174);
    int128_t v0_120;
    int128_t v1_77;
    int128_t v2_73;
    int128_t v3_75;
    v0_120 = _objc_release(obj_173);
    v3_75 = 1.0;
    v0_120 = 0x3fd3333333333333;
    v1_77 = v11;
    v2_73 = 0x3fee666666666666;
    id obj_175 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_169, "setTextColor:");
    int64_t x3_42;
    int128_t v0_121;
    x3_42 = _objc_release(obj_175);
    v0_121 = 9.0;
    id obj_176 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
        "fontWithName:size:", &cfstr_Menlo, x3_42));
    _objc_msgSend(obj_169, "setFont:");
    _objc_release(obj_176);
    id obj_177 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_169, "font"));
    int64_t x2_180;
    int64_t x3_43;
    int128_t v0_122;
    int128_t v1_78;
    x2_180 = _objc_release(obj_177);
    
    if (!obj_177)
    {
        v1_78 = *_UIFontWeightRegular;
        v0_122 = 9.0;
        id obj_178 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
            "monospacedSystemFontOfSize:weight:", x2_180, x3_43));
        _objc_msgSend(obj_169, "setFont:");
        _objc_release(obj_178);
    }
    
    _objc_msgSend(obj_169, "setEditable:", 0);
    data_446a78;
    _objc_msgSend(obj_169, "setText:");
    _objc_msgSend(obj_169, "setTag:");
    id obj_179 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminInner"));
    _objc_msgSend(obj_179, "addSubview:");
    _objc_release(obj_179);
    v8 = v8 + 86.0;
    id x0_635;
    int128_t v0_123;
    int128_t v1_79;
    int128_t v2_74;
    int128_t v3_76;
    x0_635 = _objc_alloc(clsRef_UILabel);
    v0_123 = 14.0;
    v3_76 = 18.0;
    v1_79 = v8;
    v2_74 = var_370;
    id obj_180 = _objc_msgSend(x0_635, "initWithFrame:");
    int128_t v0_124;
    int128_t v1_80;
    v0_124 = _objc_msgSend(obj_180, "setText:");
    v0_124 = 11.0;
    v1_80 = v1_3;
    id obj_181 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
        "systemFontOfSize:weight:"));
    _objc_msgSend(obj_180, "setFont:");
    int128_t v0_125;
    int128_t v1_81;
    int128_t v2_75;
    int128_t v3_77;
    v0_125 = _objc_release(obj_181);
    v1_81 = 0.5;
    v2_75 = 1.0;
    v3_77 = 1.0;
    v0_125 = 0x3fc999999999999a;
    id obj_182 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_180, "setTextColor:");
    _objc_release(obj_182);
    _objc_msgSend(obj_180, "setTextAlignment:", 1);
    id obj_183 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminInner"));
    _objc_msgSend(obj_183, "addSubview:");
    _objc_release(obj_183);
    v8 = v8 + 20.0;
    id obj_184;
    int128_t v0_127;
    int128_t v1_82;
    int128_t v2_76;
    int128_t v3_78;
    obj_184 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:"));
    v0_127 = 14.0;
    v3_78 = 18.0;
    v1_82 = v8;
    v2_76 = var_370;
    _objc_msgSend(obj_184, "setFrame:");
    int128_t v0_128;
    int128_t v1_83;
    int128_t v2_77;
    int128_t v3_79;
    v0_128 = _objc_msgSend(obj_184, "setTitle:forState:");
    v0_128 = 0x3fd6666666666666;
    v2_77 = 1.0;
    v3_79 = 1.0;
    v1_83 = 0x3fd999999999999a;
    id obj_185 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_184, "setTitleColor:forState:");
    int128_t v0_129;
    int128_t v1_84;
    v0_129 = _objc_release(obj_185);
    v1_84 = *_UIFontWeightBold;
    v0_129 = 11.0;
    id obj_186 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
        "systemFontOfSize:weight:"));
    id obj_187 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_184, "titleLabel"));
    _objc_msgSend(obj_187, "setFont:");
    _objc_release(obj_187);
    _objc_release(obj_186);
    _objc_msgSend(obj_184, "addTarget:action:forControlEvents:");
    id obj_188 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminInner"));
    _objc_msgSend(obj_188, "addSubview:");
    _objc_release(obj_188);
    v8 = v8 + 26.0;
    id obj_189;
    int128_t v0_130;
    int128_t v1_85;
    int128_t v2_78;
    int128_t v3_80;
    obj_189 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminInner"));
    v0_130 = 0.0;
    v1_85 = 0.0;
    v2_78 = v2;
    v3_80 = v8;
    _objc_msgSend(obj_189, "setFrame:");
    _objc_release(obj_189);
    id obj_190;
    int64_t x2_195;
    int128_t v0_131;
    int128_t v1_86;
    obj_190 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminScroll"));
    v0_131 = v2;
    v1_86 = v8;
    _objc_msgSend(obj_190, "setContentSize:", x2_195);
    _objc_release(obj_190);
    _objc_release(obj_184);
    _objc_release(obj_180);
    _objc_release(obj_169);
    _objc_release(obj_165);
    _objc_release(obj_149);
    _objc_release(obj_145);
    _objc_release(obj_136);
    _objc_release(obj_132);
    _objc_release(obj_125);
    _objc_release(obj_112);
    _objc_release(obj_108);
    _objc_release(obj_95);
    _objc_release(obj_91);
    _objc_release(obj_87);
    _objc_release(obj_80);
    _objc_release(obj_67);
    _objc_release(obj_63);
    _objc_release(obj_56);
    _objc_release(obj_49);
    _objc_release(obj_45);
    _objc_release(obj_37);
    _objc_release(obj_30);
    _objc_release(obj_17);
    _objc_release(obj_13);
    _objc_release(obj_9);
    _objc_release(obj_5);
    _objc_release(obj_1);
    
    if (*___stack_chk_guard == x8)
        return;
    
    ___stack_chk_fail();
    /* no return */
}

void -[ACPanelController showAdminPasscodePrompt](struct ACPanelController* self, SEL sel)
{
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIAlertController, 
        "alertControllerWithTitle:message:preferredStyle:", &cfstr_??_Admin_Access, 
        &cfstr_Enter_passcode:, 1));
    _objc_msgSend(obj, "addTextFieldWithConfigurationHandler:", &data_43c0e0);
    struct objc_class_t* clsRef_UIAlertAction_1 = clsRef_UIAlertAction;
    void* (* const var_70)[0x20] = __NSConcreteStackBlock;
    int64_t var_68 = 0xc2000000;
    int64_t (* var_60)(void* arg1) = sub_410b08;
    void* const var_58 = &data_43c100;
    struct ACPanelController* self_1 = self;
    id obj_1 = _objc_retain(obj);
    id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIAlertAction_1, 
        "actionWithTitle:style:handler:", &cfstr_Enter, 0, &var_70));
    _objc_msgSend(obj_1, "addAction:", obj_2);
    _objc_release(obj_2);
    id obj_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIAlertAction, 
        "actionWithTitle:style:handler:", &cfstr_Cancel, 1, 0));
    _objc_msgSend(obj_1, "addAction:", obj_3);
    _objc_release(obj_3);
    _objc_msgSend(self, "presentViewController:animated:completion:", obj_1, 1, 0);
    _objc_release(obj);
    _objc_release(obj_1);
}

int64_t sub_410a90(int64_t arg1, id arg2)
{
    id x0_1 = _objc_retain(arg2);
    _objc_msgSend(arg2, "setSecureTextEntry:", 1);
    _objc_msgSend(arg2, "setKeyboardType:", 4);
    _objc_msgSend(arg2, "setPlaceholder:", &cfstr_Passcode);
    /* tailcall */
    return _objc_release(x0_1);
}

int64_t sub_410b08(void* arg1)
{
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(*(arg1 + 0x20), "textFields"));
    id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj, "firstObject"));
    id x0_4 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_1, "text"));
    _objc_release(obj_1);
    _objc_release(obj);
    
    if (!_objc_msgSend(*(arg1 + 0x28), "_vK:", x0_4))
    {
        sub_410c94(&cfstr_Admin:_Wrong_passcode!);
        id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIAlertController, 
            "alertControllerWithTitle:message:preferredStyle:", &cfstr_Access_Denied, 
            &cfstr_Wrong_passcode, 1));
        id obj_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIAlertAction, 
            "actionWithTitle:style:handler:", &cfstr_OK, 1, 0));
        _objc_msgSend(obj_2, "addAction:", obj_3);
        _objc_release(obj_3);
        _objc_msgSend(*(arg1 + 0x28), "presentViewController:animated:completion:", obj_2, 1, 0);
        _objc_release(obj_2);
    }
    else
    {
        data_446ad0 = 1;
        sub_410c94(&cfstr_Admin:_Welcome!);
        _objc_msgSend(*(arg1 + 0x28), "setActiveTab:", 4);
        _objc_msgSend(*(arg1 + 0x28), "updateTabAppearance");
    }
    
    /* tailcall */
    return _objc_release(x0_4);
}

int64_t sub_410c94(id arg1)
{
    id x0 = _objc_retain(arg1);
    id x0_1 = data_446a78;
    
    if (!x0_1)
    {
        id x0_3 = _objc_msgSend(clsRef_NSMutableString, "new");
        id obj_3 = data_446a78;
        data_446a78 = x0_3;
        _objc_release(obj_3);
        x0_1 = data_446a78;
    }
    
    id var_50 = x0;
    _objc_msgSend(x0_1, "appendFormat:", &cfstr_%@\n);
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(data_446a78, 
        "componentsSeparatedByString:", &cfstr_\n));
    
    if (_objc_msgSend(obj, "count") >= 0x1f)
    {
        id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj, "subarrayWithRange:", 
            _objc_msgSend(obj, "count") - 0x1e));
        id x22_1 = data_446a78;
        id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_1, 
            "componentsJoinedByString:", &cfstr_\n));
        _objc_msgSend(x22_1, "setString:", obj_2);
        _objc_release(obj_2);
        _objc_release(obj_1);
    }
    
    _objc_retainAutorelease(__dispatch_main_q);
    _dispatch_async(__dispatch_main_q, &data_43c650);
    _objc_release(obj);
    /* tailcall */
    return _objc_release(x0);
}

int64_t sub_410df8(int64_t arg1, void* arg2)
{
    _objc_retain(*(arg2 + 0x20));
    /* tailcall */
    return _objc_retain(*(arg2 + 0x28));
}

int64_t sub_410e20(void* arg1)
{
    _objc_release(*(arg1 + 0x28));
    /* tailcall */
    return _objc_release(*(arg1 + 0x20));
}

bool -[ACPanelController _vK:](struct ACPanelController* self, SEL sel, id _vK)
{
    id obj = _objc_retain(_vK);
    id x0_1 = _objc_msgSend(obj, "length");
    int32_t x0_3;
    
    if (x0_1 == 5)
        x0_3 = _objc_msgSend(obj, "characterAtIndex:", 0);
    
    char result;
    
    if (x0_1 != 5 || x0_3 != 0x30)
        result = 0;
    else
    {
        int64_t x21_1 = 0;
        int64_t x24_1;
        int32_t i;
        
        do
        {
            x24_1 = x21_1;
            
            if (x21_1 == 4)
                break;
            
            x21_1 = x24_1 + 1;
            i = _objc_msgSend(obj, "characterAtIndex:", x21_1);
        } while (i == (data_42f0e8[1][x24_1] ^ 0x41));
        result = x24_1 > 3 ? 1 : 0;
    }
    
    _objc_release(obj);
    return result;
}

void -[ACPanelController aiCommandTapped](struct ACPanelController* self, SEL sel)
{
    int64_t v13;
    int64_t var_90 = v13;
    int64_t v12;
    int64_t var_88 = v12;
    int64_t v11;
    int64_t var_80 = v11;
    int64_t v10;
    int64_t var_78 = v10;
    int64_t v9;
    int64_t var_70 = v9;
    int64_t v8;
    int64_t var_68 = v8;
    int64_t x8 = *___stack_chk_guard;
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminInner"));
    id obj_11 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj, "viewWithTag:", 0x37c));
    _objc_release(obj);
    id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_11, "text"));
    id obj_12 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_1, "lowercaseString"));
    _objc_release(obj_1);
    id x0_10;
    
    if (obj_12)
        x0_10 = _objc_msgSend(obj_12, "length");
    
    if (!obj_12 || !x0_10)
        sub_410c94(&cfstr_AI:_No_command_entered);
    else
    {
        id obj_15 = obj_12;
        id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
            "stringWithFormat:", &cfstr_AI:_Processing_'%@'));
        sub_410c94(obj_2);
        _objc_release(obj_2);
        
        if (!_objc_msgSend(obj_12, "hasPrefix:", &cfstr_hey_ai_spawn_))
            sub_410c94(&cfstr_AI:_Command_not_recognized._Use:_Hey_AI_spawn_[item]_[qty]);
        else
        {
            id obj_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_12, 
                "substringFromIndex:", _objc_msgSend(&cfstr_hey_ai_spawn_, "length")));
            id obj_4 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_3, 
                "componentsSeparatedByString:", &cfstr__));
            id obj_5 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_4, "firstObject"));
            uint64_t x8_2;
            
            if (_objc_msgSend(obj_4, "count") < 2)
                x8_2 = 1;
            else
            {
                id obj_6 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_4, 
                    "objectAtIndexedSubscript:", 1));
                int32_t x0_25 = _objc_msgSend(obj_6, "intValue");
                _objc_release(obj_6);
                int32_t x8_1;
                
                x8_1 = x0_25 < 0x1f4 ? x0_25 : 0x1f4;
                
                x8_2 = x8_1 > 1 ? x8_1 : 1;
            }
            
            int128_t var_140;
            __builtin_memset(&var_140, 0, 0x20);
            int128_t var_160;
            __builtin_memset(&var_160, 0, 0x18);
            id obj_7 = _objc_retain(data_446a88);
            void var_120;
            id i_4 = _objc_msgSend(obj_7, "countByEnumeratingWithState:objects:count:", &var_160, 
                &var_120, 0x10);
            id obj_14;
            
            if (i_4)
            {
                id i_3 = i_4;
                int64_t* var_150;
                int64_t x19 = *var_150;
                id i;
                
                do
                {
                    int64_t x20_1 = 0;
                    
                    do
                    {
                        if (*var_150 != x19)
                            _objc_enumerationMutation(obj_7);
                        
                        id obj_13 = *(*(&var_160 + 8) + (x20_1 << 3));
                        id obj_8 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_13, 
                            "lowercaseString"));
                        int32_t x0_31 = _objc_msgSend(obj_8, "containsString:", obj_5);
                        _objc_release(obj_8);
                        
                        if (x0_31 & 1)
                        {
                            obj_14 = _objc_retain(obj_13);
                            _objc_release(obj_7);
                            
                            if (obj_14)
                                goto label_411270;
                            
                            goto label_411250;
                        }
                        
                        x20_1 += 1;
                    } while (i_3 != x20_1);
                    
                    i = _objc_msgSend(obj_7, "countByEnumeratingWithState:objects:count:");
                    i_3 = i;
                } while (i);
            }
            
            _objc_release(obj_7);
        label_411250:
            id obj_16 = obj_5;
            obj_14 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
                "stringWithFormat:"));
        label_411270:
            int32_t v0_1;
            int32_t v1_1;
            int32_t v2_1;
            v0_1 = sub_4113d8();
            v8 = v0_1;
            v10 = v1_1;
            v9 = v2_1;
            id obj_17 = obj_14;
            uint64_t var_1a8_1 = x8_2;
            id obj_9 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
                "stringWithFormat:"));
            sub_410c94(obj_9);
            _objc_release(obj_9);
            v10 = v10 + 1f;
            v11 = -2f;
            int32_t i_2 = x8_2;
            int32_t i_1;
            
            do
            {
                v12 = 0x42c80000;
                v13 = _arc4random_uniform(0x190) / v12 + v11;
                uint32_t x0_45;
                int128_t v2_2;
                x0_45 = _arc4random_uniform(0x190);
                v2_2 = v9 + x0_45 / v12 + v11;
                sub_4114c8(obj_14, v8 + v13);
                i_1 = i_2;
                i_2 -= 1;
            } while (i_1 != 1);
            id obj_18 = obj_14;
            uint64_t var_1a8_2 = x8_2;
            id obj_10 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
                "stringWithFormat:"));
            sub_410c94(obj_10);
            _objc_release(obj_10);
            _objc_release(obj_14);
            _objc_release(obj_5);
            _objc_release(obj_4);
            _objc_release(obj_3);
        }
        
        _objc_msgSend(obj_11, "setText:", &cfstr_);
    }
    
    _objc_release(obj_12);
    _objc_release(obj_11);
    
    if (*___stack_chk_guard == x8)
        return;
    
    ___stack_chk_fail();
    /* no return */
}

int64_t sub_4113d8()
{
    int64_t var_40 = 0x4020000000000000;
    int32_t var_38 = 0;
    int64_t result = data_446b38;
    int128_t v1;
    int128_t v2;
    int64_t v8;
    int64_t v9;
    int128_t v0;
    
    if (!result)
    {
        v8 = 2.5f;
        v9 = 0f;
        v0 = 0f;
    }
    else
    {
        int64_t var_48 = 0;
        result = data_446b08(result, 0, 0, &var_48);
        v8 = 2.5f;
        v9 = 0f;
        bool z_1;
        
        z_1 = result ? !var_48 : false;
        
        if (!z_1)
            v0 = 0f;
        else
        {
            int64_t result_1 = result;
            result = data_446b40;
            bool z_2;
            
            if (result)
                z_2 = !data_446b48;
            else
                z_2 = true;
            
            if (z_2)
                v0 = 0f;
            else
            {
                var_48 = 0;
                result = data_446b08(result, result_1, 0, &var_48);
                
                if (!result)
                    v0 = 0f;
                else
                {
                    v0 = 0f;
                    
                    if (!var_48)
                    {
                        int128_t v0_1;
                        result = data_446b48(result, &var_40, v0);
                        v0_1 = var_40;
                        v8 = *(&var_40 + 4);
                        v9 = var_38;
                    }
                }
            }
        }
    }
    v1 = v8;
    v2 = v9;
    return result;
}

int64_t sub_4114c8(id arg1, int32_t arg2 @ v0)
{
    int64_t x8 = *___stack_chk_guard;
    int32_t var_198 = arg2;
    int32_t v1;
    int32_t var_194 = v1;
    int32_t v2;
    int32_t var_190 = v2;
    id obj = _objc_retain(arg1);
    int64_t x0_1 = sub_42172c(data_446b98);
    int64_t x23 = data_446ba0;
    id obj_1 = _objc_retainAutorelease(obj);
    _objc_msgSend(obj_1, "UTF8String");
    x23();
    int128_t var_1b0 = data_42f160;
    int64_t var_168;
    int32_t var_158;
    
    if (data_446774 & 0x80000000)
    {
        int64_t x24_1 = 0;
        int64_t x8_3 = data_446ba8;
        var_168 = x8_3;
        int64_t var_160_2 = 0;
        int32_t* x25_1 = &var_158;
        var_158 = 4;
        char const* const var_150_2 = "TRY-SI4s";
        int64_t var_148_1 = x8_3;
        int64_t var_140_1 = x0_1;
        int32_t var_138_1 = 4;
        int64_t x11_2 = data_446bb0;
        char const* const var_130_1 = "TRY-SI4i";
        int64_t var_128_1 = x11_2;
        int64_t var_120_1 = 0;
        int32_t var_118_1 = 1;
        char const* const var_110_1 = "TRY-SI1s";
        int64_t var_108_1 = x11_2;
        int64_t var_100_1 = x0_1;
        int32_t var_f8_1 = 1;
        int64_t x12_1 = data_446bb8;
        char const* const var_f0_1 = "TRY-SI1i";
        int64_t var_e8_1 = x12_1;
        int64_t var_e0_1 = 0;
        int32_t var_d8_1 = 4;
        char const* const var_d0_1 = "TRY-SIA4s";
        int64_t var_c8_1 = x12_1;
        int64_t var_c0_1 = x0_1;
        int32_t var_b8_1 = 4;
        char const* const var_b0_1 = "TRY-SIA4i";
        int64_t var_a8_1 = x12_1;
        int64_t var_a0_1 = 0;
        int32_t var_98_1 = 1;
        char const* const var_90_1 = "TRY-SIA1s";
        int64_t var_88_1 = x12_1;
        int64_t var_80_1 = x0_1;
        int32_t var_78_1 = 1;
        char const* const var_70_1 = "TRY-SIA1i";
        
        if (x8_3)
            goto label_411694;
        
        while (true)
        {
            if (x24_1 == 7)
            {
                id obj_3 = obj_1;
                id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
                    "stringWithFormat:", &cfstr_[ERR]_All_item_approaches_failed:_%@));
                sub_410c94(obj_2);
                _objc_release(obj_2);
                goto label_411830;
            }
            
            int64_t x8_5 = *(x25_1 + 0x10);
            x25_1 = &x25_1[8];
            x24_1 += 1;
            
            if (x8_5)
            {
            label_411694:
                int64_t x27_1 = data_446ba0;
                _objc_msgSend(_objc_retainAutorelease(obj_1), "UTF8String");
                int64_t x0_9 = x27_1();
                int64_t var_188;
                
                if (*x25_1 != 4)
                {
                    var_188 = x0_9;
                    *(x25_1 + 8);
                    
                    if (!sub_42d16c(*(x25_1 - 0x10), *(x25_1 - 8), &var_188))
                        continue;
                }
                else
                {
                    var_188 = x0_9;
                    int32_t* var_180_1 = &var_198;
                    int128_t* var_178_1 = &var_1b0;
                    int64_t var_170_1 = 0;
                    *(x25_1 + 8);
                    
                    if (!(sub_42d16c(*(x25_1 - 0x10), *(x25_1 - 8), &var_188) & 1))
                        continue;
                }
                data_446774 = x24_1;
                break;
            }
        }
    }
    else
    {
        int64_t x22_1 = data_446ba0;
        _objc_msgSend(_objc_retainAutorelease(obj_1), "UTF8String");
        int64_t x0_5 = x22_1();
        uint64_t x8_2 = data_446774;
        
        if (x8_2 <= 7)
        {
            int64_t x0_6;
            int64_t x1_3;
            int64_t* x2_3;
            
            switch (x8_2)
            {
                case 0:
                {
                    var_168 = x0_5;
                    int32_t* var_160_1 = &var_198;
                    var_158 = &var_1b0;
                    int64_t var_150_1 = 0;
                    x0_6 = data_446ba8;
                    x2_3 = &var_168;
                    x1_3 = 0;
                    break;
                }
                case 1:
                {
                    var_168 = x0_5;
                    int32_t* var_160_3 = &var_198;
                    var_158 = &var_1b0;
                    int64_t var_150_3 = 0;
                    x0_6 = data_446ba8;
                    x2_3 = &var_168;
                    x1_3 = x0_1;
                    break;
                }
                case 2:
                {
                    var_168 = x0_5;
                    x0_6 = data_446bb0;
                    x2_3 = &var_168;
                    x1_3 = 0;
                    break;
                }
                case 3:
                {
                    var_168 = x0_5;
                    x0_6 = data_446bb0;
                    x2_3 = &var_168;
                    x1_3 = x0_1;
                    break;
                }
                case 4:
                {
                    var_168 = x0_5;
                    int32_t* var_160_4 = &var_198;
                    var_158 = &var_1b0;
                    int64_t var_150_4 = 0;
                    x0_6 = data_446bb8;
                    x2_3 = &var_168;
                    x1_3 = 0;
                    break;
                }
                case 5:
                {
                    var_168 = x0_5;
                    int32_t* var_160_5 = &var_198;
                    var_158 = &var_1b0;
                    int64_t var_150_5 = 0;
                    x0_6 = data_446bb8;
                    x2_3 = &var_168;
                    x1_3 = x0_1;
                    break;
                }
                case 6:
                {
                    var_168 = x0_5;
                    x0_6 = data_446bb8;
                    x2_3 = &var_168;
                    x1_3 = 0;
                    break;
                }
                case 7:
                {
                    var_168 = x0_5;
                    x0_6 = data_446bb8;
                    x2_3 = &var_168;
                    x1_3 = x0_1;
                    break;
                }
            }
            
            sub_42d16c(x0_6, x1_3, x2_3);
        }
    }
label_411830:
    int64_t result = _objc_release(obj_1);
    
    if (*___stack_chk_guard == x8)
        return result;
    
    ___stack_chk_fail();
    /* no return */
}

void -[ACPanelController adminSpawn100](struct ACPanelController* self, SEL sel)
{
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "selectedItemNameOrDefault"));
    float v0;
    int32_t v1;
    float v2;
    v0 = sub_4113d8();
    int64_t v10;
    v10 = v1;
    id obj_3 = obj;
    id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
        "stringWithFormat:", &cfstr_Admin:_spawning_%@_x100));
    sub_410c94(obj_1);
    _objc_release(obj_1);
    v10 = v10 + 0.5f;
    double v11 = 0.0;
    int32_t i_1 = 0x64;
    int64_t v12;
    v12 = -5f;
    id obj_2;
    int32_t i;
    
    do
    {
        float v8_1 = 0x42c80000;
        float v9_1 = _arc4random_uniform(0x3e8) / v8_1 + v12;
        uint32_t x0_5;
        double v0_3;
        x0_5 = _arc4random_uniform(0x3e8);
        v0_3 = x0_5;
        v0_3 = v0_3 / v8_1;
        v0_3 = v0_3 + v12;
        dispatch_time_t when = _dispatch_time(0, vcvtd_s64_f64(v11 * 0.02 * 1000000000.0));
        _objc_retainAutorelease(__dispatch_main_q);
        void* (* const var_d8)[0x20] = __NSConcreteStackBlock;
        int64_t var_d0_1 = 0xc2000000;
        int64_t (* var_c8_1)(void* arg1) = sub_411a2c;
        void* const var_c0_1 = &data_43c130;
        obj_2 = _objc_retain(obj);
        float var_b0_1 = v0 + v9_1;
        int32_t var_ac_1 = v10;
        float var_a8_1 = v2 + v0_3;
        _dispatch_after(when, __dispatch_main_q, &var_d8);
        _objc_release(obj_2);
        v11 = v11 + 1.0;
        i = i_1;
        i_1 -= 1;
    } while (i != 1);
    _objc_release(obj_2);
}

int64_t sub_411a2c(void* arg1)
{
    int128_t v1;
    v1 = *(arg1 + 0x2c);
    int128_t v2;
    v2 = *(arg1 + 0x30);
    /* tailcall */
    return sub_4114c8(*(arg1 + 0x20), *(arg1 + 0x28));
}

void -[ACPanelController adminSpawnAll](struct ACPanelController* self, SEL sel)
{
    int64_t v15;
    int64_t var_a0 = v15;
    int64_t v14;
    int64_t var_98 = v14;
    int64_t v13;
    int64_t var_90 = v13;
    int64_t v12;
    int64_t var_88 = v12;
    int64_t v11;
    int64_t var_80 = v11;
    float v0;
    int32_t v1;
    int32_t v2;
    v0 = sub_4113d8();
    int64_t v10;
    v10 = v1;
    struct objc_class_t* clsRef_NSString_1 = clsRef_NSString;
    id var_f0 = _objc_msgSend(data_446a88, "count");
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString_1, 
        "stringWithFormat:", &cfstr_Admin:_spawning_ALL_%lu_items!));
    sub_410c94(obj);
    _objc_release(obj);
    
    if (_objc_msgSend(data_446a88, "count") < 1)
        return;
    
    int64_t x20_1 = 0;
    v10 = v10 + 1f;
    v11 = -10f;
    id x0_17;
    
    do
    {
        id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(data_446a88, 
            "objectAtIndexedSubscript:", x20_1));
        v15 = 0x42c80000;
        float v8_1 = _arc4random_uniform(0x7d0) / v15 + v11;
        uint32_t x0_10;
        double v0_3;
        x0_10 = _arc4random_uniform(0x7d0);
        v0_3 = x0_10;
        v0_3 = v0_3 / v15;
        v0_3 = v0_3 + v11;
        v15 = v2 + v0_3;
        dispatch_time_t when =
            _dispatch_time(0, vcvtd_s64_f64(x20_1 * 0.029999999999999999 * 1000000000.0));
        _objc_retainAutorelease(__dispatch_main_q);
        void* (* const var_d8)[0x20] = __NSConcreteStackBlock;
        int64_t var_d0_1 = 0xc2000000;
        int64_t (* var_c8_1)(void* arg1) = sub_411c40;
        void* const var_c0_1 = &data_43c130;
        float var_b0_1 = v0 + v8_1;
        int32_t var_ac_1 = v10;
        int32_t var_a8_1 = v15;
        id obj_2 = _objc_retain(obj_1);
        _dispatch_after(when, __dispatch_main_q, &var_d8);
        _objc_release(obj_1);
        _objc_release(obj_2);
        x20_1 += 1;
        x0_17 = _objc_msgSend(data_446a88, "count");
    } while (x20_1 < x0_17);
}

int64_t sub_411c40(void* arg1)
{
    int128_t v1;
    v1 = *(arg1 + 0x2c);
    int128_t v2;
    v2 = *(arg1 + 0x30);
    /* tailcall */
    return sub_4114c8(*(arg1 + 0x20), *(arg1 + 0x28));
}

void -[ACPanelController followApproachTapped:](struct ACPanelController* self, SEL sel, id followApproachTapped)
{
    id obj = _objc_retain(followApproachTapped);
    id x0_1;
    int64_t x2;
    int64_t x3;
    int64_t x4;
    int64_t x5;
    int128_t v0;
    int128_t v1;
    int128_t v2;
    int128_t v3;
    x0_1 = _objc_msgSend(obj, "tag");
    int32_t x8 = data_446770;
    bool z;
    
    if (data_446ad1 == 1)
        z = x8 == (x0_1 - 0xbb8);
    else
        z = false;
    
    id obj_9;
    
    if (z)
    {
        data_446ad1 = 0;
        data_446770 = 0xffffffff;
        id x0_25 = data_446a50;
        
        if (x0_25)
        {
            _objc_msgSend(x0_25, "invalidate");
            id obj_10 = data_446a50;
            data_446a50 = 0;
            x2 = _objc_release(obj_10);
        }
        
        v0 = 0x3fc3333333333333;
        v1 = 0x3fbeb851eb851eb8;
        v2 = 0x3fd3333333333333;
        v3 = 1.0;
        int64_t obj_11 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
            "colorWithRed:green:blue:alpha:", x2, x3, x4, x5));
        _objc_msgSend(obj, "setBackgroundColor:", obj_11);
        _objc_release(obj_11);
        void* __offset(objc_object, -0xbb7) var_c0_1 = x0_1 - 0xbb7;
        id obj_14 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
            "stringWithFormat:", &cfstr_Follow_approach_%ld_stopped));
        sub_410c94(obj_14);
        obj_9 = obj_14;
    }
    else
    {
        id x0_2 = data_446a50;
        
        if (x0_2)
        {
            _objc_msgSend(x0_2, "invalidate");
            id obj_1 = data_446a50;
            data_446a50 = 0;
            _objc_release(obj_1);
            x8 = data_446770;
        }
        
        if (!(x8 & 0x80000000))
        {
            id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminInner"));
            id obj_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_2, "viewWithTag:", 
                data_446770 + 0xbb8));
            int64_t x2_2;
            int64_t x3_1;
            int64_t x4_1;
            int64_t x5_1;
            int128_t v0_1;
            int128_t v1_1;
            int128_t v2_1;
            int128_t v3_1;
            x2_2 = _objc_release(obj_2);
            v0_1 = 0x3fc3333333333333;
            v1_1 = 0x3fbeb851eb851eb8;
            v2_1 = 0x3fd3333333333333;
            v3_1 = 1.0;
            id obj_4 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
                "colorWithRed:green:blue:alpha:", x2_2, x3_1, x4_1, x5_1));
            _objc_msgSend(obj_3, "setBackgroundColor:", obj_4);
            _objc_release(obj_4);
            _objc_release(obj_3);
        }
        
        data_446ad1 = 1;
        data_446770 = (x0_1 - 0xbb8);
        
        if (!data_446a58)
        {
            id obj_5 = data_446a58;
            data_446a58 = &cfstr_item_goldbar;
            _objc_release(obj_5);
        }
        
        id obj_6 =
            _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "selectedItemNameOrDefault"));
        int64_t x2_4;
        int64_t x3_2;
        int64_t x4_2;
        int64_t x5_2;
        int128_t v0_2;
        int128_t v2_2;
        int128_t v3_2;
        x2_4 = _objc_storeStrong(&data_446a58, obj_6);
        v0_2 = 0x3fe999999999999a;
        v3_2 = 1.0;
        v2_2 = 0x3fc999999999999a;
        int64_t obj_7 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
            "colorWithRed:green:blue:alpha:", x2_4, x3_2, x4_2, x5_2));
        _objc_msgSend(obj, "setBackgroundColor:", obj_7);
        _objc_release(obj_7);
        void* __offset(objc_object, -0xbb7) var_c0 = x0_1 - 0xbb7;
        id obj_13 = obj_6;
        id obj_8 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
            "stringWithFormat:", &cfstr_Follow_approach_%ld:_%@));
        sub_410c94(obj_8);
        int64_t x4_3 = _objc_release(obj_8);
        *(&data_42f0f0 + ((x0_1 - 0xbb8) << 2));
        int64_t var_80 = 0;
        int64_t* var_78_1 = &var_80;
        int64_t var_70_1 = 0x2020000000;
        int32_t var_68_1 = 0;
        struct objc_class_t* clsRef_NSTimer_1 = clsRef_NSTimer;
        void* (* const var_b0)[0x20] = __NSConcreteStackBlock;
        int64_t var_a8_1 = 0xc2000000;
        int64_t (* var_a0_1)(void* arg1, id arg2) = sub_412010;
        void* const var_98_1 = &data_43c160;
        int64_t* var_90_1 = &var_80;
        void* __offset(objc_object, -0xbb8) var_88_1 = x0_1 - 0xbb8;
        id x0_22 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSTimer_1, 
            "scheduledTimerWithTimeInterval:repeats:block:", 1, &var_b0, x4_3));
        id obj_12 = data_446a50;
        data_446a50 = x0_22;
        _objc_release(obj_12);
        __Block_object_dispose(&var_80, 8);
        obj_9 = obj_6;
    }
    
    _objc_release(obj_9);
    _objc_release(obj);
}

int64_t sub_412010(void* arg1, id arg2)
{
    int64_t v13;
    int64_t var_90 = v13;
    int64_t v12;
    int64_t var_88 = v12;
    int64_t v11;
    int64_t var_80 = v11;
    
    if (!(data_446ad1 & 1))
    {
        _objc_msgSend(arg2, "invalidate");
        id x0_17 = data_446a50;
        data_446a50 = 0;
        /* tailcall */
        return _objc_release(x0_17);
    }
    
    float v0;
    int32_t v1;
    float v2;
    v0 = sub_4113d8();
    float v8 = v0;
    int64_t v10;
    v10 = v1;
    float v9 = v2;
    
    if (_objc_msgSend(data_446a60, "length"))
    {
        sub_412450();
        
        if (_objc_msgSend(data_4469e0, "count") >= 1)
        {
            int64_t x21_1 = 0;
            id x0_15;
            
            do
            {
                id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(data_4469e0, 
                    "objectAtIndexedSubscript:", x21_1));
                id obj_1 =
                    _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj, "lowercaseString"));
                id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(data_446a60, 
                    "lowercaseString"));
                int32_t x0_10 = _objc_msgSend(obj_1, "containsString:", obj_2);
                _objc_release(obj_2);
                _objc_release(obj_1);
                _objc_release(obj);
                
                if (x0_10)
                {
                    id obj_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(data_4469e8, 
                        "objectAtIndexedSubscript:", x21_1));
                    
                    if (_objc_msgSend(obj_3, "isKindOfClass:", 
                        _objc_msgSend(clsRef_NSValue, "class")))
                    {
                        float v0_3;
                        int32_t v1_3;
                        float v2_3;
                        v0_3 = sub_4127a8(_objc_msgSend(obj_3, "pointerValue"));
                        v8 = v0_3;
                        v10 = v1_3;
                        v9 = v2_3;
                    }
                    
                    _objc_release(obj_3);
                    break;
                }
                
                x21_1 += 1;
                x0_15 = _objc_msgSend(data_4469e0, "count");
            } while (x21_1 < x0_15);
        }
    }
    
    void* x8_3 = *(*(arg1 + 0x20) + 8);
    int32_t x9_1 = *(x8_3 + 0x18);
    *(x8_3 + 0x18) = x9_1 + 1;
    uint64_t x8_4 = *(arg1 + 0x28);
    
    if (x8_4 <= 0x13)
    {
        float v0_1 = x9_1 * 0.5f;
        float v1_1;
        float v2_1;
        
        switch (x8_4)
        {
            case 0:
            {
                v10 = v10 + 1f;
                break;
            }
            case 1:
            {
                v10 = v10 + 1f;
                break;
            }
            case 2:
            {
                v10 = v10 + 1f;
                break;
            }
            case 3:
            {
                v10 = v10 + 2.5f;
                break;
            }
            case 4:
            {
                v0_1 = -1.5f;
            label_412294:
                v8 = v8 + v0_1;
                v10 = v10 + 1f;
                break;
            }
            case 5:
            {
                v0_1 = 1.5f;
                goto label_412294;
            }
            case 6:
            {
                v10 = v10 + 0.800000012f;
                break;
            }
            case 7:
            {
                v0_1 = ___sincosf_stret(v0_1);
                v2_1 = 2f;
                v8 = vfma_f32(v8, v1_1, v2_1);
                v10 = v10 + 1.5f;
                vfma_f32(v9, v0_1, v2_1);
                break;
            }
            case 8:
            {
                v0_1 = ___sincosf_stret(v0_1);
                v2_1 = 2f;
                v8 = vfma_f32(v8, v1_1, v2_1);
                v10 = v10 + 1.5f;
                vfms_f64(v9, v0_1, v2_1);
                break;
            }
            case 9:
            {
                v10 = v10 + 1f;
                break;
            }
            case 0xa:
            {
                v10 = v10 + 1f;
                break;
            }
            case 0xb:
            {
                v10 = v10 + -0.300000012f;
                break;
            }
            case 0xc:
            {
                v10 = v10 + 1f;
                break;
            }
            case 0xd:
            {
                v8 = v8 + -1f;
                v10 = v10 + 1f;
                break;
            }
            case 0xe:
            {
                v0_1 = 1f;
                v8 = v8 + v0_1;
                v10 = v10 + v0_1;
                break;
            }
            case 0xf:
            {
                v0_1 = ___sincosf_stret(v0_1);
                v8 = vfma_f32(v8, v1_1, 0.800000012f);
                v10 = v10 + 2f;
                vfma_f32(v9, v0_1, 0.800000012f);
                break;
            }
            case 0x10:
            {
                v10 = v10 + 0.100000001f;
                break;
            }
            case 0x11:
            {
                v0_1 = ___sincosf_stret(v0_1 * 0.300000012f);
                v2_1 = 1.5f;
                v8 = vfma_f32(v8, v1_1, v2_1);
                v10 = v10 + 1.20000005f;
                vfma_f32(v9, v0_1, v2_1);
                break;
            }
            case 0x12:
            {
                v11 = v10 + 1f;
                sub_4114c8(data_446a58, v8);
                v10 = v11;
                break;
            }
            case 0x13:
            {
                v11 = 0x42c80000;
                v12 = -1f;
                v13 = _arc4random_uniform(0xc8) / v11 + v12;
                _arc4random_uniform(0xc8);
                v8 = v8 + v13;
                v10 = v10 + 1f;
                break;
            }
        }
    }
    
    /* tailcall */
    return sub_4114c8(data_446a58, v8);
}

int64_t sub_412450()
{
    int64_t x8 = *___stack_chk_guard;
    
    if (!data_4469e0)
    {
        id x0_2 = _objc_msgSend(clsRef_NSMutableArray, "new");
        id obj_3 = data_4469e0;
        data_4469e0 = x0_2;
        _objc_release(obj_3);
    }
    
    if (!data_4469e8)
    {
        id x0_5 = _objc_msgSend(clsRef_NSMutableArray, "new");
        id obj_4 = data_4469e8;
        data_4469e8 = x0_5;
        _objc_release(obj_4);
    }
    
    _objc_msgSend(data_4469e0, "removeAllObjects");
    _objc_msgSend(data_4469e8, "removeAllObjects");
    int64_t x0_9 = data_446bc0;
    bool z;
    
    if (x0_9)
        z = !data_446af0;
    else
        z = true;
    
    if (!z && data_446af8(x0_9))
    {
        int64_t x0_11 = data_446b00();
        
        if (x0_11)
        {
            int64_t var_78 = 0;
            int64_t var_70 = x0_11;
            void* x0_13 = data_446b08(data_446af0, 0, &var_70, &var_78);
            
            if (x0_13 && !var_78)
            {
                uint64_t x20_1 = *(x0_13 + 0x18);
                
                if (x20_1 - 1 <= 0x62)
                {
                    int64_t x23_1 = 0;
                    
                    do
                    {
                        int64_t x24_1 = *(x0_13 + 0x20 + (x23_1 << 3));
                        
                        if (x24_1)
                        {
                            int64_t var_a0_1 = x23_1;
                            id obj_5 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(
                                clsRef_NSString, "stringWithFormat:"));
                            int64_t x0_17 = data_446bc8;
                            
                            if (x0_17)
                            {
                                var_78 = 0;
                                void* x0_18 = data_446b08(x0_17, x24_1, 0, &var_78);
                                bool z_1;
                                
                                z_1 = x0_18 ? !var_78 : false;
                                
                                if (z_1 && *(x0_18 + 0x10) - 1 <= 0xfe)
                                {
                                    id x0_20 = _objc_alloc(clsRef_NSString);
                                    *(x0_18 + 0x10);
                                    id obj_6 = _objc_msgSend(x0_20, "initWithCharacters:length:");
                                    _objc_release(obj_5);
                                    obj_5 = obj_6;
                                }
                            }
                            
                            _objc_msgSend(data_4469e0, "addObject:", obj_5);
                            id x26_3 = data_4469e8;
                            id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(
                                clsRef_NSValue, "valueWithPointer:"));
                            _objc_msgSend(x26_3, "addObject:", obj);
                            _objc_release(obj);
                            _objc_release(obj_5);
                        }
                        
                        x23_1 += 1;
                    } while (x20_1 != x23_1);
                }
            }
        }
    }
    
    if (!_objc_msgSend(data_4469e0, "count"))
    {
        _objc_msgSend(data_4469e0, "addObject:", &cfstr_Local_Player);
        id x21_1 = data_4469e8;
        id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNull, "null"));
        _objc_msgSend(x21_1, "addObject:", obj_1);
        _objc_release(obj_1);
    }
    
    struct objc_class_t* clsRef_NSString_1 = clsRef_NSString;
    id var_a0_2 = _objc_msgSend(data_4469e0, "count");
    id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString_1, 
        "stringWithFormat:", &cfstr_Found_%lu_players));
    sub_410c94(obj_2);
    int64_t result = _objc_release(obj_2);
    
    if (*___stack_chk_guard == x8)
        return result;
    
    ___stack_chk_fail();
    /* no return */
}

int128_t sub_4127a8(int64_t arg1)
{
    int64_t var_30 = 0x4020000000000000;
    int32_t var_28 = 0;
    int128_t result;
    
    if (!arg1)
        result = 0f;
    else
    {
        int64_t x0 = data_446b40;
        bool z_1;
        
        if (x0)
            z_1 = !data_446b48;
        else
            z_1 = true;
        
        result = 0f;
        
        if (!z_1)
        {
            int64_t var_38 = 0;
            int64_t x0_1;
            int128_t v1_1;
            int128_t v2_1;
            x0_1 = data_446b08(x0, arg1, 0, &var_38, result);
            bool z_2;
            
            z_2 = x0_1 ? !var_38 : false;
            
            if (z_2)
            {
                int128_t v1_2;
                int128_t v2_2;
                result = data_446b48(x0_1, &var_30);
                result = var_30;
                v1_2 = *(&var_30 + 4);
                v2_2 = var_28;
            }
            else
            {
                v1_1 = 2.5f;
                v2_1 = 0f;
                result = 0f;
            }
        }
    }
    
    return result;
}

int64_t sub_41285c(void* arg1, void* arg2)
{
    /* tailcall */
    return __Block_object_assign(arg1 + 0x20, *(arg2 + 0x20), 8);
}

int64_t sub_41286c(void* arg1)
{
    /* tailcall */
    return __Block_object_dispose(*(arg1 + 0x20), 8);
}

void -[ACPanelController saveUsernameTapped](struct ACPanelController* self, SEL sel)
{
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminInner"));
    id x19 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj, "viewWithTag:", 0x380));
    _objc_release(obj);
    id x0_6 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(x19, "text"));
    id obj_7 = data_446a60;
    data_446a60 = x0_6;
    _objc_release(obj_7);
    
    if (!_objc_msgSend(data_446a60, "length"))
        sub_410c94(&cfstr_Username:_cleared);
    else
    {
        int64_t var_80_1 = data_446a60;
        id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
            "stringWithFormat:", &cfstr_Username_saved:_%@));
        sub_410c94(obj_1);
        _objc_release(obj_1);
        sub_412450();
        
        if (_objc_msgSend(data_4469e0, "count") < 1)
        {
        label_412a34:
            sub_410c94(&cfstr_Player_rig_not_found_by_name_?_follow_approaches_will_use_local_player_position);
        }
        else
        {
            int64_t x22_1 = 0;
            
            while (true)
            {
                id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(data_4469e0, 
                    "objectAtIndexedSubscript:", x22_1));
                id obj_3 =
                    _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_2, "lowercaseString"));
                id obj_4 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(data_446a60, 
                    "lowercaseString"));
                int32_t x0_21 = _objc_msgSend(obj_3, "containsString:", obj_4);
                _objc_release(obj_4);
                _objc_release(obj_3);
                _objc_release(obj_2);
                
                if (x0_21)
                {
                    struct objc_class_t* clsRef_NSString_1 = clsRef_NSString;
                    id obj_5 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(data_4469e0, 
                        "objectAtIndexedSubscript:", x22_1));
                    id obj_8 = obj_5;
                    id obj_6 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString_1, 
                        "stringWithFormat:"));
                    sub_410c94(obj_6);
                    _objc_release(obj_6);
                    _objc_release(obj_5);
                    break;
                }
                
                x22_1 += 1;
                
                if (x22_1 >= _objc_msgSend(data_4469e0, "count"))
                    goto label_412a34;
            }
        }
    }
    
    /* tailcall */
    return _objc_release(x19);
}

void -[ACPanelController spellTextTapped](struct ACPanelController* self, SEL sel)
{
    int64_t v15;
    int64_t var_a0 = v15;
    int64_t v14;
    int64_t var_98 = v14;
    int64_t v13;
    int64_t var_90 = v13;
    int64_t v12;
    int64_t var_88 = v12;
    int64_t v11;
    int64_t var_80 = v11;
    int64_t v10;
    int64_t var_78 = v10;
    int64_t v9;
    int64_t var_70 = v9;
    int64_t v8;
    int64_t var_68 = v8;
    int64_t x8 = *___stack_chk_guard;
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminInner"));
    id obj_5 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj, "viewWithTag:", 0x381));
    _objc_release(obj);
    id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_5, "text"));
    id obj_6 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_1, "uppercaseString"));
    _objc_release(obj_1);
    
    if (!_objc_msgSend(obj_6, "length"))
        sub_410c94(&cfstr_Spell:_Enter_text_first!);
    else
    {
        float v0_1;
        int32_t v1_1;
        int32_t v2_1;
        v0_1 = sub_4113d8();
        v10 = v1_1;
        v9 = v2_1;
        id obj_7 = obj_6;
        id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
            "stringWithFormat:", &cfstr_Spelling:_%@));
        sub_410c94(obj_2);
        _objc_release(obj_2);
        uint64_t x25_1;
        
        if (_objc_msgSend(obj_6, "length") < 1)
            x25_1 = 0;
        else
        {
            x25_1 = 0;
            int64_t x27_1 = 0;
            float var_1b4_1 = v10 + 3f;
            v9 = v9 + 5f;
            id obj_9 = obj_6;
            int64_t x0_29;
            
            do
            {
                _objc_msgSend(obj_6, "characterAtIndex:");
                int64_t x0_19 = _objc_msgSend(obj_6, "length");
                id obj_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "dotsForChar:"));
                int128_t var_170;
                __builtin_memset(&var_170, 0, 0x18);
                int128_t var_150;
                __builtin_memset(&var_150, 0, 0x20);
                int64_t i_2 = _objc_msgSend(obj_3, "countByEnumeratingWithState:objects:count:");
                
                if (i_2)
                {
                    int64_t i_1 = i_2;
                    v8 = vfma_f32(vfma_f32(v0_1, x27_1, 4f), x0_19 * -4f, 0.5f);
                    int64_t* var_160;
                    int64_t x26_1 = *var_160;
                    int32_t x22;
                    int64_t x27_2;
                    int64_t i;
                    
                    do
                    {
                        x27_2 = 0;
                        x22 = x25_1;
                        
                        do
                        {
                            if (*var_160 != x26_1)
                                _objc_enumerationMutation(obj_3);
                            
                            double var_180;
                            _objc_msgSend(*(*(&var_170 + 8) + (x27_2 << 3)), "getValue:", &var_180);
                            double v0_4;
                            v0_4 = var_180;
                            v11 = vfma_f32(v8, v0_4, 0.400000006f);
                            int64_t var_178;
                            v0_4 = var_178;
                            int64_t v1_3;
                            v1_3 = 4f;
                            v0_4 = v1_3 - v0_4;
                            v1_3 = var_1b4_1;
                            v10 = vfma_f32(v1_3, v0_4, 0.400000006f);
                            dispatch_time_t when = _dispatch_time(0, 
                                vcvtd_s64_f64((x22 + x27_2) * 0.029999999999999999 * 1000000000.0));
                            _objc_retainAutorelease(__dispatch_main_q);
                            void* (* const var_1b0)[0x20] = __NSConcreteStackBlock;
                            int64_t var_1a8_1 = 0xc0000000;
                            int64_t (* var_1a0_1)(void* arg1) = sub_412ed0;
                            void* const var_198_1 = &data_43c190;
                            int32_t var_190_1 = v11;
                            int32_t var_18c_1 = v10;
                            int32_t var_188_1 = v9;
                            _dispatch_after(when, __dispatch_main_q, &var_1b0);
                            x27_2 += 1;
                        } while (i_1 != x27_2);
                        
                        i = _objc_msgSend(obj_3, "countByEnumeratingWithState:objects:count:");
                        i_1 = i;
                        x25_1 = x22 + x27_2;
                    } while (i);
                    x25_1 = x22 + x27_2;
                    obj_6 = obj_9;
                }
                
                _objc_release(obj_3);
                x27_1 += 1;
                x0_29 = _objc_msgSend(obj_6, "length");
            } while (x27_1 < x0_29);
        }
        
        id obj_8 = obj_6;
        uint64_t var_218_1 = x25_1;
        id obj_4 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
            "stringWithFormat:"));
        sub_410c94(obj_4);
        _objc_release(obj_4);
    }
    
    _objc_release(obj_6);
    _objc_release(obj_5);
    
    if (*___stack_chk_guard == x8)
        return;
    
    ___stack_chk_fail();
    /* no return */
}

int64_t sub_412ed0(void* arg1)
{
    int128_t v1;
    v1 = *(arg1 + 0x24);
    int128_t v2;
    v2 = *(arg1 + 0x28);
    /* tailcall */
    return sub_4114c8(&cfstr_item_stash_grenade, *(arg1 + 0x20));
}

id -[ACPanelController dotsForChar:](struct ACPanelController* self, SEL sel, uint16_t dotsForChar)
{
    id obj = _objc_msgSend(clsRef_NSMutableArray, "new");
    void* (* const var_58)[0x20] = __NSConcreteStackBlock;
    int64_t var_50 = 0xc2000000;
    int64_t (* var_48)(void* arg1, int32_t arg2, int64_t arg3) = sub_413af8;
    void* const var_40 = &data_43c1b0;
    id obj_1 = _objc_retain(obj);
    id obj_2 = _objc_retainBlock(&var_58);
    uint64_t x8 = dotsForChar - 0x20;
    id obj_4;
    id obj_6;
    id obj_8;
    id obj_9;
    id obj_10;
    id obj_11;
    id obj_12;
    id obj_13;
    id obj_14;
    id obj_15;
    id obj_16;
    id obj_18;
    int64_t x1;
    int64_t x1_2;
    int64_t x1_4;
    int64_t x1_5;
    int64_t x1_6;
    int64_t x1_7;
    int64_t x1_8;
    int64_t x1_9;
    int64_t x1_10;
    int64_t x1_11;
    int64_t x1_12;
    int64_t x1_14;
    int64_t x2;
    int64_t x2_1;
    int64_t x2_2;
    int64_t x2_3;
    int64_t x8_4;
    int64_t x8_15;
    int64_t x8_19;
    int64_t x8_28;
    int64_t x8_33;
    int64_t x8_37;
    int64_t x8_48;
    int64_t x8_55;
    int64_t x8_61;
    int64_t x8_64;
    int64_t x8_66;
    int64_t x8_83;
    int64_t x8_84;
    int64_t x8_92;
    int64_t x8_103;
    id obj_5;
    id obj_7;
    id obj_17;
    int64_t x1_1;
    int64_t x1_3;
    int64_t x1_13;
    int64_t x2_5;
    int64_t x8_13;
    int64_t x8_24;
    int64_t x8_85;
    int64_t x21_1;
    
    if (x8 > 0x3a)
    {
    label_412fd8:
        (*(obj_2 + 0x10))(obj_2, 0, 0);
        (*(obj_2 + 0x10))(obj_2, 1, 0);
        x21_1 = 2;
        (*(obj_2 + 0x10))(obj_2, 2, 0);
        (*(obj_2 + 0x10))(obj_2, 0, 1);
        (*(obj_2 + 0x10))(obj_2, 2, 1);
        (*(obj_2 + 0x10))(obj_2, 0, 2);
        (*(obj_2 + 0x10))(obj_2, 2, 2);
        (*(obj_2 + 0x10))(obj_2, 0, 3);
        x8_13 = *(obj_2 + 0x10);
        obj_5 = obj_2;
        x1_1 = 2;
    label_413a7c:
        x8_13(obj_5, x1_1, 3);
        x8_24 = *(obj_2 + 0x10);
        obj_7 = obj_2;
        x1_3 = 0;
        x2_5 = 4;
    label_413a90:
        x8_24(obj_7, x1_3, x2_5);
        x8_85 = *(obj_2 + 0x10);
        obj_17 = obj_2;
        x1_13 = 1;
    label_413aa0:
        x8_85(obj_17, x1_13, 4);
        (*(obj_2 + 0x10))(obj_2, x21_1, 4);
    }
    else
        switch (x8)
        {
            case 1:
            case 2:
            case 3:
            case 4:
            case 5:
            case 6:
            case 7:
            case 8:
            case 9:
            case 0xa:
            case 0xb:
            case 0xc:
            case 0xd:
            case 0xe:
            case 0xf:
            case 0x10:
            case 0x11:
            case 0x12:
            case 0x13:
            case 0x14:
            case 0x15:
            case 0x16:
            case 0x17:
            case 0x18:
            case 0x19:
            case 0x1a:
            case 0x1b:
            case 0x1c:
            case 0x1d:
            case 0x1e:
            case 0x1f:
            case 0x20:
            {
                goto label_412fd8;
            }
            case 0x21:
            {
                (*(obj_2 + 0x10))(obj_2, 0, 0);
                x8_15 = *(obj_2 + 0x10);
                obj_6 = obj_2;
                x1_2 = 1;
            label_413300:
                x8_15(obj_6, x1_2, 0);
                x21_1 = 2;
                (*(obj_2 + 0x10))(obj_2, 2, 0);
                (*(obj_2 + 0x10))(obj_2, 0, 1);
                (*(obj_2 + 0x10))(obj_2, 2, 1);
                (*(obj_2 + 0x10))(obj_2, 0, 2);
                x8_28 = *(obj_2 + 0x10);
                obj_8 = obj_2;
                x1_4 = 1;
                goto label_413368;
            }
            case 0x22:
            {
                (*(obj_2 + 0x10))(obj_2, 0, 0);
                x21_1 = 1;
                (*(obj_2 + 0x10))(obj_2, 1, 0);
                (*(obj_2 + 0x10))(obj_2, 0, 1);
                x8_19 = *(obj_2 + 0x10);
            label_41366c:
                x8_19(obj_2, 2, 1);
                (*(obj_2 + 0x10))(obj_2, 0, 2);
                x8_48 = *(obj_2 + 0x10);
                obj_11 = obj_2;
                x1_7 = 1;
            label_413694:
                x8_48(obj_11, x1_7, 2);
                x8_83 = *(obj_2 + 0x10);
                obj_15 = obj_2;
                x1_11 = 0;
                x2_3 = 3;
                goto label_4136a8;
            }
            case 0x23:
            {
                (*(obj_2 + 0x10))(obj_2, 1, 0);
                x21_1 = 2;
                (*(obj_2 + 0x10))(obj_2, 2, 0);
                (*(obj_2 + 0x10))(obj_2, 0, 1);
                (*(obj_2 + 0x10))(obj_2, 0, 2);
                x8_24 = *(obj_2 + 0x10);
                obj_7 = obj_2;
                x1_3 = 0;
            label_413614:
                x2_5 = 3;
                goto label_413a90;
            }
            case 0x24:
            {
                (*(obj_2 + 0x10))(obj_2, 0, 0);
                x21_1 = 1;
                (*(obj_2 + 0x10))(obj_2, 1, 0);
                x8_4 = *(obj_2 + 0x10);
                obj_4 = obj_2;
                x1 = 0;
                goto label_413188;
            }
            case 0x25:
            {
                (*(obj_2 + 0x10))(obj_2, 0, 0);
                (*(obj_2 + 0x10))(obj_2, 1, 0);
                x21_1 = 2;
                (*(obj_2 + 0x10))(obj_2, 2, 0);
                (*(obj_2 + 0x10))(obj_2, 0, 1);
                x8_33 = *(obj_2 + 0x10);
                obj_9 = obj_2;
                x1_5 = 0;
                x2 = 2;
            label_413a54:
                x8_33(obj_9, x1_5, x2);
                x8_64 = *(obj_2 + 0x10);
                obj_14 = obj_2;
                x1_10 = 1;
                goto label_413a68;
            }
            case 0x26:
            {
                (*(obj_2 + 0x10))(obj_2, 0, 0);
                (*(obj_2 + 0x10))(obj_2, 1, 0);
                (*(obj_2 + 0x10))(obj_2, 2, 0);
                x8_37 = *(obj_2 + 0x10);
                obj_10 = obj_2;
                x1_6 = 0;
            label_413544:
                x8_37(obj_10, x1_6, 1);
                (*(obj_2 + 0x10))(obj_2, 0, 2);
                (*(obj_2 + 0x10))(obj_2, 1, 2);
                (*(obj_2 + 0x10))(obj_2, 0, 3);
                (*(obj_2 + 0x10))(obj_2, 0, 4);
                break;
            }
            case 0x27:
            {
                (*(obj_2 + 0x10))(obj_2, 1, 0);
                x21_1 = 2;
                (*(obj_2 + 0x10))(obj_2, 2, 0);
                (*(obj_2 + 0x10))(obj_2, 0, 1);
                (*(obj_2 + 0x10))(obj_2, 0, 2);
                (*(obj_2 + 0x10))(obj_2, 2, 2);
                (*(obj_2 + 0x10))(obj_2, 0, 3);
                x8_24 = *(obj_2 + 0x10);
                obj_7 = obj_2;
                x1_3 = 2;
                goto label_413614;
            }
            case 0x28:
            {
                x8_15 = *(obj_2 + 0x10);
                obj_6 = obj_2;
                x1_2 = 0;
                goto label_413300;
            }
            case 0x29:
            {
                (*(obj_2 + 0x10))(obj_2, 0, 0);
                (*(obj_2 + 0x10))(obj_2, 1, 0);
                x21_1 = 2;
                (*(obj_2 + 0x10))(obj_2, 2, 0);
                (*(obj_2 + 0x10))(obj_2, 1, 1);
                (*(obj_2 + 0x10))(obj_2, 1, 2);
                x8_13 = *(obj_2 + 0x10);
                obj_5 = obj_2;
                x1_1 = 1;
                goto label_413a7c;
            }
            case 0x2a:
            {
                (*(obj_2 + 0x10))(obj_2, 2, 0);
                x8_55 = *(obj_2 + 0x10);
                x21_1 = 1;
                obj_12 = obj_2;
                x1_8 = 2;
                x2_1 = 1;
            label_4137d0:
                x8_55(obj_12, x1_8, x2_1);
                (*(obj_2 + 0x10))(obj_2, 2, 2);
                (*(obj_2 + 0x10))(obj_2, 0, 3);
                x8_85 = *(obj_2 + 0x10);
                obj_17 = obj_2;
                x1_13 = 2;
            label_4139fc:
                x8_85(obj_17, x1_13, 3);
                (*(obj_2 + 0x10))(obj_2, x21_1, 4);
                break;
            }
            case 0x2b:
            {
                (*(obj_2 + 0x10))(obj_2, 0, 0);
                x21_1 = 2;
                (*(obj_2 + 0x10))(obj_2, 2, 0);
                (*(obj_2 + 0x10))(obj_2, 0, 1);
                (*(obj_2 + 0x10))(obj_2, 1, 1);
                (*(obj_2 + 0x10))(obj_2, 0, 2);
                x8_61 = *(obj_2 + 0x10);
                obj_13 = obj_2;
                x1_9 = 0;
                x2_2 = 3;
            label_413988:
                x8_61(obj_13, x1_9, x2_2);
                x8_84 = *(obj_2 + 0x10);
                obj_16 = obj_2;
                x1_12 = 1;
            label_4136bc:
                x8_84(obj_16, x1_12, 3);
                x8_85 = *(obj_2 + 0x10);
                obj_17 = obj_2;
                x1_13 = 0;
                goto label_413aa0;
            }
            case 0x2c:
            {
                (*(obj_2 + 0x10))(obj_2, 0, 0);
                (*(obj_2 + 0x10))(obj_2, 0, 1);
                x8_64 = *(obj_2 + 0x10);
                x21_1 = 2;
                obj_14 = obj_2;
                x1_10 = 0;
            label_413a68:
                x8_64(obj_14, x1_10, 2);
                x8_13 = *(obj_2 + 0x10);
                obj_5 = obj_2;
                x1_1 = 0;
                goto label_413a7c;
            }
            case 0x2d:
            case 0x2e:
            {
                (*(obj_2 + 0x10))(obj_2, 0, 0);
                x21_1 = 2;
                (*(obj_2 + 0x10))(obj_2, 2, 0);
                (*(obj_2 + 0x10))(obj_2, 0, 1);
                x8_4 = *(obj_2 + 0x10);
                obj_4 = obj_2;
                x1 = 1;
            label_413188:
                x8_4(obj_4, x1, 1);
                (*(obj_2 + 0x10))(obj_2, 2, 1);
                x8_28 = *(obj_2 + 0x10);
                obj_8 = obj_2;
                x1_4 = 0;
            label_413368:
                x8_28(obj_8, x1_4, 2);
                x8_48 = *(obj_2 + 0x10);
                obj_11 = obj_2;
                x1_7 = 2;
                goto label_413694;
            }
            case 0x2f:
            {
                x21_1 = 1;
                (*(obj_2 + 0x10))(obj_2, 1, 0);
                x8_66 = *(obj_2 + 0x10);
            label_4137a8:
                x8_66(obj_2, 0, 1);
                (*(obj_2 + 0x10))(obj_2, 2, 1);
                x8_55 = *(obj_2 + 0x10);
                obj_12 = obj_2;
                x1_8 = 0;
                x2_1 = 2;
                goto label_4137d0;
            }
            case 0x30:
            {
                (*(obj_2 + 0x10))(obj_2, 0, 0);
                (*(obj_2 + 0x10))(obj_2, 1, 0);
                (*(obj_2 + 0x10))(obj_2, 0, 1);
                x8_37 = *(obj_2 + 0x10);
                obj_10 = obj_2;
                x1_6 = 2;
                goto label_413544;
            }
            case 0x31:
            {
                (*(obj_2 + 0x10))(obj_2, 1, 0);
                (*(obj_2 + 0x10))(obj_2, 0, 1);
                x21_1 = 2;
                (*(obj_2 + 0x10))(obj_2, 2, 1);
                (*(obj_2 + 0x10))(obj_2, 0, 2);
                (*(obj_2 + 0x10))(obj_2, 2, 2);
                (*(obj_2 + 0x10))(obj_2, 0, 3);
                x8_24 = *(obj_2 + 0x10);
                obj_7 = obj_2;
                x1_3 = 1;
                goto label_413614;
            }
            case 0x32:
            {
                (*(obj_2 + 0x10))(obj_2, 0, 0);
                (*(obj_2 + 0x10))(obj_2, 1, 0);
                (*(obj_2 + 0x10))(obj_2, 0, 1);
                x8_19 = *(obj_2 + 0x10);
                x21_1 = 2;
                goto label_41366c;
            }
            case 0x33:
            {
                x21_1 = 1;
                (*(obj_2 + 0x10))(obj_2, 1, 0);
                (*(obj_2 + 0x10))(obj_2, 2, 0);
                (*(obj_2 + 0x10))(obj_2, 0, 1);
                x8_83 = *(obj_2 + 0x10);
                obj_15 = obj_2;
                x1_11 = 1;
                x2_3 = 2;
            label_4136a8:
                x8_83(obj_15, x1_11, x2_3);
                x8_84 = *(obj_2 + 0x10);
                obj_16 = obj_2;
                x1_12 = 2;
                goto label_4136bc;
            }
            case 0x34:
            {
                (*(obj_2 + 0x10))(obj_2, 0, 0);
                x21_1 = 1;
                (*(obj_2 + 0x10))(obj_2, 1, 0);
                (*(obj_2 + 0x10))(obj_2, 2, 0);
                x8_92 = *(obj_2 + 0x10);
            label_4139d8:
                x8_92(obj_2, 1, 1);
                x8_103 = *(obj_2 + 0x10);
                obj_18 = obj_2;
                x1_14 = 1;
                goto label_4139ec;
            }
            case 0x35:
            {
                (*(obj_2 + 0x10))(obj_2, 0, 0);
                (*(obj_2 + 0x10))(obj_2, 2, 0);
                x8_66 = *(obj_2 + 0x10);
                x21_1 = 1;
                goto label_4137a8;
            }
            case 0x36:
            {
                (*(obj_2 + 0x10))(obj_2, 0, 0);
                (*(obj_2 + 0x10))(obj_2, 2, 0);
                x21_1 = 1;
                (*(obj_2 + 0x10))(obj_2, 0, 1);
                (*(obj_2 + 0x10))(obj_2, 2, 1);
                (*(obj_2 + 0x10))(obj_2, 0, 2);
                x8_103 = *(obj_2 + 0x10);
                obj_18 = obj_2;
                x1_14 = 2;
            label_4139ec:
                x8_103(obj_18, x1_14, 2);
                x8_85 = *(obj_2 + 0x10);
                obj_17 = obj_2;
                x1_13 = 1;
                goto label_4139fc;
            }
            case 0x37:
            {
                (*(obj_2 + 0x10))(obj_2, 0, 0);
                x21_1 = 2;
                (*(obj_2 + 0x10))(obj_2, 2, 0);
                (*(obj_2 + 0x10))(obj_2, 0, 1);
                (*(obj_2 + 0x10))(obj_2, 2, 1);
                (*(obj_2 + 0x10))(obj_2, 0, 2);
                (*(obj_2 + 0x10))(obj_2, 1, 2);
                (*(obj_2 + 0x10))(obj_2, 2, 2);
                (*(obj_2 + 0x10))(obj_2, 0, 3);
                x8_83 = *(obj_2 + 0x10);
                obj_15 = obj_2;
                x1_11 = 1;
                x2_3 = 3;
                goto label_4136a8;
            }
            case 0x38:
            {
                (*(obj_2 + 0x10))(obj_2, 0, 0);
                x21_1 = 2;
                (*(obj_2 + 0x10))(obj_2, 2, 0);
                (*(obj_2 + 0x10))(obj_2, 1, 1);
                x8_61 = *(obj_2 + 0x10);
                obj_13 = obj_2;
                x1_9 = 1;
                x2_2 = 2;
                goto label_413988;
            }
            case 0x39:
            {
                (*(obj_2 + 0x10))(obj_2, 0, 0);
                (*(obj_2 + 0x10))(obj_2, 2, 0);
                x8_92 = *(obj_2 + 0x10);
                x21_1 = 1;
                goto label_4139d8;
            }
            case 0x3a:
            {
                (*(obj_2 + 0x10))(obj_2, 0, 0);
                (*(obj_2 + 0x10))(obj_2, 1, 0);
                x21_1 = 2;
                (*(obj_2 + 0x10))(obj_2, 2, 0);
                x8_33 = *(obj_2 + 0x10);
                obj_9 = obj_2;
                x1_5 = 2;
                x2 = 1;
                goto label_413a54;
            }
        }
    id obj_3 = _objc_retainAutoreleaseReturnValue(obj_1);
    _objc_release(obj_2);
    _objc_release(obj_1);
    _objc_release(obj_3);
    return obj_3;
}

int64_t sub_413af8(void* arg1, int32_t arg2, int64_t arg3)
{
    id x19 = *(arg1 + 0x20);
    int128_t v0;
    v0 = arg2;
    int128_t v1;
    v1 = arg3;
    id x0_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSValue, 
        "valueWithCGPoint:", arg3));
    _objc_msgSend(x19, "addObject:", x0_2);
    /* tailcall */
    return _objc_release(x0_2);
}

void -[ACPanelController moreAdminTapped:](struct ACPanelController* self, SEL sel, id moreAdminTapped)
{
    int64_t v15;
    int64_t var_a0 = v15;
    int64_t v14;
    int64_t var_98 = v14;
    double v13;
    double var_90 = v13;
    int64_t v12;
    int64_t var_88 = v12;
    double v11;
    double var_80 = v11;
    int64_t v10;
    int64_t var_78 = v10;
    int64_t x8 = *___stack_chk_guard;
    id x0_1 = _objc_msgSend(moreAdminTapped, "tag");
    int32_t v0;
    int32_t v1;
    float v2;
    double v8;
    v0 = sub_4113d8();
    
    if (&x0_1[-0x271] > 5)
    {
    label_414068:
        
        if (*___stack_chk_guard == x8)
            return;
    }
    else
    {
        v8 = v0;
        v10 = v1;
        
        switch (x0_1)
        {
            case 0x1388:
            {
                sub_410c94(&cfstr_Admin:_500_Gold_Bars_incoming!);
                float v0_1 = v10 + 1f;
                v11 = 0.0;
                int32_t i_5 = 0x1f4;
                v13 = -10f;
                int32_t i;
                
                do
                {
                    v10 = 0x42c80000;
                    v12 = _arc4random_uniform(0x7d0) / v10 + v13;
                    uint32_t x0_3;
                    double v0_3;
                    x0_3 = _arc4random_uniform(0x7d0);
                    v0_3 = x0_3;
                    v0_3 = v0_3 / v10;
                    v0_3 = v0_3 + v13;
                    v10 = v8 + v12;
                    v12 = v2 + v0_3;
                    dispatch_time_t when =
                        _dispatch_time(0, vcvtd_s64_f64(v11 * 0.01 * 1000000000.0));
                    _objc_retainAutorelease(__dispatch_main_q);
                    void* (* const var_118)[0x20] = __NSConcreteStackBlock;
                    int64_t var_110_1 = 0xc0000000;
                    int64_t (* var_108_1)(void* arg1) = sub_414118;
                    void* const var_100_1 = &data_43c190;
                    int32_t var_f8_1 = v10;
                    float var_f4_1 = v0_1;
                    int32_t var_f0_1 = v12;
                    _dispatch_after(when, __dispatch_main_q, &var_118);
                    v11 = v11 + 1.0;
                    i = i_5;
                    i_5 -= 1;
                } while (i != 1);
                goto label_414068;
            }
            case 0x1389:
            {
                sub_410c94(&cfstr_Admin:_Jetpack_Rain!);
                v8 = 0.0;
                int32_t i_6 = 0x1e;
                float v9_1 = -10f;
                int32_t i_1;
                
                do
                {
                    v14 = 0x42c80000;
                    v15 = _arc4random_uniform(0x7d0) / v14 + v9_1;
                    uint32_t x0_7;
                    double v0_7;
                    x0_7 = _arc4random_uniform(0x7d0);
                    v0_7 = x0_7;
                    v0_7 = v0_7 / v14;
                    v14 = v0_7 + v9_1;
                    dispatch_time_t when_1 =
                        _dispatch_time(0, vcvtd_s64_f64(v8 * 0.10000000000000001 * 1000000000.0));
                    _objc_retainAutorelease(__dispatch_main_q);
                    void* (* const var_148)[0x20] = __NSConcreteStackBlock;
                    int64_t var_140_1 = 0xc0000000;
                    int64_t (* var_138_1)(void* arg1) = sub_41412c;
                    void* const var_130_1 = &data_43c190;
                    int32_t var_128_1 = v15;
                    int32_t var_124_1 = 0x41c80000;
                    int32_t var_120_1 = v14;
                    _dispatch_after(when_1, __dispatch_main_q, &var_148);
                    v8 = v8 + 1.0;
                    i_1 = i_6;
                    i_6 -= 1;
                } while (i_1 != 1);
                goto label_414068;
            }
            case 0x138a:
            {
                sub_410c94(&cfstr_Admin:_RPG_Arsenal!);
                int32_t i_2 = 0;
                v10 = v10 + 1f;
                v11 = -3f;
                
                do
                {
                    v12 = 0x42c80000;
                    v13 = _arc4random_uniform(0x258) / v12 + v11;
                    uint32_t x0_11;
                    int128_t v2_1;
                    x0_11 = _arc4random_uniform(0x258);
                    v2_1 = v2 + x0_11 / v12 + v11;
                    id x0_12;
                    
                    x0_12 = (i_2 & 0xff) * 0xaaaaaaab < 0x55555556 ? &cfstr_item_rpg
                        : &cfstr_item_rpg_ammo;
                    
                    sub_4114c8(x0_12, v8 + v13);
                    i_2 += 1;
                } while (i_2 != 0x14);
                
                goto label_414068;
            }
            case 0x138b:
            {
                sub_410c94(&cfstr_Admin:_Diamond_Floor!);
                int32_t x22_1 = 0;
                double v0_11;
                v0_11 = 0x3dcccccd;
                v10 = v10 + 0.100000001f;
                int32_t i_3 = -5;
                v11 = 0.5f;
                int32_t var_17c_1 = v8;
                
                do
                {
                    v0_11 = i_3;
                    v15 = vfma_f32(v8, v0_11, v11);
                    
                    for (int32_t j = -5; j != 6; j += 1)
                    {
                        v0_11 = j;
                        v8 = vfma_f32(v2, v0_11, v11);
                        dispatch_time_t when_2 =
                            _dispatch_time(0, vcvtd_s64_f64((x22_1 + j + 5) * 0.02 * 1000000000.0));
                        _objc_retainAutorelease(__dispatch_main_q);
                        void* (* const var_178)[0x20] = __NSConcreteStackBlock;
                        int64_t var_170_1 = 0xc0000000;
                        int64_t (* var_168_1)(void* arg1) = sub_414140;
                        void* const var_160_1 = &data_43c190;
                        int32_t var_158_1 = v15;
                        int32_t var_154_1 = v10;
                        int32_t var_150_1 = v8;
                        _dispatch_after(when_2, __dispatch_main_q, &var_178);
                    }
                    
                    i_3 += 1;
                    x22_1 += 0xb;
                    v8 = var_17c_1;
                } while (i_3 != 6);
                
                goto label_414068;
            }
            case 0x138c:
            {
                sub_410c94(&cfstr_Admin:_Weapon_Wall!);
                struct __NSConstantString* const var_e8 = &cfstr_item_shotgun;
                struct __NSConstantString* const var_e0_1 = &cfstr_item_rpg;
                struct __NSConstantString* const var_d8_1 = &cfstr_item_crossbow;
                struct __NSConstantString* const var_d0_1 = &cfstr_item_revolver;
                struct __NSConstantString* const var_c8_1 = &cfstr_item_flamethrower;
                struct __NSConstantString* const var_c0_1 = &cfstr_item_demon_sword;
                struct __NSConstantString* const var_b8_1 = &cfstr_item_alphablade;
                struct __NSConstantString* const var_b0_1 = &cfstr_item_great_sword;
                id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
                    "arrayWithObjects:count:", &var_e8, 8));
                int64_t i_4 = 0;
                v13 = -4f;
                v15 = 0.5f;
                
                do
                {
                    int32_t j_1 = 0;
                    v11 = v8 + i_4 + v13;
                    
                    do
                    {
                        v12 = vfma_f32(v10, j_1, 0.800000012f) + v15;
                        id obj_1;
                        int128_t v1_2;
                        int128_t v2_2;
                        obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj, 
                            "objectAtIndexedSubscript:", i_4));
                        v1_2 = v12;
                        v2_2 = v2 + 3f;
                        sub_4114c8(obj_1, v11);
                        _objc_release(obj_1);
                        j_1 += 1;
                    } while (j_1 != 4);
                    
                    i_4 += 1;
                } while (i_4 != 8);
                
                _objc_release(obj);
                goto label_414068;
            }
            case 0x138d:
            {
                data_446774 = 0xffffffff;
                data_446778 = 0xffffffff;
                data_44677c = 0xffffffff;
                data_446780 = 0xffffffff;
                
                if (*___stack_chk_guard == x8)
                    /* tailcall */
                    return sub_410c94(
                        &cfstr_Admin:_Spawn/color/scale_approach_reset_?_will_re-probe_next_spawn);
                break;
            }
        }
    }
    
    ___stack_chk_fail();
    /* no return */
}

int64_t sub_414118(void* arg1)
{
    int128_t v1;
    v1 = *(arg1 + 0x24);
    int128_t v2;
    v2 = *(arg1 + 0x28);
    /* tailcall */
    return sub_4114c8(&cfstr_item_goldbar, *(arg1 + 0x20));
}

int64_t sub_41412c(void* arg1)
{
    int128_t v1;
    v1 = *(arg1 + 0x24);
    int128_t v2;
    v2 = *(arg1 + 0x28);
    /* tailcall */
    return sub_4114c8(&cfstr_item_jetpack, *(arg1 + 0x20));
}

int64_t sub_414140(void* arg1)
{
    int128_t v1;
    v1 = *(arg1 + 0x24);
    int128_t v2;
    v2 = *(arg1 + 0x28);
    /* tailcall */
    return sub_4114c8(&cfstr_item_ruby, *(arg1 + 0x20));
}

void -[ACPanelController rebuildConnectedUserRows](struct ACPanelController* self, SEL sel)
{
    int64_t v15;
    int64_t var_a0 = v15;
    int64_t v14;
    int64_t var_98 = v14;
    int64_t v13;
    int64_t var_90 = v13;
    double v12;
    double var_88 = v12;
    double v11;
    double var_80 = v11;
    int64_t v10;
    int64_t var_78 = v10;
    int64_t x8 = *___stack_chk_guard;
    
    if (!data_4469f8)
    {
        id x0_1 = _objc_msgSend(clsRef_NSMutableSet, "new");
        id obj_22 = data_4469f8;
        data_4469f8 = x0_1;
        _objc_release(obj_22);
    }
    
    int128_t var_150;
    __builtin_memset(&var_150, 0, 0x20);
    int128_t var_170;
    __builtin_memset(&var_170, 0, 0x18);
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "connectedUsersContainer"));
    id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj, "subviews"));
    id obj_2 = _objc_msgSend(obj_1, "copy");
    _objc_release(obj_1);
    _objc_release(obj);
    void var_130;
    id i_2 = _objc_msgSend(obj_2, "countByEnumeratingWithState:objects:count:", &var_170, &var_130, 
        0x10);
    
    if (i_2)
    {
        id i_1 = i_2;
        int64_t* var_160;
        int64_t x23_1 = *var_160;
        id i;
        
        do
        {
            int64_t x25_1 = 0;
            
            do
            {
                if (*var_160 != x23_1)
                    _objc_enumerationMutation(obj_2);
                
                _objc_msgSend(*(*(&var_170 + 8) + (x25_1 << 3)), "removeFromSuperview");
                x25_1 += 1;
            } while (i_1 != x25_1);
            
            i = _objc_msgSend(obj_2, "countByEnumeratingWithState:objects:count:", &var_170, 
                &var_130, 0x10);
            i_1 = i;
        } while (i);
    }
    
    _objc_release(obj_2);
    sub_412450();
    id obj_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "connectedUsersContainer"));
    double v9 = _objc_msgSend(obj_3, "frame");
    _objc_release(obj_3);
    double v8;
    
    if (_objc_msgSend(data_4469e0, "count") < 1)
    {
        v8 = 6.0;
    label_4147c0:
        id x0_67;
        int64_t x2_17;
        int128_t v1_6;
        int128_t v2_5;
        int128_t v3_5;
        x0_67 = _objc_alloc(clsRef_UILabel);
        v2_5 = v9 + -16.0;
        v3_5 = 24.0;
        v1_6 = v8;
        id obj_16 = _objc_msgSend(x0_67, "initWithFrame:", x2_17);
        int64_t x2_18;
        int128_t v0_12;
        x2_18 = _objc_msgSend(obj_16, "setText:", &cfstr_No_players_found_(or_all_kicked));
        v0_12 = 10.0;
        id obj_17 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
            "systemFontOfSize:", x2_18));
        _objc_msgSend(obj_16, "setFont:", obj_17);
        int64_t x2_20;
        int64_t x3_5;
        int64_t x4_2;
        int64_t x5_1;
        int128_t v0_13;
        int128_t v1_7;
        int128_t v2_6;
        int128_t v3_6;
        x2_20 = _objc_release(obj_17);
        v0_13 = 0x3fdccccccccccccd;
        v1_7 = 0x3fe199999999999a;
        v2_6 = 0x3fe6666666666666;
        v3_6 = 1.0;
        int64_t obj_18 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
            "colorWithRed:green:blue:alpha:", x2_20, x3_5, x4_2, x5_1));
        _objc_msgSend(obj_16, "setTextColor:", obj_18);
        _objc_release(obj_18);
        id obj_19 =
            _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "connectedUsersContainer"));
        _objc_msgSend(obj_19, "addSubview:", obj_16);
        _objc_release(obj_19);
        v8 = v8 + 28.0;
        _objc_release(obj_16);
    }
    else
    {
        int64_t x25_2 = 0;
        int64_t x23_2 = 0;
        v11 = *_UIFontWeightMedium;
        v8 = 6.0;
        int64_t x0_65;
        
        do
        {
            id obj_4 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(data_4469e0, 
                "objectAtIndexedSubscript:"));
            
            if (!(_objc_msgSend(data_4469f8, "containsObject:") & 1))
            {
                id x0_23;
                int128_t v0_2;
                int128_t v1_1;
                int128_t v2_1;
                int128_t v3_1;
                x0_23 = _objc_alloc(clsRef_UILabel);
                v0_2 = 8.0;
                v3_1 = 28.0;
                v1_1 = v8;
                v2_1 = v9 + -90.0;
                id obj_5 = _objc_msgSend(x0_23, "initWithFrame:");
                int128_t v0_3;
                int128_t v1_2;
                v0_3 = _objc_msgSend(obj_5, "setText:");
                v0_3 = 12.0;
                v1_2 = v11;
                id obj_6 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
                    "systemFontOfSize:weight:"));
                _objc_msgSend(obj_5, "setFont:");
                int128_t v0_4;
                int128_t v1_3;
                int128_t v2_2;
                int128_t v3_2;
                v0_4 = _objc_release(obj_6);
                v2_2 = 1.0;
                v3_2 = 1.0;
                v0_4 = 0x3feb333333333333;
                v1_3 = 0x3feccccccccccccd;
                id obj_7 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
                    "colorWithRed:green:blue:alpha:"));
                _objc_msgSend(obj_5, "setTextColor:");
                _objc_release(obj_7);
                _objc_msgSend(obj_5, "setTag:");
                id obj_8 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, 
                    "connectedUsersContainer"));
                _objc_msgSend(obj_8, "addSubview:");
                _objc_release(obj_8);
                id obj_9;
                int128_t v0_5;
                int128_t v1_4;
                int128_t v2_3;
                int128_t v3_3;
                obj_9 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, 
                    "buttonWithType:"));
                v3_3 = 28.0;
                v0_5 = v9 + -78.0;
                v1_4 = v8;
                v2_3 = 0x4051800000000000;
                int128_t v0_6;
                int128_t v1_5;
                int128_t v2_4;
                int128_t v3_4;
                v0_6 = _objc_msgSend(obj_9, "setFrame:");
                v3_4 = 1.0;
                v0_6 = 0x3fe999999999999a;
                v1_5 = 0x3fc3333333333333;
                v2_4 = 0x3fc3333333333333;
                id obj_10 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
                    "colorWithRed:green:blue:alpha:"));
                _objc_msgSend(obj_9, "setBackgroundColor:");
                _objc_release(obj_10);
                id obj_11;
                int128_t v0_7;
                obj_11 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_9, "layer"));
                v0_7 = 6.0;
                _objc_msgSend(obj_11, "setCornerRadius:");
                _objc_release(obj_11);
                _objc_msgSend(obj_9, "setTitle:forState:");
                id obj_12 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
                    "whiteColor"));
                _objc_msgSend(obj_9, "setTitleColor:forState:");
                _objc_release(obj_12);
                int128_t v0_8;
                v0_8 = 10.0;
                id obj_13 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
                    "boldSystemFontOfSize:"));
                id obj_14 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_9, "titleLabel"));
                _objc_msgSend(obj_14, "setFont:");
                _objc_release(obj_14);
                _objc_release(obj_13);
                _objc_msgSend(obj_9, "setTag:");
                _objc_msgSend(obj_9, "addTarget:action:forControlEvents:");
                id obj_15 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, 
                    "connectedUsersContainer"));
                _objc_msgSend(obj_15, "addSubview:");
                _objc_release(obj_15);
                v8 = v8 + 0x4041000000000000;
                x25_2 += 1;
                _objc_release(obj_9);
                _objc_release(obj_5);
            }
            
            _objc_release(obj_4);
            x23_2 += 1;
            x0_65 = _objc_msgSend(data_4469e0, "count");
        } while (x23_2 < x0_65);
        
        if (!x25_2)
            goto label_4147c0;
    }
    
    id obj_20 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "connectedUsersContainer"));
    double v0_15;
    int64_t v1_8;
    double v2_7;
    v0_15 = _objc_msgSend(obj_20, "frame");
    _objc_release(obj_20);
    id obj_21;
    int64_t x2_23;
    int128_t v0_16;
    int128_t v1_9;
    int128_t v2_8;
    int128_t v3_7;
    obj_21 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "connectedUsersContainer"));
    v0_16 = v0_15;
    v1_9 = v1_8;
    v2_8 = v2_7;
    v3_7 = v8 + 6.0;
    _objc_msgSend(obj_21, "setFrame:", x2_23);
    _objc_release(obj_21);
    
    if (*___stack_chk_guard == x8)
        return;
    
    ___stack_chk_fail();
    /* no return */
}

void -[ACPanelController refreshConnectedUsers](struct ACPanelController* self, SEL sel)
{
    int64_t x8 = *___stack_chk_guard;
    sub_410c94(&cfstr_Refreshing_connected_users...);
    _objc_msgSend(self, "rebuildConnectedUserRows");
    int128_t var_110;
    __builtin_memset(&var_110, 0, 0x20);
    int128_t var_130;
    __builtin_memset(&var_130, 0, 0x18);
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminInner"));
    id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj, "subviews"));
    id obj_2 = _objc_msgSend(obj_1, "copy");
    _objc_release(obj_1);
    _objc_release(obj);
    void var_e8;
    id i_2 =
        _objc_msgSend(obj_2, "countByEnumeratingWithState:objects:count:", &var_130, &var_e8, 0x10);
    
    if (i_2)
    {
        id i_1 = i_2;
        int64_t* var_120;
        int64_t x24_1 = *var_120;
        id i;
        
        do
        {
            int64_t x26_1 = 0;
            
            do
            {
                if (*var_120 != x24_1)
                    _objc_enumerationMutation(obj_2);
                
                _objc_msgSend(*(*(&var_130 + 8) + (x26_1 << 3)), "removeFromSuperview");
                x26_1 += 1;
            } while (i_1 != x26_1);
            
            i = _objc_msgSend(obj_2, "countByEnumeratingWithState:objects:count:", &var_130, 
                &var_e8, 0x10);
            i_1 = i;
        } while (i);
    }
    
    _objc_release(obj_2);
    _objc_msgSend(self, "buildAdminContent");
    struct objc_class_t* clsRef_NSString_1 = clsRef_NSString;
    id var_140 = _objc_msgSend(data_4469e0, "count");
    id obj_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString_1, 
        "stringWithFormat:", &cfstr_Found_%lu_players));
    sub_410c94(obj_3);
    _objc_release(obj_3);
    
    if (*___stack_chk_guard == x8)
        return;
    
    ___stack_chk_fail();
    /* no return */
}

void -[ACPanelController kickPlayerTapped:](struct ACPanelController* self, SEL sel, id kickPlayerTapped)
{
    int64_t x8 = *___stack_chk_guard;
    id obj = _objc_retain(kickPlayerTapped);
    
    if (!data_4469f8)
    {
        id x0_2 = _objc_msgSend(clsRef_NSMutableSet, "new");
        id obj_9 = data_4469f8;
        data_4469f8 = x0_2;
        _objc_release(obj_9);
    }
    
    id x0_5 = _objc_msgSend(obj, "tag");
    
    if (x0_5 >= 0x1838 && &x0_5[-0x307] < _objc_msgSend(data_4469e0, "count"))
    {
        id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(data_4469e0, 
            "objectAtIndexedSubscript:", &x0_5[-0x307]));
        _objc_msgSend(data_4469f8, "addObject:", obj_1);
        id obj_10 = obj_1;
        id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
            "stringWithFormat:", &cfstr_KICKED:_%@));
        sub_410c94(obj_2);
        _objc_release(obj_2);
        id obj_11 = obj_1;
        id obj_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
            "stringWithFormat:", 
            &cfstr_Player_'%@'_kicked.\nThey_will_see:_'An_admin_has_closed_your_menu._Please_contact_PolarGT'));
        id obj_4 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIAlertController, 
            "alertControllerWithTitle:message:preferredStyle:", &cfstr_Player_Kicked, obj_3, 1));
        id obj_5 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIAlertAction, 
            "actionWithTitle:style:handler:", &cfstr_OK, 0, 0));
        _objc_msgSend(obj_4, "addAction:", obj_5);
        _objc_release(obj_5);
        _objc_msgSend(self, "presentViewController:animated:completion:", obj_4, 1, 0);
        _objc_msgSend(self, "rebuildConnectedUserRows");
        int128_t var_110;
        __builtin_memset(&var_110, 0, 0x20);
        int128_t var_130;
        __builtin_memset(&var_130, 0, 0x18);
        id obj_6 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminInner"));
        id obj_7 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_6, "subviews"));
        id obj_8 = _objc_msgSend(obj_7, "copy");
        _objc_release(obj_7);
        _objc_release(obj_6);
        void var_f0;
        id i_2 = _objc_msgSend(obj_8, "countByEnumeratingWithState:objects:count:", &var_130, 
            &var_f0, 0x10);
        
        if (i_2)
        {
            id i_1 = i_2;
            int64_t* var_120;
            int64_t x28_1 = *var_120;
            id i;
            
            do
            {
                int64_t x21_2 = 0;
                
                do
                {
                    if (*var_120 != x28_1)
                        _objc_enumerationMutation(obj_8);
                    
                    _objc_msgSend(*(*(&var_130 + 8) + (x21_2 << 3)), "removeFromSuperview");
                    x21_2 += 1;
                } while (i_1 != x21_2);
                
                i = _objc_msgSend(obj_8, "countByEnumeratingWithState:objects:count:", &var_130, 
                    &var_f0, 0x10);
                i_1 = i;
            } while (i);
        }
        
        _objc_release(obj_8);
        _objc_msgSend(self, "buildAdminContent");
        _objc_release(obj_4);
        _objc_release(obj_3);
        _objc_release(obj_1);
    }
    
    _objc_release(obj);
    
    if (*___stack_chk_guard == x8)
        return;
    
    ___stack_chk_fail();
    /* no return */
}

void -[ACPanelController voiceBtnDown](struct ACPanelController* self, SEL sel)
{
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminInner"));
    id x0_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj, "viewWithTag:", 0x37f));
    _objc_release(obj);
    int64_t x2;
    int64_t x3;
    int64_t x4;
    int64_t x5;
    int128_t v1;
    int128_t v2;
    int128_t v3;
    x2 = _objc_msgSend(x0_2, "setTitle:forState:", &cfstr_??_LISTENING..._speak_now, 0);
    v1 = 0x3fe6666666666666;
    v3 = 1.0;
    v2 = 0x3fc999999999999a;
    id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:", x2, x3, x4, x5));
    _objc_msgSend(x0_2, "setBackgroundColor:", obj_1);
    _objc_release(obj_1);
    _objc_msgSend(self, "startVoiceRecognition");
    /* tailcall */
    return _objc_release(x0_2);
}

void -[ACPanelController voiceBtnUp](struct ACPanelController* self, SEL sel)
{
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminInner"));
    id x0_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj, "viewWithTag:", 0x37f));
    _objc_release(obj);
    int64_t x2;
    int64_t x3;
    int64_t x4;
    int64_t x5;
    int128_t v0;
    int128_t v2;
    int128_t v3;
    x2 = _objc_msgSend(x0_2, "setTitle:forState:", 
        &cfstr_??_Hold_to_Talk_?_"Hey_AI_spawn_[item]_[qty]", 0);
    v0 = 0x3fe999999999999a;
    v3 = 1.0;
    v2 = 0x3fc999999999999a;
    id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:", x2, x3, x4, x5));
    _objc_msgSend(x0_2, "setBackgroundColor:", obj_1);
    _objc_release(obj_1);
    _objc_msgSend(self, "stopVoiceRecognition");
    /* tailcall */
    return _objc_release(x0_2);
}

void -[ACPanelController startVoiceRecognition](struct ACPanelController* self, SEL sel)
{
    if (!data_446a20)
    {
        id x0_1 = _objc_alloc(clsRef_SFSpeechRecognizer);
        id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSLocale, 
            "localeWithLocaleIdentifier:", &cfstr_en-US));
        id x0_5 = _objc_msgSend(x0_1, "initWithLocale:", obj);
        id obj_1 = data_446a20;
        data_446a20 = x0_5;
        _objc_release(obj_1);
        _objc_release(obj);
    }
    
    if (!data_446a38)
    {
        id x0_9 = _objc_alloc_init(clsRef_AVAudioEngine);
        id obj_2 = data_446a38;
        data_446a38 = x0_9;
        _objc_release(obj_2);
    }
    
    struct objc_class_t* clsRef_SFSpeechRecognizer_1 = clsRef_SFSpeechRecognizer;
    void* (* const var_68)[0x20] = __NSConcreteStackBlock;
    int64_t var_60 = 0xc2000000;
    int64_t (* var_58)(void* arg1, int64_t arg2) = sub_4151a4;
    void* const var_50 = &data_43c220;
    struct ACPanelController* self_1 = self;
    _objc_msgSend(clsRef_SFSpeechRecognizer_1, "requestAuthorization:", &var_68);
}

int64_t sub_4151a4(void* arg1, int64_t arg2)
{
    _objc_retainAutorelease(__dispatch_main_q);
    
    if (arg2 != 3)
        /* tailcall */
        return _dispatch_async(__dispatch_main_q, &data_43c200);
    
    void* (* const var_48)[0x20] = __NSConcreteStackBlock;
    int64_t var_40 = 0xc2000000;
    int64_t (* var_38)(void* arg1) = sub_415250;
    void* const var_30 = &data_43c090;
    int64_t var_28 = *(arg1 + 0x20);
    return _dispatch_async(__dispatch_main_q, &var_48);
}

int64_t sub_415244()
{
    /* tailcall */
    return sub_410c94(&cfstr_Voice:_Speech_recognition_not_authorized);
}

int64_t sub_415250(void* arg1)
{
    /* tailcall */
    return _objc_msgSend(*(arg1 + 0x20), "beginRecording");
}

void -[ACPanelController beginRecording](struct ACPanelController* self, SEL sel)
{
    id x0 = data_446a30;
    
    if (x0)
    {
        _objc_msgSend(x0, "cancel");
        id obj_2 = data_446a30;
        data_446a30 = 0;
        _objc_release(obj_2);
    }
    
    id obj_3 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_AVAudioSession, "sharedInstance"));
    int64_t x2 = *_AVAudioSessionCategoryRecord;
    int64_t x3 = *_AVAudioSessionModeMeasurement;
    id obj_1 = nullptr;
    _objc_msgSend(obj_3, "setCategory:mode:options:error:", x2, x3, 2, &obj_1);
    id obj_4 = _objc_retain(obj_1);
    id obj = obj_4;
    _objc_msgSend(obj_3, "setActive:withOptions:error:", 1, 1, &obj);
    id obj_5 = _objc_retain(obj);
    _objc_release(obj_4);
    id x0_8 = _objc_alloc_init(clsRef_SFSpeechAudioBufferRecognitionRequest);
    id obj_8 = data_446a28;
    data_446a28 = x0_8;
    _objc_release(obj_8);
    _objc_msgSend(data_446a28, "setShouldReportPartialResults:", 1);
    id obj_6 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(data_446a38, "inputNode"));
    id var_68;
    _objc_initWeak(&var_68, self);
    id x23 = data_446a20;
    int64_t x24 = data_446a28;
    void* (* const var_90)[0x20] = __NSConcreteStackBlock;
    int64_t var_88 = 0xc2000000;
    int64_t (* var_80)(void* arg1, id arg2, id arg3) = sub_4154f0;
    void* const var_78 = &data_43c2b0;
    id var_70;
    _objc_copyWeak(&var_70, &var_68);
    id x0_17 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(x23, 
        "recognitionTaskWithRequest:resultHandler:", x24, &var_90));
    id obj_9 = data_446a30;
    data_446a30 = x0_17;
    _objc_release(obj_9);
    id obj_7 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_6, "outputFormatForBus:", 0));
    _objc_msgSend(obj_6, "installTapOnBus:bufferSize:format:block:", 0, 0x400, obj_7, &data_43c300);
    _objc_msgSend(data_446a38, "prepare");
    _objc_msgSend(data_446a38, "startAndReturnError:", 0);
    sub_410c94(&cfstr_Voice:_Listening...);
    _objc_release(obj_7);
    _objc_destroyWeak(&var_70);
    _objc_destroyWeak(&var_68);
    _objc_release(obj_6);
    _objc_release(obj_5);
    _objc_release(obj_3);
}

int64_t sub_4154d0(struct _Unwind_Exception* arg1, id* arg2 @ x22)
{
    _objc_destroyWeak(arg2);
    void location;
    _objc_destroyWeak(&location);
    void* x0_3;
    id x1;
    id x2;
    x0_3 = __Unwind_Resume(arg1);
    /* tailcall */
    return sub_4154f0(x0_3, x1, x2);
}

int64_t sub_4154f0(void* arg1, id arg2, id arg3)
{
    int64_t v8;
    int64_t var_68 = v8;
    id obj = _objc_retain(arg2);
    id obj_1 = _objc_retain(arg3);
    
    if (obj)
    {
        id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj, "bestTranscription"));
        id obj_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_2, "formattedString"));
        _objc_release(obj_2);
        _objc_retainAutorelease(__dispatch_main_q);
        void* (* const var_a8)[0x20] = __NSConcreteStackBlock;
        int64_t var_a0_1 = 0xc2000000;
        int64_t (* var_98_1)(void* arg1) = sub_415714;
        void* const var_90_1 = &data_43c250;
        id var_80[0x2];
        _objc_copyWeak(&var_80, arg1 + 0x20);
        id obj_4 = _objc_retain(obj_3);
        _dispatch_async(__dispatch_main_q, &var_a8);
        
        if (_objc_msgSend(obj, "isFinal"))
        {
            void* (* const var_d8)[0x20] = __NSConcreteStackBlock;
            int64_t var_d0_1 = 0xc2000000;
            int64_t (* var_c8_1)(void* arg1) = sub_4157f8;
            void* const var_c0_1 = &data_43c250;
            id var_b0;
            _objc_copyWeak(&var_b0, arg1 + 0x20);
            id obj_5 = _objc_retain(obj_4);
            _dispatch_async(__dispatch_main_q, &var_d8);
            _objc_release(__dispatch_main_q);
            _objc_release(obj_5);
            _objc_destroyWeak(&var_b0);
        }
        
        _objc_release(obj_4);
        _objc_destroyWeak(&var_80);
        _objc_release(obj_4);
    }
    
    if (obj_1)
    {
        _objc_retainAutorelease(__dispatch_main_q);
        void* (* const var_100)[0x20] = __NSConcreteStackBlock;
        int64_t var_f8_1 = 0xc2000000;
        int64_t (* var_f0_1)(void* arg1) = sub_415834;
        void* const var_e8_1 = &data_43c280;
        id var_e0;
        _objc_copyWeak(&var_e0, arg1 + 0x20);
        _dispatch_async(__dispatch_main_q, &var_100);
        _objc_destroyWeak(&var_e0);
    }
    
    _objc_release(obj_1);
    return _objc_release(obj);
}

int64_t sub_415714(void* arg1)
{
    id obj = _objc_loadWeakRetained(arg1 + 0x28);
    id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj, "adminInner"));
    id x0_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_1, "viewWithTag:", 0x37c));
    _objc_release(obj_1);
    _objc_release(obj);
    _objc_msgSend(x0_3, "setText:", *(arg1 + 0x20));
    /* tailcall */
    return _objc_release(x0_3);
}

int64_t sub_4157a0(void* arg1, void* arg2)
{
    _objc_retain(*(arg2 + 0x20));
    /* tailcall */
    return _objc_copyWeak(arg1 + 0x28, arg2 + 0x28);
}

int64_t sub_4157d0(void* arg1)
{
    _objc_destroyWeak(arg1 + 0x28);
    /* tailcall */
    return _objc_release(*(arg1 + 0x20));
}

int64_t sub_4157f8(void* arg1)
{
    id x0_1 = _objc_loadWeakRetained(arg1 + 0x28);
    _objc_msgSend(x0_1, "processVoiceCommand:", *(arg1 + 0x20));
    /* tailcall */
    return _objc_release(x0_1);
}

int64_t sub_415834(void* arg1)
{
    id x0_1 = _objc_loadWeakRetained(arg1 + 0x20);
    _objc_msgSend(x0_1, "stopVoiceRecognition");
    /* tailcall */
    return _objc_release(x0_1);
}

int64_t sub_415868(void* arg1, void* arg2)
{
    /* tailcall */
    return _objc_copyWeak(arg1 + 0x20, arg2 + 0x20);
}

int64_t sub_415874(void* arg1)
{
    /* tailcall */
    return _objc_destroyWeak(arg1 + 0x20);
}

int64_t sub_41587c(int64_t arg1, int64_t arg2)
{
    /* tailcall */
    return _objc_msgSend(data_446a28, "appendAudioPCMBuffer:", arg2);
}

void -[ACPanelController stopVoiceRecognition](struct ACPanelController* self, SEL sel)
{
    if (_objc_msgSend(data_446a38, "isRunning"))
    {
        _objc_msgSend(data_446a38, "stop");
        id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(data_446a38, "inputNode"));
        _objc_msgSend(obj, "removeTapOnBus:", 0);
        _objc_release(obj);
    }
    
    id x0_6 = data_446a28;
    
    if (x0_6)
    {
        _objc_msgSend(x0_6, "endAudio");
        id obj_1 = data_446a28;
        data_446a28 = 0;
        _objc_release(obj_1);
    }
    
    id x0_7 = data_446a30;
    
    if (!x0_7)
        return;
    
    _objc_msgSend(x0_7, "cancel");
    id x0_8 = data_446a30;
    data_446a30 = 0;
    /* tailcall */
    return _objc_release(x0_8);
}

void -[ACPanelController processVoiceCommand:](struct ACPanelController* self, SEL sel, id processVoiceCommand)
{
    int64_t v15;
    int64_t var_a0 = v15;
    int64_t v14;
    int64_t var_98 = v14;
    int64_t v13;
    int64_t var_90 = v13;
    int64_t v12;
    int64_t var_88 = v12;
    double v11;
    double var_80 = v11;
    int64_t v10;
    int64_t var_78 = v10;
    int64_t v9;
    int64_t var_70 = v9;
    int64_t v8;
    int64_t var_68 = v8;
    int64_t x8 = *___stack_chk_guard;
    id obj_18 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(processVoiceCommand, "lowercaseString"));
    id obj_21 = obj_18;
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
        "stringWithFormat:", &cfstr_Voice_heard:_%@));
    sub_410c94(obj);
    _objc_release(obj);
    id obj_19;
    
    if (!_objc_msgSend(obj_18, "containsString:", &cfstr_spawn))
    {
        obj_19 = nullptr;
        sub_410c94(&cfstr_Voice:_Could_not_parse_command._Say:_Hey_AI_spawn_[item]_[quantity]);
    }
    else
    {
        id x0_9;
        int64_t x1;
        x0_9 = _objc_msgSend(obj_18, "rangeOfString:", &cfstr_spawn);
        id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_18, "substringFromIndex:", 
            x0_9 + x1));
        id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSCharacterSet, 
            "whitespaceCharacterSet"));
        obj_19 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_1, 
            "stringByTrimmingCharactersInSet:", obj_2));
        _objc_release(obj_2);
        _objc_release(obj_1);
        
        if (!obj_19)
            sub_410c94(&cfstr_Voice:_Could_not_parse_command._Say:_Hey_AI_spawn_[item]_[quantity]);
        else if (!_objc_msgSend(obj_19, "length"))
            sub_410c94(&cfstr_Voice:_Could_not_parse_command._Say:_Hey_AI_spawn_[item]_[quantity]);
        else
        {
            id obj_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_19, 
                "componentsSeparatedByString:", &cfstr__));
            id obj_4 =
                _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSMutableArray, "array"));
            int128_t var_280;
            __builtin_memset(&var_280, 0, 0x18);
            int128_t var_260;
            __builtin_memset(&var_260, 0, 0x20);
            id obj_5 = _objc_retain(obj_3);
            void var_138;
            id i_8 = _objc_msgSend(obj_5, "countByEnumeratingWithState:objects:count:", &var_280, 
                &var_138, 0x10);
            uint64_t var_348_1;
            
            if (!i_8)
                var_348_1 = 1;
            else
            {
                id i_4 = i_8;
                var_348_1 = 1;
                int64_t* var_270;
                int64_t x25_1 = *var_270;
                id i;
                
                do
                {
                    int64_t x22_1 = 0;
                    
                    do
                    {
                        if (*var_270 != x25_1)
                            _objc_enumerationMutation(obj_5);
                        
                        int64_t x19_3 = *(*(&var_280 + 8) + (x22_1 << 3));
                        int32_t x0_28 = _objc_msgSend(x19_3, "intValue");
                        id obj_6;
                        
                        if (x0_28 >= 1)
                        {
                            obj_6 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_5, 
                                "lastObject"));
                            _objc_release(obj_6);
                        }
                        
                        if (x0_28 >= 1 && x19_3 == obj_6)
                        {
                            uint64_t x8_5;
                            
                            x8_5 = x0_28 < 0x1f4 ? x0_28 : 0x1f4;
                            
                            var_348_1 = x8_5;
                        }
                        else
                            _objc_msgSend(obj_4, "addObject:", x19_3);
                        
                        x22_1 += 1;
                    } while (i_4 != x22_1);
                    
                    i = _objc_msgSend(obj_5, "countByEnumeratingWithState:objects:count:");
                    i_4 = i;
                } while (i);
            }
            
            _objc_release(obj_5);
            id obj_7 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_4, 
                "componentsJoinedByString:", &cfstr__));
            int128_t var_2c0;
            __builtin_memset(&var_2c0, 0, 0x18);
            int128_t var_2a0;
            __builtin_memset(&var_2a0, 0, 0x20);
            id obj_8 = _objc_retain(data_446a88);
            int64_t i_9 = _objc_msgSend(obj_8, "countByEnumeratingWithState:objects:count:");
            id obj_20;
            
            if (i_9)
            {
                int64_t i_5 = i_9;
                int64_t* var_2b0;
                int64_t x22_2 = *var_2b0;
                int64_t i_1;
                
                do
                {
                    int64_t x25_2 = 0;
                    
                    do
                    {
                        if (*var_2b0 != x22_2)
                            _objc_enumerationMutation(obj_8);
                        
                        id obj_16 = *(*(&var_2c0 + 8) + (x25_2 << 3));
                        id obj_9 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_16, 
                            "lowercaseString"));
                        int32_t x0_42 = _objc_msgSend(obj_9, "containsString:");
                        _objc_release(obj_9);
                        
                        if (x0_42 & 1)
                        {
                            obj_20 = _objc_retain(obj_16);
                            _objc_release(obj_8);
                            
                            if (obj_20)
                                goto label_415f0c;
                            
                            goto label_415dc0;
                        }
                        
                        x25_2 += 1;
                    } while (i_5 != x25_2);
                    
                    i_1 = _objc_msgSend(obj_8, "countByEnumeratingWithState:objects:count:");
                    i_5 = i_1;
                } while (i_1);
            }
            
            _objc_release(obj_8);
        label_415dc0:
            id obj_22 = obj_7;
            id obj_10 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
                "stringWithFormat:"));
            int128_t var_300;
            __builtin_memset(&var_300, 0, 0x18);
            int128_t var_2e0;
            __builtin_memset(&var_2e0, 0, 0x20);
            id obj_11 = _objc_retain(data_446a88);
            int64_t i_10 = _objc_msgSend(obj_11, "countByEnumeratingWithState:objects:count:");
            
            if (i_10)
            {
                int64_t i_7 = i_10;
                int64_t* var_2f0;
                int64_t x22_3 = *var_2f0;
                int64_t i_2;
                
                do
                {
                    int64_t x25_3 = 0;
                    
                    do
                    {
                        if (*var_2f0 != x22_3)
                            _objc_enumerationMutation(obj_11);
                        
                        id obj_17 = *(*(&var_300 + 8) + (x25_3 << 3));
                        id obj_12 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_17, 
                            "lowercaseString"));
                        int32_t x0_55 = _objc_msgSend(obj_12, "containsString:");
                        _objc_release(obj_12);
                        
                        if (x0_55 & 1)
                        {
                            obj_20 = _objc_retain(obj_17);
                            _objc_release(obj_11);
                            _objc_release(obj_10);
                            
                            if (obj_20)
                                goto label_415f0c;
                            
                            goto label_415eec;
                        }
                        
                        x25_3 += 1;
                    } while (i_7 != x25_3);
                    
                    i_2 = _objc_msgSend(obj_11, "countByEnumeratingWithState:objects:count:");
                    i_7 = i_2;
                } while (i_2);
            }
            
            _objc_release(obj_11);
            _objc_release(obj_10);
        label_415eec:
            id obj_23 = obj_7;
            obj_20 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
                "stringWithFormat:"));
        label_415f0c:
            int32_t v0_1;
            int32_t v1_1;
            int32_t v2_1;
            v0_1 = sub_4113d8();
            v10 = v1_1;
            id obj_24 = obj_20;
            uint64_t var_388_1 = var_348_1;
            id obj_13 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
                "stringWithFormat:"));
            sub_410c94(obj_13);
            _objc_release(obj_13);
            
            if (var_348_1 >= 1)
            {
                v10 = v10 + 1f;
                v11 = 0.0;
                v12 = -3f;
                int32_t i_6 = var_348_1;
                int32_t i_3;
                
                do
                {
                    v8 = 0x42c80000;
                    v9 = _arc4random_uniform(0x258) / v8 + v12;
                    uint32_t x0_71;
                    double v0_4;
                    x0_71 = _arc4random_uniform(0x258);
                    v0_4 = x0_71;
                    v0_4 = v0_4 / v8;
                    v0_4 = v0_4 + v12;
                    v8 = v0_1 + v9;
                    v9 = v2_1 + v0_4;
                    dispatch_time_t when =
                        _dispatch_time(0, vcvtd_s64_f64(v11 * 0.029999999999999999 * 1000000000.0));
                    _objc_retainAutorelease(__dispatch_main_q);
                    void* (* const var_338)[0x20] = __NSConcreteStackBlock;
                    int64_t var_330_1 = 0xc2000000;
                    int64_t (* var_328_1)(void* arg1) = sub_4160b4;
                    void* const var_320_1 = &data_43c130;
                    id obj_14 = _objc_retain(obj_20);
                    int32_t var_310_1 = v8;
                    int32_t var_30c_1 = v10;
                    int32_t var_308_1 = v9;
                    _dispatch_after(when, __dispatch_main_q, &var_338);
                    _objc_release(obj_14);
                    v11 = v11 + 1.0;
                    i_3 = i_6;
                    i_6 -= 1;
                } while (i_3 != 1);
            }
            
            id obj_25 = obj_20;
            uint64_t var_388_2 = var_348_1;
            id obj_15 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
                "stringWithFormat:"));
            sub_410c94(obj_15);
            _objc_release(obj_15);
            _objc_release(obj_20);
            _objc_release(obj_7);
            _objc_release(obj_4);
            _objc_release(obj_5);
        }
    }
    
    _objc_release(obj_19);
    _objc_release(obj_18);
    
    if (*___stack_chk_guard == x8)
        return;
    
    ___stack_chk_fail();
    /* no return */
}

int64_t sub_4160b4(void* arg1)
{
    int128_t v1;
    v1 = *(arg1 + 0x2c);
    int128_t v2;
    v2 = *(arg1 + 0x30);
    /* tailcall */
    return sub_4114c8(*(arg1 + 0x20), *(arg1 + 0x28));
}

void -[ACPanelController presetTapped:](struct ACPanelController* self, SEL sel, id presetTapped)
{
    int64_t v15;
    int64_t var_a0 = v15;
    int64_t v14;
    int64_t var_98 = v14;
    int64_t v13;
    int64_t var_90 = v13;
    int64_t v12;
    int64_t var_88 = v12;
    int64_t v11;
    int64_t var_80 = v11;
    int64_t v10;
    int64_t var_78 = v10;
    int64_t v9;
    int64_t var_70 = v9;
    int64_t v8;
    int64_t var_68 = v8;
    int64_t x8 = *___stack_chk_guard;
    void* __offset(objc_object, -0x7d0) x2 = _objc_msgSend(presetTapped, "tag") - 0x7d0;
    data_446768 = x2;
    data_446ad2 = 1;
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(data_4469d8, 
        "objectAtIndexedSubscript:", x2));
    int64_t var_140;
    _objc_msgSend(obj, "getValue:", &var_140);
    _objc_release(obj);
    data_446ad4 = var_140;
    int32_t var_138;
    data_446adc = var_138;
    int128_t var_180;
    __builtin_memset(&var_180, 0, 0x18);
    int128_t var_160;
    __builtin_memset(&var_160, 0, 0x20);
    id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "settingsContent"));
    id obj_7 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_1, "subviews"));
    _objc_release(obj_1);
    void var_130;
    id i_2 = _objc_msgSend(obj_7, "countByEnumeratingWithState:objects:count:", &var_180, &var_130, 
        0x10);
    
    if (i_2)
    {
        id i_1 = i_2;
        int64_t* var_170;
        int64_t x21_1 = *var_170;
        id obj_9 = obj_7;
        id i;
        
        do
        {
            int64_t x26_1 = 0;
            
            do
            {
                if (*var_170 != x21_1)
                    _objc_enumerationMutation(obj_7);
                
                id x23_1 = *(*(&var_180 + 8) + (x26_1 << 3));
                
                if (_objc_msgSend(x23_1, "tag") >= 0x7d0
                    && _objc_msgSend(x23_1, "tag") < &_objc_msgSend(data_4469d0, "count")[0xfa])
                {
                    _objc_msgSend(clsRef_UIButton, "class");
                    
                    if (_objc_msgSend(x23_1, "isKindOfClass:"))
                    {
                        id x0_23;
                        int128_t v0_1;
                        int128_t v1_1;
                        int128_t v2_1;
                        int128_t v3_1;
                        x0_23 = _objc_msgSend(x23_1, "tag");
                        
                        if (x0_23 - 0x7d0 != data_446768)
                        {
                            v3_1 = 1.0;
                            v0_1 = 0x3fa999999999999a;
                            v1_1 = 0x3fa47ae147ae147b;
                            v2_1 = 0x3fc1eb851eb851ec;
                        }
                        else
                        {
                            v1_1 = 0.25;
                            v3_1 = 1.0;
                            v0_1 = 0x3fb999999999999a;
                            v2_1 = 0x3fe199999999999a;
                        }
                        
                        id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(
                            clsRef_UIColor, "colorWithRed:green:blue:alpha:"));
                        _objc_msgSend(x23_1, "setBackgroundColor:");
                        int128_t v0_2;
                        int128_t v1_2;
                        int128_t v2_2;
                        int128_t v3_2;
                        v0_2 = _objc_release(obj_2);
                        
                        if (x0_23 - 0x7d0 != data_446768)
                        {
                            v2_2 = 1.0;
                            v3_2 = 1.0;
                            v0_2 = 0x3feb333333333333;
                            v1_2 = 0x3feccccccccccccd;
                        }
                        else
                        {
                            v3_2 = 1.0;
                            v0_2 = 0x3fb999999999999a;
                            v1_2 = 0x3fe999999999999a;
                            v2_2 = 0x3fee666666666666;
                        }
                        
                        id obj_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(
                            clsRef_UIColor, "colorWithRed:green:blue:alpha:"));
                        _objc_msgSend(x23_1, "setTitleColor:forState:");
                        _objc_release(obj_3);
                        obj_7 = obj_9;
                    }
                }
                
                x26_1 += 1;
            } while (i_1 != x26_1);
            
            i = _objc_msgSend(obj_7, "countByEnumeratingWithState:objects:count:");
            i_1 = i;
        } while (i);
    }
    
    _objc_release(obj_7);
    id clsRef_NSString_1 = clsRef_NSString;
    data_446768;
    id obj_4 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(data_4469d0, 
        "objectAtIndexedSubscript:"));
    id obj_8 = obj_4;
    int64_t obj_5 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString_1, 
        "stringWithFormat:", &cfstr_Location:_%@));
    id obj_6 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "locationLabel"));
    _objc_msgSend(obj_6, "setText:", obj_5);
    _objc_release(obj_6);
    _objc_release(obj_5);
    _objc_release(obj_4);
    
    if (*___stack_chk_guard == x8)
        return;
    
    ___stack_chk_fail();
    /* no return */
}

void -[ACPanelController usePlayerPosition](struct ACPanelController* self, SEL sel)
{
    float v0;
    float v1;
    float v2;
    v0 = sub_4113d8();
    *data_446ad4 = v0;
    *(data_446ad4 + 4) = v1;
    data_446adc = v2;
    data_446ad2 = 1;
    double v8 = v0;
    double v9 = v1;
    double v10 = v2;
    double var_78 = v9;
    double var_70 = v10;
    double var_80 = v8;
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
        "stringWithFormat:", &cfstr_Player_pos:_%.1f,_%.1f,_%.1f));
    id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "locationLabel"));
    _objc_msgSend(obj_1, "setText:", obj);
    _objc_release(obj_1);
    _objc_release(obj);
    double var_78_1 = v9;
    double var_70_1 = v10;
    double var_80_1 = v8;
    id x0_8 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
        "stringWithFormat:", &cfstr_Player_pos:_%.1f,_%.1f,_%.1f));
    sub_410c94(x0_8);
    /* tailcall */
    return _objc_release(x0_8);
}

void -[ACPanelController scanItemPositionsTapped](struct ACPanelController* self, SEL sel)
{
    double v9;
    double var_70 = v9;
    double v8;
    double var_68 = v8;
    int64_t x8 = *___stack_chk_guard;
    sub_410c94(&cfstr_Scanning_scene_for_spawned_items...);
    
    if (!data_446a10)
    {
        id x0_1 = _objc_msgSend(clsRef_NSMutableArray, "new");
        id obj_20 = data_446a10;
        data_446a10 = x0_1;
        _objc_release(obj_20);
    }
    
    if (!data_446a18)
    {
        id x0_4 = _objc_msgSend(clsRef_NSMutableArray, "new");
        id obj_21 = data_446a18;
        data_446a18 = x0_4;
        _objc_release(obj_21);
    }
    
    id obj_23 = _objc_msgSend(clsRef_NSMutableArray, "new");
    id obj = _objc_msgSend(clsRef_NSMutableArray, "new");
    struct __NSConstantString* const var_a8 = &cfstr_ItemInstance;
    struct __NSConstantString* const var_a0 = &cfstr_Item;
    struct __NSConstantString* const var_98 = &cfstr_ItemController;
    struct __NSConstantString* const var_90 = &cfstr_PickupItem;
    struct __NSConstantString* const var_88 = &cfstr_DroppedItem;
    id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &var_a8, 5));
    int128_t var_170;
    __builtin_memset(&var_170, 0, 0x18);
    int128_t var_150;
    __builtin_memset(&var_150, 0, 0x20);
    id obj_28 = _objc_retain(obj_1);
    id obj_22 = obj_28;
    void var_128;
    id i_3 = _objc_msgSend(obj_28, "countByEnumeratingWithState:objects:count:", &var_170, 
        &var_128, 0x10);
    id obj_27 = obj_23;
    id obj_26 = obj_22;
    
    if (i_3)
    {
        id i_1 = i_3;
        int64_t* var_160;
        int64_t x8_4 = *var_160;
        id i;
        
        do
        {
            int64_t x28_1 = 0;
            id i_2 = i_1;
            
            do
            {
                if (*var_160 != x8_4)
                    _objc_enumerationMutation(obj_22);
                
                int64_t x19_1 = data_446ae0;
                int64_t x21_1 = data_446ae8;
                id obj_2 = _objc_retainAutorelease(*(*(&var_170 + 8) + (x28_1 << 3)));
                int64_t x0_15 = x19_1(x21_1, &cstr_, _objc_msgSend(obj_2, "UTF8String"));
                
                if (!x0_15)
                    x0_15 = data_446ae0(data_446ae8, "AnimalCompany", 
                        _objc_msgSend(_objc_retainAutorelease(obj_2), "UTF8String"));
                
                bool z_1;
                
                if (x0_15)
                    z_1 = !data_446af0;
                else
                    z_1 = true;
                
                if (!z_1 && data_446af8())
                {
                    int64_t x0_21 = data_446b00();
                    
                    if (x0_21)
                    {
                        int64_t var_178 = 0;
                        int64_t var_130 = x0_21;
                        void* x0_23 = data_446b08(data_446af0, 0, &var_130, &var_178);
                        
                        if (x0_23 && !var_178)
                        {
                            uint64_t x20_1 = *(x0_23 + 0x18);
                            
                            if (x20_1 - 0xc9 >= 0xffffff38)
                            {
                                uint64_t var_230_1 = x20_1;
                                id obj_25 = obj_2;
                                id obj_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(
                                    clsRef_NSString, "stringWithFormat:"));
                                sub_410c94(obj_3);
                                _objc_release(obj_3);
                                int64_t j = 0;
                                int32_t x8_15;
                                
                                x8_15 = x20_1 - 1 < 0x31 ? x20_1 - 1 : 0x31;
                                
                                do
                                {
                                    int64_t x0_27 = *(x0_23 + 0x20 + (j << 3));
                                    
                                    if (x0_27)
                                    {
                                        double v0_1;
                                        double v1_1;
                                        double v2_1;
                                        v0_1 = sub_4127a8(x0_27);
                                        int32_t var_188 = v0_1;
                                        int32_t var_184_1 = v1_1;
                                        int32_t var_180_1 = v2_1;
                                        double var_218_1 = v1_1;
                                        double var_210_1 = v2_1;
                                        double var_220_1 = v0_1;
                                        id obj_24 = obj_2;
                                        int64_t j_1 = j;
                                        int64_t obj_4 = _objc_retainAutoreleasedReturnValue(
                                            _objc_msgSend(clsRef_NSString, "stringWithFormat:"));
                                        _objc_msgSend(obj_23, "addObject:", obj_4);
                                        int64_t obj_5 = _objc_retainAutoreleasedReturnValue(
                                            _objc_msgSend(clsRef_NSValue, 
                                            "valueWithBytes:objCType:", &var_188, "{?=fff}"));
                                        _objc_msgSend(obj, "addObject:", obj_5);
                                        obj_23 = obj_27;
                                        _objc_release(obj_5);
                                        _objc_release(obj_4);
                                    }
                                    
                                    j += 1;
                                } while (x8_15 + 1 != j);
                                
                                obj_22 = obj_26;
                                i_1 = i_2;
                                
                                if (_objc_msgSend(obj_23, "count"))
                                    goto label_416a50;
                            }
                        }
                    }
                }
                
                x28_1 += 1;
            } while (x28_1 != i_1);
            
            i = _objc_msgSend(obj_22, "countByEnumeratingWithState:objects:count:");
            i_1 = i;
        } while (i);
    }
    
label_416a50:
    _objc_release(obj_22);
    
    if (!_objc_msgSend(obj_23, "count"))
        sub_410c94(&cfstr_No_items_found_in_scene._Try_spawning_some_first!);
    else
    {
        id clsRef_UIAlertController_1 = clsRef_UIAlertController;
        id clsRef_NSString_1 = clsRef_NSString;
        int64_t var_230_2 = _objc_msgSend(obj_23, "count");
        int64_t obj_6 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString_1, 
            "stringWithFormat:", &cfstr_%lu_items_found));
        id obj_7 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIAlertController_1, 
            "alertControllerWithTitle:message:preferredStyle:", &cfstr_Select_Item_Position, obj_6, 
            0));
        _objc_release(obj_6);
        
        if (_objc_msgSend(obj_23, "count") > 0)
        {
            int64_t x25_1 = 0;
            int64_t x0_66;
            
            do
            {
                id obj_8 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_27, 
                    "objectAtIndexedSubscript:", x25_1));
                id obj_9 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj, 
                    "objectAtIndexedSubscript:", x25_1));
                id clsRef_UIAlertAction_1 = clsRef_UIAlertAction;
                void* (* const var_1c0)[0x20] = __NSConcreteStackBlock;
                int64_t var_1b8_1 = 0xc2000000;
                id (* var_1b0_1)(void* arg1) = sub_416e34;
                void* const var_1a8_1 = &data_43c320;
                struct ACPanelController* self_1 = self;
                id obj_10 = _objc_retain(obj_8);
                id obj_11 = _objc_retain(obj_9);
                id obj_12 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(
                    clsRef_UIAlertAction_1, "actionWithTitle:style:handler:", obj_10, 0, &var_1c0));
                _objc_msgSend(obj_7, "addAction:", obj_12);
                _objc_release(obj_12);
                _objc_release(obj_8);
                _objc_release(obj_9);
                _objc_release(obj_10);
                _objc_release(obj_11);
                x0_66 = _objc_msgSend(obj_27, "count");
                
                if (x25_1 > 0x12)
                    break;
                
                x25_1 += 1;
            } while (x25_1 < x0_66);
            obj_23 = obj_27;
            obj_22 = obj_26;
        }
        
        int64_t obj_13 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIAlertAction, 
            "actionWithTitle:style:handler:", &cfstr_Cancel, 1, 0));
        _objc_msgSend(obj_7, "addAction:", obj_13);
        _objc_release(obj_13);
        id obj_14 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_7, 
            "popoverPresentationController"));
        _objc_release(obj_14);
        
        if (obj_14)
        {
            id obj_15 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "view"));
            id obj_16 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_7, 
                "popoverPresentationController"));
            _objc_msgSend(obj_16, "setSourceView:", obj_15);
            _objc_release(obj_16);
            _objc_release(obj_15);
            id obj_17 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "view"));
            v9 = 0.5;
            v8 = _objc_msgSend(obj_17, "bounds") * v9;
            id obj_18 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "view"));
            v9 = _objc_msgSend(obj_18, "bounds") * v9;
            id obj_19;
            int64_t x2_16;
            int128_t v0_2;
            int128_t v1_2;
            int128_t v2_3;
            int128_t v3_2;
            obj_19 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_7, 
                "popoverPresentationController"));
            v2_3 = 1.0;
            v3_2 = 1.0;
            v0_2 = v8;
            v1_2 = v9;
            _objc_msgSend(obj_19, "setSourceRect:", x2_16);
            _objc_release(obj_19);
            _objc_release(obj_18);
            _objc_release(obj_17);
        }
        
        _objc_msgSend(self, "presentViewController:animated:completion:", obj_7, 1, 0);
        _objc_release(obj_7);
    }
    
    _objc_release(obj_22);
    _objc_release(obj);
    _objc_release(obj_23);
    
    if (*___stack_chk_guard == x8)
        return;
    
    ___stack_chk_fail();
    /* no return */
}

id sub_416e34(void* arg1)
{
    int64_t var_50;
    _objc_msgSend(*(arg1 + 0x20), "getValue:", &var_50);
    data_446ad4 = var_50;
    int32_t var_48;
    data_446adc = var_48;
    data_446ad2 = 1;
    _objc_msgSend(data_446a10, "addObject:", *(arg1 + 0x28));
    double v0;
    double v1;
    double v2;
    v0 = _objc_msgSend(data_446a18, "addObject:", *(arg1 + 0x20));
    v0 = var_50;
    v1 = *(&var_50 + 4);
    v2 = var_48;
    double var_68 = v1;
    double var_60 = v2;
    double var_70 = v0;
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
        "stringWithFormat:", &cfstr_Saved:_%.1f,_%.1f,_%.1f));
    id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(*(arg1 + 0x30), "locationLabel"));
    _objc_msgSend(obj_1, "setText:", obj);
    _objc_release(obj_1);
    _objc_release(obj);
    int64_t var_70_1 = *(arg1 + 0x28);
    id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
        "stringWithFormat:", &cfstr_Done_saved_position:_%@));
    sub_410c94(obj_2);
    _objc_release(obj_2);
    return _objc_msgSend(*(arg1 + 0x30), "refreshSavedPositions");
}

int64_t sub_416f98(int64_t arg1, void* arg2)
{
    _objc_retain(*(arg2 + 0x20));
    _objc_retain(*(arg2 + 0x28));
    /* tailcall */
    return _objc_retain(*(arg2 + 0x30));
}

int64_t sub_416fc8(void* arg1)
{
    _objc_release(*(arg1 + 0x30));
    _objc_release(*(arg1 + 0x28));
    /* tailcall */
    return _objc_release(*(arg1 + 0x20));
}

void -[ACPanelController refreshSavedPositions](struct ACPanelController* self, SEL sel)
{
    int64_t v14;
    int64_t var_98 = v14;
    int64_t v13;
    int64_t var_90 = v13;
    int64_t v12;
    int64_t var_88 = v12;
    int64_t v11;
    int64_t var_80 = v11;
    int64_t v10;
    int64_t var_78 = v10;
    double v9;
    double var_70 = v9;
    int64_t x8 = *___stack_chk_guard;
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "settingsContent"));
    id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj, "viewWithTag:", 0x898));
    _objc_release(obj);
    int128_t var_150;
    __builtin_memset(&var_150, 0, 0x20);
    int128_t var_170;
    __builtin_memset(&var_170, 0, 0x18);
    id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_1, "subviews"));
    void var_130;
    id i_2 = _objc_msgSend(obj_2, "countByEnumeratingWithState:objects:count:", &var_170, &var_130, 
        0x10);
    
    if (i_2)
    {
        id i_1 = i_2;
        int64_t* var_160;
        int64_t x23_1 = *var_160;
        id i;
        
        do
        {
            int64_t x25_1 = 0;
            
            do
            {
                if (*var_160 != x23_1)
                    _objc_enumerationMutation(obj_2);
                
                _objc_msgSend(*(*(&var_170 + 8) + (x25_1 << 3)), "removeFromSuperview");
                x25_1 += 1;
            } while (i_1 != x25_1);
            
            i = _objc_msgSend(obj_2, "countByEnumeratingWithState:objects:count:", &var_170, 
                &var_130, 0x10);
            i_1 = i;
        } while (i);
    }
    
    _objc_release(obj_2);
    int64_t v2 = _objc_msgSend(obj_1, "bounds");
    
    if (_objc_msgSend(data_446a10, "count") >= 1)
    {
        int64_t x22_1 = 0;
        v9 = 0.0;
        int64_t x0_46;
        
        do
        {
            int64_t obj_3;
            int128_t v0_1;
            int128_t v1_1;
            int128_t v2_1;
            int128_t v3_1;
            obj_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, 
                "buttonWithType:"));
            v3_1 = 0x4040000000000000;
            v0_1 = 0.0;
            v1_1 = v9;
            v2_1 = v2;
            int64_t x2_3;
            int64_t x3_2;
            int64_t x4_1;
            int64_t x5_1;
            int128_t v0_2;
            int128_t v1_2;
            int128_t v2_2;
            int128_t v3_2;
            x2_3 = _objc_msgSend(obj_3, "setFrame:");
            v3_2 = 1.0;
            v0_2 = 0x3fa999999999999a;
            v1_2 = 0x3fa47ae147ae147b;
            v2_2 = 0x3fc1eb851eb851ec;
            id obj_4 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
                "colorWithRed:green:blue:alpha:", x2_3, x3_2, x4_1, x5_1));
            _objc_msgSend(obj_3, "setBackgroundColor:");
            _objc_release(obj_4);
            id obj_5;
            int128_t v0_3;
            obj_5 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_3, "layer"));
            v0_3 = 8.0;
            _objc_msgSend(obj_5, "setCornerRadius:");
            _objc_release(obj_5);
            struct objc_class_t* clsRef_NSString_1 = clsRef_NSString;
            id obj_6 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(data_446a10, 
                "objectAtIndexedSubscript:"));
            id obj_12 = obj_6;
            id obj_7 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString_1, 
                "stringWithFormat:"));
            _objc_msgSend(obj_3, "setTitle:forState:");
            _objc_release(obj_7);
            int64_t x2_8;
            int64_t x3_4;
            int64_t x4_2;
            int64_t x5_2;
            int128_t v0_4;
            int128_t v1_3;
            int128_t v2_3;
            int128_t v3_3;
            x2_8 = _objc_release(obj_6);
            v2_3 = 1.0;
            v3_3 = 1.0;
            v0_4 = 0x3feb333333333333;
            v1_3 = 0x3feccccccccccccd;
            id obj_8 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
                "colorWithRed:green:blue:alpha:", x2_8, x3_4, x4_2, x5_2));
            _objc_msgSend(obj_3, "setTitleColor:forState:");
            _objc_release(obj_8);
            int128_t v0_5;
            v0_5 = 11.0;
            id obj_9 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
                "systemFontOfSize:"));
            id obj_10 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_3, "titleLabel"));
            _objc_msgSend(obj_10, "setFont:");
            _objc_release(obj_10);
            _objc_release(obj_9);
            id obj_11 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_3, "titleLabel"));
            _objc_msgSend(obj_11, "setAdjustsFontSizeToFitWidth:");
            _objc_release(obj_11);
            _objc_msgSend(obj_3, "setTag:");
            _objc_msgSend(obj_3, "addTarget:action:forControlEvents:", self, "savedPosTapped:", 
                0x40);
            _objc_msgSend(obj_1, "addSubview:", obj_3);
            _objc_release(obj_3);
            x0_46 = _objc_msgSend(data_446a10, "count");
            
            if (x22_1 > 6)
                break;
            
            v9 = v9 + 0x4042000000000000;
            x22_1 += 1;
        } while (x22_1 < x0_46);
    }
    
    _objc_release(obj_1);
    
    if (*___stack_chk_guard == x8)
        return;
    
    ___stack_chk_fail();
    /* no return */
}

void -[ACPanelController savedPosTapped:](struct ACPanelController* self, SEL sel, id savedPosTapped)
{
    id x0_1 = _objc_msgSend(savedPosTapped, "tag");
    
    if (x0_1 < 0x835 || x0_1 - 0x835 >= _objc_msgSend(data_446a18, "count"))
        return;
    
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(data_446a18, 
        "objectAtIndexedSubscript:", x0_1 - 0x835));
    int64_t var_50;
    _objc_msgSend(obj, "getValue:", &var_50);
    double v0_1;
    double v1_1;
    double v2_1;
    v0_1 = _objc_release(obj);
    data_446ad4 = var_50;
    int32_t var_48;
    data_446adc = var_48;
    data_446ad2 = 1;
    v0_1 = var_50;
    v1_1 = *(&var_50 + 4);
    v2_1 = var_48;
    double var_68_1 = v1_1;
    double var_60_1 = v2_1;
    double var_70_1 = v0_1;
    id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
        "stringWithFormat:", &cfstr_Saved:_%.1f,_%.1f,_%.1f));
    id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "locationLabel"));
    _objc_msgSend(obj_2, "setText:", obj_1);
    _objc_release(obj_2);
    _objc_release(obj_1);
    struct objc_class_t* clsRef_NSString_1 = clsRef_NSString;
    id obj_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(data_446a10, 
        "objectAtIndexedSubscript:", x0_1 - 0x835));
    id obj_5 = obj_3;
    id obj_4 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString_1, 
        "stringWithFormat:", &cfstr_Using_saved_position:_%@));
    sub_410c94(obj_4);
    _objc_release(obj_4);
    _objc_release(obj_3);
}

void -[ACPanelController scanWorldItemsTapped](struct ACPanelController* self, SEL sel)
{
    int64_t x8 = *___stack_chk_guard;
    sub_410c94(&cfstr_Scanning_world_for_all_items...);
    id x0 = data_446a40;
    
    if (!x0)
    {
        id x0_2 = _objc_msgSend(clsRef_NSMutableArray, "new");
        id obj_9 = data_446a40;
        data_446a40 = x0_2;
        _objc_release(obj_9);
        x0 = data_446a40;
    }
    
    _objc_msgSend(x0, "removeAllObjects");
    struct __NSConstantString* const var_98 = &cfstr_ItemInstance;
    struct __NSConstantString* const var_90 = &cfstr_Item;
    struct __NSConstantString* const var_88 = &cfstr_ItemController;
    struct __NSConstantString* const var_80 = &cfstr_PickupItem;
    struct __NSConstantString* const var_78 = &cfstr_DroppedItem;
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &var_98, 5));
    id obj_1 = _objc_msgSend(clsRef_NSMutableSet, "new");
    int128_t var_160;
    __builtin_memset(&var_160, 0, 0x18);
    int128_t var_140;
    __builtin_memset(&var_140, 0, 0x20);
    id obj_14 = _objc_retain(obj);
    id obj_10 = obj_14;
    void var_118;
    id i_2 = _objc_msgSend(obj_14, "countByEnumeratingWithState:objects:count:", &var_160, 
        &var_118, 0x10);
    id obj_13 = obj_10;
    
    if (i_2)
    {
        id i_1 = i_2;
        int64_t* var_150;
        int64_t x8_2 = *var_150;
        id i;
        
        do
        {
            int64_t x27_1 = 0;
            
            do
            {
                if (*var_150 != x8_2)
                    _objc_enumerationMutation(obj_10);
                
                int64_t x21_1 = data_446ae0;
                int64_t x19_1 = data_446ae8;
                id obj_2 = _objc_retainAutorelease(*(*(&var_160 + 8) + (x27_1 << 3)));
                int64_t x0_12 = x21_1(x19_1, &cstr_, _objc_msgSend(obj_2, "UTF8String"));
                int64_t x19_2 = x0_12;
                
                if (!x0_12)
                    x19_2 = data_446ae0(data_446ae8, "AnimalCompany", 
                        _objc_msgSend(_objc_retainAutorelease(obj_2), "UTF8String"));
                
                bool z_1;
                
                if (x19_2)
                    z_1 = !data_446af0;
                else
                    z_1 = true;
                
                if (!z_1 && data_446af8(x19_2))
                {
                    int64_t x0_20 = data_446b00();
                    
                    if (x0_20)
                    {
                        int64_t var_168 = 0;
                        int64_t var_120 = x0_20;
                        void* x0_22 = data_446b08(data_446af0, 0, &var_120, &var_168);
                        
                        if (x0_22 && !var_168)
                        {
                            uint64_t j_1 = *(x0_22 + 0x18);
                            
                            if (j_1 - 0x1f5 >= 0xfffffe0c)
                            {
                                uint64_t j_2 = j_1;
                                id obj_12 = obj_2;
                                id obj_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(
                                    clsRef_NSString, "stringWithFormat:"));
                                sub_410c94(obj_3);
                                _objc_release(obj_3);
                                int64_t* x21_4 = x0_22 + 0x20;
                                uint64_t j;
                                
                                do
                                {
                                    int64_t x20_3 = *x21_4;
                                    
                                    if (x20_3)
                                    {
                                        int64_t x0_27 = data_446b10(x19_2, "get_name", 0);
                                        void* const var_170;
                                        id obj_11;
                                        
                                        if (x0_27)
                                        {
                                            var_170 = nullptr;
                                            void* x0_28 = data_446b08(x0_27, x20_3, 0, &var_170);
                                            bool z_2;
                                            
                                            z_2 = x0_28 ? !var_170 : false;
                                            
                                            if (!z_2 || *(x0_28 + 0x10) - 1 >= 0xff)
                                                goto label_417a04;
                                            
                                            id obj_15 = _objc_msgSend(_objc_alloc(clsRef_NSString), 
                                                "initWithCharacters:length:", x0_28 + 0x14, 
                                                *(x0_28 + 0x10));
                                            obj_11 = obj_15;
                                            
                                            if (obj_15)
                                                goto label_417bcc;
                                            
                                            goto label_417a04;
                                        }
                                        
                                    label_417a04:
                                        int64_t x0_32 = data_446b18(x19_2, "itemName");
                                        
                                        if (!x0_32)
                                        {
                                        label_417a74:
                                            int64_t x0_37 = data_446b18(x19_2, "name");
                                            
                                            if (x0_37)
                                            {
                                                var_170 = nullptr;
                                                data_446b20(x20_3, x0_37, &var_170);
                                                void* const x28_3 = var_170;
                                                
                                                if (!x28_3 || *(x28_3 + 0x10) - 1 >= 0xff)
                                                    goto label_417ae4;
                                                
                                                id obj_17 = _objc_msgSend(
                                                    _objc_alloc(clsRef_NSString), 
                                                    "initWithCharacters:length:", x28_3 + 0x14, 
                                                    *(x28_3 + 0x10));
                                                obj_11 = obj_17;
                                                
                                                if (obj_17)
                                                    goto label_417bcc;
                                                
                                                goto label_417ae4;
                                            }
                                            
                                        label_417ae4:
                                            int64_t x0_42 = data_446b18(x19_2, "prefabName");
                                            
                                            if (x0_42)
                                            {
                                                var_170 = nullptr;
                                                data_446b20(x20_3, x0_42, &var_170);
                                                void* const x28_4 = var_170;
                                                
                                                if (!x28_4 || *(x28_4 + 0x10) - 1 >= 0xff)
                                                    goto label_417b5c;
                                                
                                                id obj_18 = _objc_msgSend(
                                                    _objc_alloc(clsRef_NSString), 
                                                    "initWithCharacters:length:", x28_4 + 0x14, 
                                                    *(x28_4 + 0x10));
                                                obj_11 = obj_18;
                                                
                                                if (obj_18)
                                                    goto label_417bcc;
                                                
                                                goto label_417b5c;
                                            }
                                            
                                        label_417b5c:
                                            int64_t x0_47 = data_446b10(x19_2, "ToString", 0);
                                            void* x0_48;
                                            
                                            if (x0_47)
                                            {
                                                var_170 = nullptr;
                                                x0_48 = data_446b08(x0_47, x20_3, 0, &var_170);
                                            }
                                            
                                            if (!x0_47 || !x0_48 || var_170
                                                    || *(x0_48 + 0x10) - 1 >= 0xff)
                                                obj_11 = nullptr;
                                            else
                                            {
                                                id obj_19 = _objc_msgSend(
                                                    _objc_alloc(clsRef_NSString), 
                                                    "initWithCharacters:length:", x0_48 + 0x14, 
                                                    *(x0_48 + 0x10));
                                                obj_11 = obj_19;
                                                
                                                if (obj_19)
                                                    goto label_417bcc;
                                            }
                                        }
                                        else
                                        {
                                            var_170 = nullptr;
                                            data_446b20(x20_3, x0_32, &var_170);
                                            void* const x28_2 = var_170;
                                            
                                            if (!x28_2 || *(x28_2 + 0x10) - 1 >= 0xff)
                                                goto label_417a74;
                                            
                                            id obj_16 = _objc_msgSend(_objc_alloc(clsRef_NSString), 
                                                "initWithCharacters:length:", x28_2 + 0x14, 
                                                *(x28_2 + 0x10));
                                            obj_11 = obj_16;
                                            
                                            if (!obj_16)
                                                goto label_417a74;
                                            
                                        label_417bcc:
                                            
                                            if (_objc_msgSend(obj_11, "length"))
                                                _objc_msgSend(obj_1, "addObject:");
                                        }
                                        
                                        _objc_release(obj_11);
                                    }
                                    
                                    x21_4 = &x21_4[1];
                                    j = j_1;
                                    j_1 -= 1;
                                } while (j != 1);
                                obj_10 = obj_13;
                                
                                if (_objc_msgSend(obj_1, "count"))
                                    goto label_417c44;
                            }
                        }
                    }
                }
                
                x27_1 += 1;
            } while (x27_1 != i_1);
            
            i = _objc_msgSend(obj_10, "countByEnumeratingWithState:objects:count:");
            i_1 = i;
        } while (i);
    }
    
label_417c44:
    _objc_release(obj_10);
    id x19_4 = data_446a40;
    id obj_4 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_1, "allObjects"));
    _objc_msgSend(x19_4, "addObjectsFromArray:", obj_4);
    _objc_release(obj_4);
    _objc_msgSend(data_446a40, "sortUsingSelector:", "compare:");
    id obj_5 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "settingsContent"));
    id obj_6 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_5, "viewWithTag:", 0x8fc));
    _objc_release(obj_5);
    
    if (obj_6)
    {
        id clsRef_NSString_2 = clsRef_NSString;
        id var_1d0_1 = _objc_msgSend(data_446a40, "count");
        int64_t obj_7 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString_2, 
            "stringWithFormat:", &cfstr_Found_%lu_unique_items));
        _objc_msgSend(obj_6, "setText:", obj_7);
        obj_10 = obj_13;
        _objc_release(obj_7);
        _objc_release(obj_6);
    }
    
    struct objc_class_t* clsRef_NSString_1 = clsRef_NSString;
    id var_1d0_2 = _objc_msgSend(data_446a40, "count");
    id obj_8 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString_1, 
        "stringWithFormat:", &cfstr_World_scan:_found_%lu_unique_item_names));
    sub_410c94(obj_8);
    _objc_release(obj_8);
    _objc_release(obj_1);
    _objc_release(obj_10);
    
    if (*___stack_chk_guard == x8)
        return;
    
    ___stack_chk_fail();
    /* no return */
}

void -[ACPanelController saveWorldItemsTapped](struct ACPanelController* self, SEL sel)
{
    id x0 = data_446a40;
    id x0_1;
    
    if (x0)
        x0_1 = _objc_msgSend(x0, "count");
    
    id x19;
    
    if (!x0 || !x0_1)
    {
        sub_410c94(&cfstr_No_items_to_save._Run_a_scan_first!);
        id obj_6 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "settingsContent"));
        x19 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_6, "viewWithTag:", 0x8fc));
        _objc_release(obj_6);
        
        if (x19)
            _objc_msgSend(x19, "setText:", &cfstr_No_items_to_save_-_scan_first!);
    }
    else
    {
        id obj = _objc_retainAutoreleasedReturnValue(_NSSearchPathForDirectoriesInDomains(
            NSDocumentDirectory, 1, true));
        x19 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj, "firstObject"));
        _objc_release(obj);
        id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(x19, 
            "stringByAppendingPathComponent:", &cfstr_orbit_saved_items.txt));
        _objc_storeStrong(&data_446a48, obj_1);
        id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(data_446a40, 
            "componentsJoinedByString:", &cfstr_\n));
        _objc_msgSend(obj_2, "writeToFile:atomically:encoding:error:", obj_1, 1, 4, 0);
        _objc_release(obj_2);
        id obj_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "settingsContent"));
        id obj_4 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_3, "viewWithTag:", 0x8fc));
        _objc_release(obj_3);
        
        if (obj_4)
        {
            struct objc_class_t* clsRef_NSString_2 = clsRef_NSString;
            id var_60_1 = _objc_msgSend(data_446a40, "count");
            id obj_5 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString_2, 
                "stringWithFormat:", &cfstr_Saved_%lu_items_to_file!));
            _objc_msgSend(obj_4, "setText:", obj_5);
            _objc_release(obj_5);
            _objc_release(obj_4);
        }
        
        struct objc_class_t* clsRef_NSString_1 = clsRef_NSString;
        id var_60_2 = _objc_msgSend(data_446a40, "count");
        id obj_8 = obj_1;
        id obj_7 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString_1, 
            "stringWithFormat:", &cfstr_Saved_%lu_items_to_%@));
        sub_410c94(obj_7);
        _objc_release(obj_7);
        _objc_release(obj_1);
    }
    
    /* tailcall */
    return _objc_release(x19);
}

void -[ACPanelController loadAndSpawnWorldItemsTapped](struct ACPanelController* self, SEL sel)
{
    int64_t v13;
    int64_t var_90 = v13;
    int64_t v12;
    int64_t var_88 = v12;
    int64_t v11;
    int64_t var_80 = v11;
    int64_t v10;
    int64_t var_78 = v10;
    int64_t v9;
    int64_t var_70 = v9;
    int64_t v8;
    int64_t var_68 = v8;
    int64_t x8 = *___stack_chk_guard;
    id obj = _objc_retainAutoreleasedReturnValue(_NSSearchPathForDirectoriesInDomains(
        NSDocumentDirectory, 1, true));
    id obj_15 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj, "firstObject"));
    _objc_release(obj);
    id obj_16 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_15, 
        "stringByAppendingPathComponent:", &cfstr_orbit_saved_items.txt));
    id obj_1 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSFileManager, "defaultManager"));
    int32_t x0_9 = _objc_msgSend(obj_1, "fileExistsAtPath:", obj_16);
    _objc_release(obj_1);
    
    if (!(x0_9 & 1))
    {
        sub_410c94(&cfstr_No_saved_items_file_found._Scan_and_save_first!);
        id obj_6 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "settingsContent"));
        id obj_7 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_6, "viewWithTag:", 0x8fc));
        _objc_release(obj_6);
        
        if (obj_7)
            _objc_msgSend(obj_7, "setText:", &cfstr_No_saved_file_found!);
        
        _objc_release(obj_7);
    }
    else
    {
        id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
            "stringWithContentsOfFile:encoding:error:", obj_16, 4, 0));
        id obj_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_2, 
            "componentsSeparatedByString:", &cfstr_\n));
        id obj_4 = _objc_msgSend(clsRef_NSMutableArray, "new");
        int128_t var_170;
        __builtin_memset(&var_170, 0, 0x18);
        int128_t var_150;
        __builtin_memset(&var_150, 0, 0x20);
        id obj_5 = _objc_retain(obj_3);
        void var_128;
        id i_2 = _objc_msgSend(obj_5, "countByEnumeratingWithState:objects:count:", &var_170, 
            &var_128, 0x10);
        
        if (i_2)
        {
            id i_1 = i_2;
            int64_t* var_160;
            int64_t x21_1 = *var_160;
            id i;
            
            do
            {
                int64_t x20_1 = 0;
                
                do
                {
                    if (*var_160 != x21_1)
                        _objc_enumerationMutation(obj_5);
                    
                    int64_t x28_1 = *(*(&var_170 + 8) + (x20_1 << 3));
                    
                    if (_objc_msgSend(x28_1, "length"))
                        _objc_msgSend(obj_4, "addObject:", x28_1);
                    
                    x20_1 += 1;
                } while (i_1 != x20_1);
                
                i = _objc_msgSend(obj_5, "countByEnumeratingWithState:objects:count:", &var_170, 
                    &var_128, 0x10);
                i_1 = i;
            } while (i);
        }
        
        _objc_release(obj_5);
        
        if (!_objc_msgSend(obj_4, "count"))
            sub_410c94(&cfstr_Saved_file_is_empty!);
        else
        {
            if (data_446ad2 != 1)
            {
                int32_t v0_1;
                int32_t v1_1;
                int32_t v2_1;
                v0_1 = sub_4113d8();
                v8 = v0_1;
                v9 = v1_1;
                v10 = v2_1;
            }
            else
            {
                v8 = *data_446ad4;
                v9 = *(data_446ad4 + 4);
                v10 = data_446adc;
            }
            
            struct objc_class_t* clsRef_NSString_1 = clsRef_NSString;
            id var_210_1 = _objc_msgSend(obj_4, "count");
            id obj_8 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString_1, 
                "stringWithFormat:", &cfstr_Spawning_%lu_saved_items...));
            sub_410c94(obj_8);
            _objc_release(obj_8);
            id obj_9 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "settingsContent"));
            id obj_10 =
                _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_9, "viewWithTag:", 0x8fc));
            _objc_release(obj_9);
            
            if (obj_10)
            {
                id clsRef_NSString_2 = clsRef_NSString;
                id var_210_2 = _objc_msgSend(obj_4, "count");
                int64_t obj_11 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(
                    clsRef_NSString_2, "stringWithFormat:", &cfstr_Spawning_%lu_items...));
                _objc_msgSend(obj_10, "setText:", obj_11);
                _objc_release(obj_11);
            }
            
            if (_objc_msgSend(obj_4, "count"))
            {
                int64_t x27_2 = 0;
                id x0_55;
                
                do
                {
                    id obj_12 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_4, 
                        "objectAtIndexedSubscript:", x27_2));
                    dispatch_time_t when = _dispatch_time(0, 
                        vcvtd_s64_f64(x27_2 * 0.050000000000000003 * 1000000000.0));
                    _objc_retainAutorelease(__dispatch_main_q);
                    void* (* const var_1a8)[0x20] = __NSConcreteStackBlock;
                    int64_t var_1a0_1 = 0xc2000000;
                    int64_t (* var_198_1)(void* arg1) = sub_418658;
                    void* const var_190_1 = &data_43c130;
                    int32_t var_180_1 = v8;
                    int32_t var_17c_1 = v9;
                    int32_t var_178_1 = v10;
                    id obj_13 = _objc_retain(obj_12);
                    _dispatch_after(when, __dispatch_main_q, &var_1a8);
                    _objc_release(obj_12);
                    _objc_release(obj_13);
                    x27_2 += 1;
                    x0_55 = _objc_msgSend(obj_4, "count");
                } while (x27_2 < x0_55);
            }
            
            dispatch_time_t when_1 = _dispatch_time(0, 
                vcvtd_s64_f64(_objc_msgSend(obj_4, "count") * 0.050000000000000003 * 1000000000.0));
            _objc_retainAutorelease(__dispatch_main_q);
            void* (* const var_1d8)[0x20] = __NSConcreteStackBlock;
            int64_t var_1d0_1 = 0xc2000000;
            int64_t (* var_1c8_1)(void* arg1) = sub_41866c;
            void* const var_1c0_1 = &data_43c350;
            id obj_14 = _objc_retain(obj_4);
            struct ACPanelController* self_1 = self;
            _dispatch_after(when_1, __dispatch_main_q, &var_1d8);
            _objc_release(obj_14);
            _objc_release(obj_10);
        }
        
        _objc_release(obj_4);
        _objc_release(obj_5);
        _objc_release(obj_2);
    }
    
    _objc_release(obj_16);
    _objc_release(obj_15);
    
    if (*___stack_chk_guard == x8)
        return;
    
    ___stack_chk_fail();
    /* no return */
}

int64_t sub_418658(void* arg1)
{
    int128_t v1;
    v1 = *(arg1 + 0x2c);
    int128_t v2;
    v2 = *(arg1 + 0x30);
    /* tailcall */
    return sub_4114c8(*(arg1 + 0x20), *(arg1 + 0x28));
}

int64_t sub_41866c(void* arg1)
{
    struct objc_class_t* clsRef_NSString_1 = clsRef_NSString;
    id var_50 = _objc_msgSend(*(arg1 + 0x20), "count");
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString_1, 
        "stringWithFormat:", &cfstr_Done_spawning_%lu_items!));
    sub_410c94(obj);
    _objc_release(obj);
    id obj_1 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(*(arg1 + 0x28), "settingsContent"));
    id x0_8 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_1, "viewWithTag:", 0x8fc));
    _objc_release(obj_1);
    
    if (x0_8)
    {
        struct objc_class_t* clsRef_NSString_2 = clsRef_NSString;
        id var_50_1 = _objc_msgSend(*(arg1 + 0x20), "count");
        id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString_2, 
            "stringWithFormat:", &cfstr_Spawned_%lu_items!));
        _objc_msgSend(x0_8, "setText:", obj_2);
        _objc_release(obj_2);
    }
    
    /* tailcall */
    return _objc_release(x0_8);
}

void -[ACPanelController heartLoopToggled](struct ACPanelController* self, SEL sel)
{
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "heartLoopSwitch"));
    data_446b28 = _objc_msgSend(obj, "isOn");
    _objc_release(obj);
    uint32_t x8 = data_446b28;
    id x0_3 = data_4469f0;
    bool z;
    
    z = !x8 ? !x0_3 : true;
    
    struct __NSConstantString* const x0_4;
    
    if (!z)
    {
        _objc_msgSend(x0_3, "invalidate");
        id obj_1 = data_4469f0;
        data_4469f0 = 0;
        _objc_release(obj_1);
        x0_4 = &cfstr_Heart_loop_disabled;
    }
    else
    {
        if (!x8)
            return;
        
        x0_4 = &cfstr_Heart_loop_enabled_-_next_heart_tap_will_repeat;
    }
    
    /* tailcall */
    return sub_410c94(x0_4);
}

void -[ACPanelController openDiscord](struct ACPanelController* self, SEL sel)
{
    id x0_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSURL, "URLWithString:", 
        &cfstr_https://discord.gg/ezWxtYS5nD));
    
    if (x0_2)
    {
        id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIApplication, 
            "sharedApplication"));
        _objc_msgSend(obj, "openURL:options:completionHandler:", x0_2, *___NSDictionary0__, 0);
        _objc_release(obj);
    }
    
    /* tailcall */
    return _objc_release(x0_2);
}

void -[ACPanelController colorEnableToggled:](struct ACPanelController* self, SEL sel, id colorEnableToggled)
{
    int32_t x0_1 = _objc_msgSend(colorEnableToggled, "isOn");
    data_446ac0 = x0_1;
    struct __NSConstantString* const x0_2;
    
    x0_2 = x0_1 ? &cfstr_Color_spawning_ON : &cfstr_Color_spawning_OFF;
    
    /* tailcall */
    return sub_410c94(x0_2);
}

void -[ACPanelController colorSliderChanged](struct ACPanelController* self, SEL sel)
{
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "redSlider"));
    data_446ac4 = vcvts_s32_f32(_objc_msgSend(obj, "value"));
    _objc_release(obj);
    id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "greenSlider"));
    data_446760 = vcvts_s32_f32(_objc_msgSend(obj_1, "value"));
    int64_t x2;
    int64_t x3;
    int64_t x4;
    int64_t x5;
    int128_t v1;
    int128_t v3;
    x2 = _objc_release(obj_1);
    data_446ac4;
    v1 = 0x4076800000000000;
    v1 = 0x406fe00000000000;
    v1 = data_446760 / 255.0;
    v3 = 1.0;
    id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithHue:saturation:brightness:alpha:", x2, x3, x4, x5));
    id obj_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "colorPreview"));
    _objc_msgSend(obj_3, "setBackgroundColor:", obj_2);
    _objc_release(obj_3);
    _objc_release(obj_2);
    id obj_4 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnerInner"));
    id x0_14 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_4, "viewWithTag:", 0x368));
    _objc_release(obj_4);
    uint64_t var_70 = data_446ac4;
    id obj_5 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
        "stringWithFormat:", &cfstr_%d));
    _objc_msgSend(x0_14, "setText:", obj_5);
    _objc_release(obj_5);
    id obj_6 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnerInner"));
    id obj_7 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_6, "viewWithTag:", 0x369));
    _objc_release(obj_6);
    uint64_t var_70_1 = data_446760;
    id obj_8 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
        "stringWithFormat:", &cfstr_%d));
    _objc_msgSend(obj_7, "setText:", obj_8);
    _objc_release(obj_8);
    id obj_9 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnerInner"));
    id obj_10 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_9, "viewWithTag:", 0x36a));
    _objc_release(obj_9);
    uint64_t var_70_2 = data_446ac4;
    uint64_t var_68 = data_446760;
    id obj_11 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
        "stringWithFormat:", &cfstr_colorHue:_%d__colorSaturation:_%d));
    _objc_msgSend(obj_10, "setText:", obj_11);
    _objc_release(obj_11);
    _objc_release(obj_10);
    _objc_release(obj_7);
    /* tailcall */
    return _objc_release(x0_14);
}

void -[ACPanelController randomColorTapped](struct ACPanelController* self, SEL sel)
{
    data_446ac4 = _arc4random_uniform(0x169);
    data_446760 = _arc4random_uniform(0xc0) + 0x40;
    int64_t v8;
    v8 = data_446ac4;
    id obj;
    int64_t x2;
    int128_t v0_1;
    obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "redSlider"));
    v0_1 = v8;
    _objc_msgSend(obj, "setValue:", x2);
    _objc_release(obj);
    v8 = data_446760;
    id obj_1;
    int64_t x2_1;
    int128_t v0_3;
    obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "greenSlider"));
    v0_3 = v8;
    _objc_msgSend(obj_1, "setValue:", x2_1);
    _objc_release(obj_1);
    /* tailcall */
    return _objc_msgSend(self, "colorSliderChanged");
}

void -[ACPanelController randomColorToggled](struct ACPanelController* self, SEL sel)
{
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "randomColorSwitch"));
    data_446ac8 = _objc_msgSend(obj, "isOn");
    _objc_release(obj);
    struct __NSConstantString_UTF16* const x0_3;
    
    if (!data_446ac8)
        x0_3 = &cfstr_Color_randomize_OFF;
    else
        x0_3 = &cfstr_Color_randomize_ON_?_each_item_gets_random_color;
    
    /* tailcall */
    return sub_410c94(x0_3);
}

void -[ACPanelController colorPresetTapped:](struct ACPanelController* self, SEL sel, id colorPresetTapped)
{
    int64_t v8;
    int64_t var_68 = v8;
    int64_t x8 = *___stack_chk_guard;
    struct objc_class_t* clsRef_NSNumber_1 = clsRef_NSNumber;
    id obj = _objc_retain(colorPresetTapped);
    id obj_1 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber_1, "numberWithInt:", 0));
    id obj_15 = obj_1;
    id obj_2 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, "numberWithInt:", 0xf0));
    id obj_16 = obj_2;
    id obj_3 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, "numberWithInt:", 0x78));
    id obj_17 = obj_3;
    id obj_4 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, "numberWithInt:", 0x2d));
    id obj_18 = obj_4;
    id obj_5 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, "numberWithInt:", 
        0x14a));
    id obj_19 = obj_5;
    id obj_6 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, "numberWithInt:", 0xb4));
    id obj_20 = obj_6;
    id obj_7 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &obj_15, 6));
    _objc_release(obj_6);
    _objc_release(obj_5);
    _objc_release(obj_4);
    _objc_release(obj_3);
    _objc_release(obj_2);
    _objc_release(obj_1);
    id x0_22 = _objc_msgSend(colorPresetTapped, "tag");
    _objc_release(obj);
    
    if (x0_22 >= 0x708 && x0_22 - 0x708 < _objc_msgSend(obj_7, "count"))
    {
        id obj_8 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_7, 
            "objectAtIndexedSubscript:", x0_22 - 0x708));
        data_446ac4 = _objc_msgSend(obj_8, "intValue");
        _objc_release(obj_8);
        data_446760 = 0xc8;
        data_446ac0 = 1;
        v8 = data_446ac4;
        id obj_9;
        int64_t x2_2;
        int128_t v0_2;
        obj_9 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "redSlider"));
        v0_2 = v8;
        _objc_msgSend(obj_9, "setValue:", x2_2);
        _objc_release(obj_9);
        v8 = data_446760;
        id obj_10;
        int64_t x2_3;
        int128_t v0_4;
        obj_10 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "greenSlider"));
        v0_4 = v8;
        _objc_msgSend(obj_10, "setValue:", x2_3);
        _objc_release(obj_10);
        id obj_11 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnerInner"));
        id obj_12 =
            _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_11, "viewWithTag:", 0x366));
        id obj_13 =
            _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_12, "viewWithTag:", 0x367));
        _objc_release(obj_12);
        _objc_release(obj_11);
        
        if (obj_13)
            _objc_msgSend(obj_13, "setOn:", 1);
        
        _objc_msgSend(self, "colorSliderChanged");
        uint64_t var_b0_1 = data_446ac4;
        id obj_14 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
            "stringWithFormat:", &cfstr_Color_preset:_Hue_%d));
        sub_410c94(obj_14);
        _objc_release(obj_14);
        _objc_release(obj_13);
    }
    
    _objc_release(obj_7);
    
    if (*___stack_chk_guard == x8)
        return;
    
    ___stack_chk_fail();
    /* no return */
}

void -[ACPanelController scaleEnableToggled:](struct ACPanelController* self, SEL sel, id scaleEnableToggled)
{
    int32_t x0_1 = _objc_msgSend(scaleEnableToggled, "isOn");
    data_446ac9 = x0_1;
    struct __NSConstantString* const x0_2;
    
    x0_2 = x0_1 ? &cfstr_Scale_modifier_ON : &cfstr_Scale_modifier_OFF;
    
    /* tailcall */
    return sub_410c94(x0_2);
}

void -[ACPanelController scaleSliderChanged:](struct ACPanelController* self, SEL sel, id scaleSliderChanged)
{
    data_446acc = vcvts_s32_f32(_objc_msgSend(scaleSliderChanged, "value"));
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnerInner"));
    id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj, "viewWithTag:", 0x366));
    id x0_5 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_1, "viewWithTag:", 0x36e));
    _objc_release(obj_1);
    _objc_release(obj);
    uint64_t var_40 = data_446acc;
    id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
        "stringWithFormat:", &cfstr_%d));
    _objc_msgSend(x0_5, "setText:", obj_2);
    _objc_release(obj_2);
    /* tailcall */
    return _objc_release(x0_5);
}

void -[ACPanelController loadJSONTapped](struct ACPanelController* self, SEL sel)
{
    int64_t x8 = *___stack_chk_guard;
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UTType, 
        "typeWithIdentifier:", &cfstr_public.json));
    id x0_3 = _objc_alloc(clsRef_UIDocumentPickerViewController);
    id obj_3 = obj;
    id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &obj_3, 1));
    id obj_2 = _objc_msgSend(x0_3, "initForOpeningContentTypes:asCopy:", obj_1, 1);
    _objc_release(obj_1);
    _objc_msgSend(obj_2, "setDelegate:", self);
    _objc_msgSend(obj_2, "setModalPresentationStyle:", 2);
    _objc_msgSend(self, "presentViewController:animated:completion:", obj_2, 1, 0);
    _objc_release(obj_2);
    _objc_release(obj);
    
    if (*___stack_chk_guard == x8)
        return;
    
    ___stack_chk_fail();
    /* no return */
}

void -[ACPanelController documentPicker:didPickDocumentsAtURLs:](struct ACPanelController* self, SEL sel, id documentPicker, id didPickDocumentsAtURLs)
{
    int64_t v13;
    int64_t var_90 = v13;
    int64_t v12;
    int64_t var_88 = v12;
    int64_t v11;
    int64_t var_80 = v11;
    int64_t v10;
    int64_t var_78 = v10;
    int64_t v9;
    int64_t var_70 = v9;
    int64_t v8;
    int64_t var_68 = v8;
    int64_t x8 = *___stack_chk_guard;
    id obj_1 = _objc_retain(didPickDocumentsAtURLs);
    
    if (_objc_msgSend(obj_1, "count"))
    {
        id obj_12 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_1, "firstObject"));
        id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSData, 
            "dataWithContentsOfURL:", obj_12));
        
        if (!obj_2)
            sub_410c94(&cfstr_[ERR]_Could_not_read_JSON_file);
        else
        {
            struct objc_class_t* clsRef_NSJSONSerialization_1 = clsRef_NSJSONSerialization;
            id obj = nullptr;
            id obj_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(
                clsRef_NSJSONSerialization_1, "JSONObjectWithData:options:error:", obj_2, 0, &obj));
            id obj_4 = _objc_retain(obj);
            id obj_13 = nullptr;
            bool z_1;
            
            z_1 = obj_3 ? !obj_4 : false;
            
            if (z_1)
            {
                id obj_14 = _objc_msgSend(clsRef_NSMutableArray, "new");
                struct __NSConstantString* const var_c8 = &cfstr_leftHand;
                struct __NSConstantString* const var_c0_1 = &cfstr_rightHand;
                struct __NSConstantString* const var_b8_1 = &cfstr_leftHip;
                struct __NSConstantString* const var_b0_1 = &cfstr_rightHip;
                struct __NSConstantString* const var_a8_1 = &cfstr_back;
                id obj_5 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
                    "arrayWithObjects:count:", &var_c8, 5));
                int128_t var_190;
                __builtin_memset(&var_190, 0, 0x18);
                int128_t var_170;
                __builtin_memset(&var_170, 0, 0x20);
                id obj_6 = _objc_retain(obj_5);
                void var_148;
                id i_2 = _objc_msgSend(obj_6, "countByEnumeratingWithState:objects:count:", 
                    &var_190, &var_148, 0x10);
                
                if (i_2)
                {
                    id i_1 = i_2;
                    int64_t* var_180;
                    int64_t x23_1 = *var_180;
                    id i;
                    
                    do
                    {
                        int64_t x22_1 = 0;
                        
                        do
                        {
                            if (*var_180 != x23_1)
                                _objc_enumerationMutation(obj_6);
                            
                            id obj_7 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_3, 
                                "objectForKeyedSubscript:", *(*(&var_190 + 8) + (x22_1 << 3))));
                            
                            if (_objc_msgSend(obj_7, "isKindOfClass:", 
                                    _objc_msgSend(clsRef_NSDictionary, "class")))
                                sub_42d204(obj_7, obj_14);
                            
                            _objc_release(obj_7);
                            x22_1 += 1;
                        } while (i_1 != x22_1);
                        
                        i = _objc_msgSend(obj_6, "countByEnumeratingWithState:objects:count:");
                        i_1 = i;
                    } while (i);
                }
                
                _objc_release(obj_6);
                _objc_release(obj_6);
                obj_13 = obj_14;
            }
            
            _objc_release(obj_3);
            _objc_release(obj_4);
            int64_t x0_27;
            
            if (obj_13)
                x0_27 = _objc_msgSend(obj_13, "count");
            
            if (!obj_13 || !x0_27)
                sub_410c94(&cfstr_[ERR]_No_items_found_in_JSON);
            else
            {
                struct objc_class_t* clsRef_NSString_1 = clsRef_NSString;
                int64_t var_220_1 = _objc_msgSend(obj_13, "count");
                id obj_8 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString_1, 
                    "stringWithFormat:", &cfstr_JSON_loaded:_%lu_items,_chunked_spawning...));
                sub_410c94(obj_8);
                _objc_release(obj_8);
                
                if (data_446ad2 != 1)
                {
                    int32_t v0_1;
                    int32_t v1_1;
                    int32_t v2_1;
                    v0_1 = sub_4113d8();
                    v8 = v0_1;
                    v9 = v1_1;
                    v10 = v2_1;
                }
                else
                {
                    v8 = *data_446ad4;
                    v9 = *(data_446ad4 + 4);
                    v10 = data_446adc;
                }
                
                int64_t x0_34 = _objc_msgSend(obj_13, "count");
                
                if (x0_34 >= 1)
                {
                    int64_t x21_2 = 0;
                    int64_t x26_2 = 0;
                    int64_t x27_1 = 5;
                    bool cond:0_1;
                    
                    do
                    {
                        int64_t x22_2;
                        
                        x22_2 = x0_34 < x27_1 ? x0_34 : x27_1;
                        
                        id obj_9 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_13, 
                            "subarrayWithRange:", x27_1 - 5));
                        dispatch_time_t when = _dispatch_time(0, 
                            vcvtd_s64_f64(x26_2 * 0.29999999999999999 * 1000000000.0));
                        _objc_retainAutorelease(__dispatch_main_q);
                        void* (* const var_1e0)[0x20] = __NSConcreteStackBlock;
                        int64_t var_1d8_1 = 0xc2000000;
                        int64_t (* var_1d0_1)(void* arg1) = sub_419800;
                        void* const var_1c8_1 = &data_43c380;
                        int32_t var_1a0_1 = v8;
                        int32_t var_19c_1 = v9;
                        int32_t var_198_1 = v10;
                        int64_t var_1b0_1 = x22_2;
                        int64_t var_1a8_1 = x0_34;
                        id obj_10 = _objc_retain(obj_13);
                        id obj_11 = _objc_retain(obj_9);
                        _dispatch_after(when, __dispatch_main_q, &var_1e0);
                        _objc_release(obj_10);
                        _objc_release(obj_9);
                        _objc_release(obj_11);
                        x26_2 += 1;
                        x21_2 -= 5;
                        cond:0_1 = x27_1 < x0_34;
                        x27_1 += 5;
                    } while (cond:0_1);
                }
            }
            
            _objc_release(obj_13);
        }
        
        _objc_release(obj_2);
        _objc_release(obj_12);
    }
    
    _objc_release(obj_1);
    
    if (*___stack_chk_guard == x8)
        return;
    
    ___stack_chk_fail();
    /* no return */
}

int64_t sub_419800(void* arg1)
{
    int64_t x8 = *___stack_chk_guard;
    int128_t var_120;
    __builtin_memset(&var_120, 0, 0x18);
    int128_t var_100;
    __builtin_memset(&var_100, 0, 0x20);
    id obj = _objc_retain(*(arg1 + 0x20));
    void var_d8;
    id i_2;
    int128_t v1;
    int128_t v2;
    i_2 = _objc_msgSend(obj, "countByEnumeratingWithState:objects:count:", &var_120, &var_d8, 0x10);
    
    if (i_2)
    {
        id i_1 = i_2;
        int64_t* var_110;
        int64_t x23_1 = *var_110;
        id i;
        
        do
        {
            int64_t x24_1 = 0;
            
            do
            {
                if (*var_110 != x23_1)
                    v1 = _objc_enumerationMutation(obj);
                
                v1 = *(arg1 + 0x44);
                v2 = *(arg1 + 0x48);
                v1 = sub_4114c8(*(*(&var_120 + 8) + (x24_1 << 3)), *(arg1 + 0x40));
                x24_1 += 1;
            } while (i_1 != x24_1);
            
            i = _objc_msgSend(obj, "countByEnumeratingWithState:objects:count:", &var_120, &var_d8, 
                0x10);
            i_1 = i;
        } while (i);
    }
    
    int64_t result = _objc_release(obj);
    
    if (*(arg1 + 0x30) >= *(arg1 + 0x38))
    {
        struct objc_class_t* clsRef_NSString_1 = clsRef_NSString;
        id var_130_1 = _objc_msgSend(*(arg1 + 0x28), "count");
        id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString_1, 
            "stringWithFormat:", &cfstr_Done_spawning_%lu_JSON_items));
        sub_410c94(obj_1);
        result = _objc_release(obj_1);
    }
    
    if (*___stack_chk_guard == x8)
        return result;
    
    ___stack_chk_fail();
    /* no return */
}

void -[ACPanelController buildExperimentContent](struct ACPanelController* self, SEL sel)
{
    int64_t x8 = *___stack_chk_guard;
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "experimentInner"));
    double v2 = _objc_msgSend(obj, "bounds");
    _objc_release(obj);
    id x0_3;
    int64_t x2;
    int128_t v1;
    int128_t v2_1;
    int128_t v3;
    x0_3 = _objc_alloc(clsRef_UILabel);
    double v9 = v2 + -28.0;
    v1 = 10.0;
    v3 = 26.0;
    v2_1 = v9;
    id obj_1 = _objc_msgSend(x0_3, "initWithFrame:", x2);
    int64_t x2_1;
    int128_t v0_1;
    x2_1 = _objc_msgSend(obj_1, "setText:", &cfstr_Experimenting_Lab);
    v0_1 = 16.0;
    id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
        "boldSystemFontOfSize:", x2_1));
    _objc_msgSend(obj_1, "setFont:", obj_2);
    int64_t x2_3;
    int64_t x3;
    int64_t x4;
    int64_t x5;
    int128_t v3_1;
    x2_3 = _objc_release(obj_2);
    v3_1 = 1.0;
    id obj_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:", x2_3, x3, x4, x5));
    _objc_msgSend(obj_1, "setTextColor:", obj_3);
    _objc_release(obj_3);
    id obj_4 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "experimentInner"));
    _objc_msgSend(obj_4, "addSubview:", obj_1);
    _objc_release(obj_4);
    id x0_16;
    int64_t x2_6;
    int128_t v0_2;
    int128_t v1_1;
    int128_t v2_2;
    int128_t v3_2;
    x0_16 = _objc_alloc(clsRef_UILabel);
    double v11 = 0x4045000000000000;
    v3_2 = 0x4042000000000000;
    v0_2 = 14.0;
    v1_1 = v11;
    v2_2 = v9;
    id obj_5 = _objc_msgSend(x0_16, "initWithFrame:", x2_6);
    int64_t x2_7;
    int128_t v0_3;
    x2_7 = _objc_msgSend(obj_5, "setText:", &cfstr_Experimental_features_-_use_at_your_own_risk!);
    v0_3 = 11.0;
    id obj_6 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
        "systemFontOfSize:", x2_7));
    _objc_msgSend(obj_5, "setFont:", obj_6);
    int64_t x2_9;
    int64_t x3_1;
    int64_t x4_1;
    int64_t x5_1;
    int128_t v1_2;
    int128_t v2_3;
    int128_t v3_3;
    x2_9 = _objc_release(obj_6);
    v1_2 = 0x3fe199999999999a;
    v3_3 = 1.0;
    v2_3 = 0x3fe6666666666666;
    id obj_7 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:", x2_9, x3_1, x4_1, x5_1));
    _objc_msgSend(obj_5, "setTextColor:", obj_7);
    _objc_release(obj_7);
    _objc_msgSend(obj_5, "setNumberOfLines:", 2);
    id obj_8 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "experimentInner"));
    _objc_msgSend(obj_8, "addSubview:", obj_5);
    _objc_release(obj_8);
    id obj_9;
    int64_t x2_12;
    int128_t v0_4;
    int128_t v1_3;
    int128_t v2_4;
    int128_t v3_4;
    obj_9 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:", 0));
    v1_3 = 0x4054000000000000;
    v0_4 = 14.0;
    v2_4 = v9;
    v3_4 = v11;
    int64_t x2_13;
    int64_t x3_2;
    int64_t x4_2;
    int64_t x5_2;
    int128_t v2_5;
    int128_t v3_5;
    x2_13 = _objc_msgSend(obj_9, "setFrame:", x2_12);
    v3_5 = 1.0;
    v2_5 = 0x3fb999999999999a;
    id obj_10 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:", x2_13, x3_2, x4_2, x5_2));
    _objc_msgSend(obj_9, "setBackgroundColor:", obj_10);
    _objc_release(obj_10);
    id obj_11;
    int64_t x2_15;
    int128_t v0_5;
    obj_11 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_9, "layer"));
    v0_5 = 12.0;
    _objc_msgSend(obj_11, "setCornerRadius:", x2_15);
    _objc_release(obj_11);
    int64_t x2_16;
    int64_t x3_3;
    int64_t x4_3;
    int64_t x5_3;
    int128_t v0_6;
    int128_t v1_4;
    int128_t v2_6;
    int128_t v3_6;
    x2_16 = _objc_msgSend(obj_9, "setTitle:forState:", &cfstr_??_Spawn_Bomb_(50_random_items), 0);
    v2_6 = 1.0;
    v3_6 = 1.0;
    v0_6 = 0x3feb333333333333;
    v1_4 = 0x3feccccccccccccd;
    id obj_12 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:", x2_16, x3_3, x4_3, x5_3));
    _objc_msgSend(obj_9, "setTitleColor:forState:", obj_12, 0);
    _objc_release(obj_12);
    int128_t v0_7;
    v0_7 = 13.0;
    id obj_13 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    id obj_14 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_9, "titleLabel"));
    _objc_msgSend(obj_14, "setFont:");
    _objc_release(obj_14);
    _objc_release(obj_13);
    _objc_msgSend(obj_9, "addTarget:action:forControlEvents:", self, "spawnBombTapped", 0x40);
    id obj_15 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "experimentInner"));
    _objc_msgSend(obj_15, "addSubview:");
    _objc_release(obj_15);
    id obj_16;
    int64_t x2_22;
    int128_t v0_8;
    int128_t v1_5;
    int128_t v2_7;
    int128_t v3_7;
    obj_16 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:"));
    v1_5 = 0x4060400000000000;
    v0_8 = 14.0;
    v2_7 = v9;
    v3_7 = v11;
    int64_t x2_23;
    int64_t x3_4;
    int64_t x4_4;
    int64_t x5_4;
    int128_t v0_9;
    int128_t v1_6;
    int128_t v2_8;
    int128_t v3_8;
    x2_23 = _objc_msgSend(obj_16, "setFrame:", x2_22);
    v3_8 = 1.0;
    v0_9 = 0x3fb999999999999a;
    v1_6 = 0x3fe3333333333333;
    v2_8 = 0x3fe6666666666666;
    id obj_17 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:", x2_23, x3_4, x4_4, x5_4));
    _objc_msgSend(obj_16, "setBackgroundColor:", obj_17);
    _objc_release(obj_17);
    id obj_18;
    int128_t v0_10;
    obj_18 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_16, "layer"));
    v0_10 = 12.0;
    _objc_msgSend(obj_18, "setCornerRadius:");
    _objc_release(obj_18);
    int64_t x2_25;
    int64_t x3_5;
    int64_t x4_5;
    int64_t x5_5;
    int128_t v0_11;
    int128_t v1_7;
    int128_t v2_9;
    int128_t v3_9;
    x2_25 =
        _objc_msgSend(obj_16, "setTitle:forState:", &cfstr_?_Spawn_Circle_(ring_around_player), 0);
    v2_9 = 1.0;
    v3_9 = 1.0;
    v0_11 = 0x3feb333333333333;
    v1_7 = 0x3feccccccccccccd;
    id obj_19 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:", x2_25, x3_5, x4_5, x5_5));
    _objc_msgSend(obj_16, "setTitleColor:forState:");
    _objc_release(obj_19);
    int128_t v0_12;
    v0_12 = 13.0;
    id obj_20 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    id obj_21 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_16, "titleLabel"));
    _objc_msgSend(obj_21, "setFont:");
    _objc_release(obj_21);
    _objc_release(obj_20);
    _objc_msgSend(obj_16, "addTarget:action:forControlEvents:");
    id obj_22 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "experimentInner"));
    _objc_msgSend(obj_22, "addSubview:");
    _objc_release(obj_22);
    id obj_23;
    int128_t v0_13;
    int128_t v1_8;
    int128_t v2_10;
    int128_t v3_10;
    obj_23 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:"));
    v1_8 = 0x4066800000000000;
    v0_13 = 14.0;
    v2_10 = v9;
    v3_10 = v11;
    int128_t v0_14;
    int128_t v1_9;
    int128_t v2_11;
    int128_t v3_11;
    v0_14 = _objc_msgSend(obj_23, "setFrame:");
    v3_11 = 1.0;
    v0_14 = 0x3fe3333333333333;
    v1_9 = 0x3fc999999999999a;
    v2_11 = 0x3fe6666666666666;
    id obj_24 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_23, "setBackgroundColor:");
    _objc_release(obj_24);
    id obj_25;
    int128_t v0_15;
    obj_25 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_23, "layer"));
    v0_15 = 12.0;
    _objc_msgSend(obj_25, "setCornerRadius:");
    _objc_release(obj_25);
    int128_t v0_16;
    int128_t v1_10;
    int128_t v2_12;
    int128_t v3_12;
    v0_16 = _objc_msgSend(obj_23, "setTitle:forState:");
    v2_12 = 1.0;
    v3_12 = 1.0;
    v0_16 = 0x3feb333333333333;
    v1_10 = 0x3feccccccccccccd;
    id obj_26 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_23, "setTitleColor:forState:");
    _objc_release(obj_26);
    int128_t v0_17;
    v0_17 = 13.0;
    id obj_27 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    id obj_28 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_23, "titleLabel"));
    _objc_msgSend(obj_28, "setFont:");
    _objc_release(obj_28);
    _objc_release(obj_27);
    _objc_msgSend(obj_23, "addTarget:action:forControlEvents:");
    id obj_29 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "experimentInner"));
    _objc_msgSend(obj_29, "addSubview:");
    _objc_release(obj_29);
    id obj_30;
    int128_t v0_18;
    int128_t v1_11;
    int128_t v2_13;
    int128_t v3_13;
    obj_30 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:"));
    v1_11 = 0x406cc00000000000;
    v0_18 = 14.0;
    v2_13 = v9;
    v3_13 = v11;
    int128_t v1_12;
    int128_t v2_14;
    int128_t v3_14;
    v1_12 = _objc_msgSend(obj_30, "setFrame:");
    v3_14 = 1.0;
    v1_12 = 0x3fd999999999999a;
    v2_14 = 0x3fc999999999999a;
    id obj_31 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_30, "setBackgroundColor:");
    _objc_release(obj_31);
    id obj_32;
    int128_t v0_19;
    obj_32 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_30, "layer"));
    v0_19 = 12.0;
    _objc_msgSend(obj_32, "setCornerRadius:");
    _objc_release(obj_32);
    int128_t v0_20;
    int128_t v1_13;
    int128_t v2_15;
    int128_t v3_15;
    v0_20 = _objc_msgSend(obj_30, "setTitle:forState:");
    v2_15 = 1.0;
    v3_15 = 1.0;
    v0_20 = 0x3feb333333333333;
    v1_13 = 0x3feccccccccccccd;
    id obj_33 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_30, "setTitleColor:forState:");
    _objc_release(obj_33);
    int128_t v0_21;
    v0_21 = 13.0;
    id obj_34 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    id obj_35 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_30, "titleLabel"));
    _objc_msgSend(obj_35, "setFont:");
    _objc_release(obj_35);
    _objc_release(obj_34);
    _objc_msgSend(obj_30, "addTarget:action:forControlEvents:");
    id obj_36 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "experimentInner"));
    _objc_msgSend(obj_36, "addSubview:");
    _objc_release(obj_36);
    id obj_37;
    int128_t v0_22;
    int128_t v1_14;
    int128_t v2_16;
    int128_t v3_16;
    obj_37 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:"));
    v1_14 = 0x4071800000000000;
    v0_22 = 14.0;
    v2_16 = v9;
    v3_16 = v11;
    int128_t v0_23;
    int128_t v1_15;
    int128_t v2_17;
    int128_t v3_17;
    v0_23 = _objc_msgSend(obj_37, "setFrame:");
    v1_15 = 0.5;
    v2_17 = 0.0;
    v3_17 = 1.0;
    v0_23 = 0x3feccccccccccccd;
    id obj_38 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_37, "setBackgroundColor:");
    _objc_release(obj_38);
    id obj_39;
    int128_t v0_24;
    obj_39 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_37, "layer"));
    v0_24 = 12.0;
    _objc_msgSend(obj_39, "setCornerRadius:");
    _objc_release(obj_39);
    int128_t v0_25;
    int128_t v1_16;
    int128_t v2_18;
    int128_t v3_18;
    v0_25 = _objc_msgSend(obj_37, "setTitle:forState:");
    v2_18 = 1.0;
    v3_18 = 1.0;
    v0_25 = 0x3feb333333333333;
    v1_16 = 0x3feccccccccccccd;
    id obj_40 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_37, "setTitleColor:forState:");
    _objc_release(obj_40);
    int128_t v0_26;
    v0_26 = 13.0;
    id obj_41 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    id obj_42 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_37, "titleLabel"));
    _objc_msgSend(obj_42, "setFont:");
    _objc_release(obj_42);
    _objc_release(obj_41);
    _objc_msgSend(obj_37, "addTarget:action:forControlEvents:");
    id obj_43 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "experimentInner"));
    _objc_msgSend(obj_43, "addSubview:");
    _objc_release(obj_43);
    id obj_44;
    int128_t v0_27;
    int128_t v1_17;
    int128_t v2_19;
    int128_t v3_19;
    obj_44 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:"));
    v1_17 = 0x4074a00000000000;
    v0_27 = 14.0;
    v2_19 = v9;
    v3_19 = v11;
    int128_t v0_28;
    int128_t v1_18;
    int128_t v2_20;
    int128_t v3_20;
    v0_28 = _objc_msgSend(obj_44, "setFrame:");
    v3_20 = 1.0;
    v0_28 = 0x3fe6666666666666;
    v1_18 = 0x3fb999999999999a;
    v2_20 = 0x3fb999999999999a;
    id obj_45 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_44, "setBackgroundColor:");
    _objc_release(obj_45);
    id obj_46;
    int128_t v0_29;
    obj_46 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_44, "layer"));
    v0_29 = 12.0;
    _objc_msgSend(obj_46, "setCornerRadius:");
    _objc_release(obj_46);
    int128_t v0_30;
    int128_t v1_19;
    int128_t v2_21;
    int128_t v3_21;
    v0_30 = _objc_msgSend(obj_44, "setTitle:forState:");
    v2_21 = 1.0;
    v3_21 = 1.0;
    v0_30 = 0x3feb333333333333;
    v1_19 = 0x3feccccccccccccd;
    id obj_47 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_44, "setTitleColor:forState:");
    _objc_release(obj_47);
    int128_t v0_31;
    v0_31 = 13.0;
    id obj_48 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    id obj_49 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_44, "titleLabel"));
    _objc_msgSend(obj_49, "setFont:");
    _objc_release(obj_49);
    _objc_release(obj_48);
    _objc_msgSend(obj_44, "addTarget:action:forControlEvents:");
    id obj_50 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "experimentInner"));
    _objc_msgSend(obj_50, "addSubview:");
    _objc_release(obj_50);
    id obj_51;
    int128_t v0_32;
    int128_t v1_20;
    int128_t v2_22;
    int128_t v3_22;
    obj_51 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:"));
    v1_20 = 0x4077c00000000000;
    v0_32 = 14.0;
    v2_22 = v9;
    v3_22 = v11;
    int128_t v0_33;
    int128_t v1_21;
    int128_t v2_23;
    int128_t v3_23;
    v0_33 = _objc_msgSend(obj_51, "setFrame:");
    v2_23 = 0.0;
    v3_23 = 1.0;
    v0_33 = 0x3feccccccccccccd;
    v1_21 = 0x3fe6666666666666;
    id obj_52 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_51, "setBackgroundColor:");
    _objc_release(obj_52);
    id obj_53;
    int128_t v0_34;
    obj_53 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_51, "layer"));
    v0_34 = 12.0;
    _objc_msgSend(obj_53, "setCornerRadius:");
    _objc_release(obj_53);
    int128_t v0_35;
    int128_t v1_22;
    int128_t v2_24;
    int128_t v3_24;
    v0_35 = _objc_msgSend(obj_51, "setTitle:forState:");
    v2_24 = 1.0;
    v3_24 = 1.0;
    v0_35 = 0x3feb333333333333;
    v1_22 = 0x3feccccccccccccd;
    id obj_54 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_51, "setTitleColor:forState:");
    _objc_release(obj_54);
    int128_t v0_36;
    v0_36 = 13.0;
    id obj_55 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    id obj_56 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_51, "titleLabel"));
    _objc_msgSend(obj_56, "setFont:");
    _objc_release(obj_56);
    _objc_release(obj_55);
    _objc_msgSend(obj_51, "addTarget:action:forControlEvents:");
    id obj_57 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "experimentInner"));
    _objc_msgSend(obj_57, "addSubview:");
    _objc_release(obj_57);
    id obj_58;
    int128_t v0_37;
    int128_t v1_23;
    int128_t v2_25;
    int128_t v3_25;
    obj_58 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:"));
    v1_23 = 0x407ae00000000000;
    v0_37 = 14.0;
    v2_25 = v9;
    v3_25 = v11;
    int128_t v0_38;
    int128_t v1_24;
    int128_t v2_26;
    int128_t v3_26;
    v0_38 = _objc_msgSend(obj_58, "setFrame:");
    v3_26 = 1.0;
    v0_38 = 0x3fc999999999999a;
    v1_24 = 0x3fd3333333333333;
    v2_26 = 0x3fe999999999999a;
    id obj_59 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_58, "setBackgroundColor:");
    _objc_release(obj_59);
    id obj_60;
    int128_t v0_39;
    obj_60 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_58, "layer"));
    v0_39 = 12.0;
    _objc_msgSend(obj_60, "setCornerRadius:");
    _objc_release(obj_60);
    int128_t v0_40;
    int128_t v1_25;
    int128_t v2_27;
    int128_t v3_27;
    v0_40 = _objc_msgSend(obj_58, "setTitle:forState:");
    v2_27 = 1.0;
    v3_27 = 1.0;
    v0_40 = 0x3feb333333333333;
    v1_25 = 0x3feccccccccccccd;
    id obj_61 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_58, "setTitleColor:forState:");
    _objc_release(obj_61);
    int128_t v0_41;
    v0_41 = 13.0;
    id obj_62 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    id obj_63 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_58, "titleLabel"));
    _objc_msgSend(obj_63, "setFont:");
    _objc_release(obj_63);
    _objc_release(obj_62);
    _objc_msgSend(obj_58, "addTarget:action:forControlEvents:");
    id obj_64 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "experimentInner"));
    _objc_msgSend(obj_64, "addSubview:");
    _objc_release(obj_64);
    id obj_65;
    int128_t v0_42;
    int128_t v1_26;
    int128_t v2_28;
    int128_t v3_28;
    obj_65 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:"));
    v1_26 = 0x407e000000000000;
    v0_42 = 14.0;
    v2_28 = v9;
    v3_28 = v11;
    int128_t v0_43;
    int128_t v1_27;
    int128_t v2_29;
    int128_t v3_29;
    v0_43 = _objc_msgSend(obj_65, "setFrame:");
    v3_29 = 1.0;
    v0_43 = 0x3feb333333333333;
    v1_27 = 0x3fe4cccccccccccd;
    v2_29 = 0x3fb999999999999a;
    id obj_66 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_65, "setBackgroundColor:");
    _objc_release(obj_66);
    id obj_67;
    int128_t v0_44;
    obj_67 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_65, "layer"));
    v0_44 = 12.0;
    _objc_msgSend(obj_67, "setCornerRadius:");
    _objc_release(obj_67);
    int128_t v0_45;
    int128_t v1_28;
    int128_t v2_30;
    int128_t v3_30;
    v0_45 = _objc_msgSend(obj_65, "setTitle:forState:");
    v2_30 = 1.0;
    v3_30 = 1.0;
    v0_45 = 0x3feb333333333333;
    v1_28 = 0x3feccccccccccccd;
    id obj_68 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_65, "setTitleColor:forState:");
    _objc_release(obj_68);
    int128_t v0_46;
    v0_46 = 13.0;
    id obj_69 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    id obj_70 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_65, "titleLabel"));
    _objc_msgSend(obj_70, "setFont:");
    _objc_release(obj_70);
    _objc_release(obj_69);
    _objc_msgSend(obj_65, "addTarget:action:forControlEvents:");
    id obj_71 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "experimentInner"));
    _objc_msgSend(obj_71, "addSubview:");
    _objc_release(obj_71);
    id obj_72;
    int128_t v0_47;
    int128_t v1_29;
    int128_t v2_31;
    int128_t v3_31;
    obj_72 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:"));
    v1_29 = 0x4080900000000000;
    v0_47 = 14.0;
    v2_31 = v9;
    v3_31 = v11;
    int128_t v0_48;
    int128_t v1_30;
    int128_t v2_32;
    int128_t v3_32;
    v0_48 = _objc_msgSend(obj_72, "setFrame:");
    v3_32 = 1.0;
    v0_48 = 0x3fb999999999999a;
    v1_30 = 0x3fe6666666666666;
    v2_32 = 0x3fe3333333333333;
    id obj_73 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_72, "setBackgroundColor:");
    _objc_release(obj_73);
    id obj_74;
    int128_t v0_49;
    obj_74 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_72, "layer"));
    v0_49 = 12.0;
    _objc_msgSend(obj_74, "setCornerRadius:");
    _objc_release(obj_74);
    _objc_msgSend(obj_72, "setTag:", 0x370);
    int128_t v0_50;
    int128_t v1_31;
    int128_t v2_33;
    int128_t v3_33;
    v0_50 = _objc_msgSend(obj_72, "setTitle:forState:");
    v2_33 = 1.0;
    v3_33 = 1.0;
    v0_50 = 0x3feb333333333333;
    v1_31 = 0x3feccccccccccccd;
    id obj_75 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_72, "setTitleColor:forState:");
    _objc_release(obj_75);
    int128_t v0_51;
    v0_51 = 13.0;
    id obj_76 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    id obj_77 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_72, "titleLabel"));
    _objc_msgSend(obj_77, "setFont:");
    _objc_release(obj_77);
    _objc_release(obj_76);
    _objc_msgSend(obj_72, "addTarget:action:forControlEvents:");
    id obj_78 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "experimentInner"));
    _objc_msgSend(obj_78, "addSubview:");
    _objc_release(obj_78);
    id obj_79;
    int128_t v0_52;
    int128_t v1_32;
    int128_t v2_34;
    int128_t v3_34;
    obj_79 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:"));
    v1_32 = 0x4082200000000000;
    v0_52 = 14.0;
    v2_34 = v9;
    v3_34 = v11;
    int128_t v0_53;
    int128_t v1_33;
    int128_t v2_35;
    int128_t v3_35;
    v0_53 = _objc_msgSend(obj_79, "setFrame:");
    v3_35 = 1.0;
    v0_53 = 0x3feccccccccccccd;
    v1_33 = 0x3fd3333333333333;
    v2_35 = 0x3fb999999999999a;
    id obj_80 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_79, "setBackgroundColor:");
    _objc_release(obj_80);
    id obj_81;
    int128_t v0_54;
    obj_81 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_79, "layer"));
    v0_54 = 12.0;
    _objc_msgSend(obj_81, "setCornerRadius:");
    _objc_release(obj_81);
    int128_t v0_55;
    int128_t v1_34;
    int128_t v2_36;
    int128_t v3_36;
    v0_55 = _objc_msgSend(obj_79, "setTitle:forState:");
    v2_36 = 1.0;
    v3_36 = 1.0;
    v0_55 = 0x3feb333333333333;
    v1_34 = 0x3feccccccccccccd;
    id obj_82 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_79, "setTitleColor:forState:");
    _objc_release(obj_82);
    int128_t v0_56;
    v0_56 = 13.0;
    id obj_83 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    id obj_84 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_79, "titleLabel"));
    _objc_msgSend(obj_84, "setFont:");
    _objc_release(obj_84);
    _objc_release(obj_83);
    _objc_msgSend(obj_79, "addTarget:action:forControlEvents:");
    id obj_85 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "experimentInner"));
    _objc_msgSend(obj_85, "addSubview:");
    _objc_release(obj_85);
    id obj_86;
    int128_t v0_57;
    int128_t v1_35;
    int128_t v2_37;
    int128_t v3_37;
    obj_86 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:"));
    v1_35 = 0x4083b00000000000;
    v0_57 = 14.0;
    v2_37 = v9;
    v3_37 = v11;
    int128_t v0_58;
    int128_t v1_36;
    int128_t v2_38;
    int128_t v3_38;
    v0_58 = _objc_msgSend(obj_86, "setFrame:");
    v1_36 = 0x3feae147ae147ae1;
    v0_58 = 1.0;
    v2_38 = 0.0;
    v3_38 = 1.0;
    id obj_87 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_86, "setBackgroundColor:");
    _objc_release(obj_87);
    id obj_88;
    int128_t v0_59;
    obj_88 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_86, "layer"));
    v0_59 = 12.0;
    _objc_msgSend(obj_88, "setCornerRadius:");
    _objc_release(obj_88);
    _objc_msgSend(obj_86, "setTitle:forState:");
    id obj_89 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, "blackColor"));
    _objc_msgSend(obj_86, "setTitleColor:forState:");
    _objc_release(obj_89);
    int128_t v0_60;
    v0_60 = 13.0;
    id obj_90 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    id obj_91 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_86, "titleLabel"));
    _objc_msgSend(obj_91, "setFont:");
    _objc_release(obj_91);
    _objc_release(obj_90);
    _objc_msgSend(obj_86, "addTarget:action:forControlEvents:");
    id obj_92 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "experimentInner"));
    _objc_msgSend(obj_92, "addSubview:");
    _objc_release(obj_92);
    id obj_93;
    int128_t v0_61;
    int128_t v1_37;
    int128_t v2_39;
    int128_t v3_39;
    obj_93 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:"));
    v1_37 = 0x4085400000000000;
    v0_61 = 14.0;
    v2_39 = v9;
    v3_39 = v11;
    int128_t v0_62;
    int128_t v1_38;
    int128_t v2_40;
    int128_t v3_40;
    v0_62 = _objc_msgSend(obj_93, "setFrame:");
    v3_40 = 1.0;
    v0_62 = 0x3fc3333333333333;
    v1_38 = 0x3fe4cccccccccccd;
    v2_40 = 0x3fc3333333333333;
    id obj_94 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_93, "setBackgroundColor:");
    _objc_release(obj_94);
    id obj_95;
    int128_t v0_63;
    obj_95 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_93, "layer"));
    v0_63 = 12.0;
    _objc_msgSend(obj_95, "setCornerRadius:");
    _objc_release(obj_95);
    int128_t v0_64;
    int128_t v1_39;
    int128_t v2_41;
    int128_t v3_41;
    v0_64 = _objc_msgSend(obj_93, "setTitle:forState:");
    v2_41 = 1.0;
    v3_41 = 1.0;
    v0_64 = 0x3feb333333333333;
    v1_39 = 0x3feccccccccccccd;
    id obj_96 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_93, "setTitleColor:forState:");
    _objc_release(obj_96);
    int128_t v0_65;
    v0_65 = 13.0;
    id obj_97 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    id obj_98 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_93, "titleLabel"));
    _objc_msgSend(obj_98, "setFont:");
    _objc_release(obj_98);
    _objc_release(obj_97);
    _objc_msgSend(obj_93, "addTarget:action:forControlEvents:");
    id obj_99 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "experimentInner"));
    _objc_msgSend(obj_99, "addSubview:");
    _objc_release(obj_99);
    id obj_100;
    int128_t v0_66;
    int128_t v1_40;
    int128_t v2_42;
    int128_t v3_42;
    obj_100 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:"));
    v1_40 = 0x4086d00000000000;
    v0_66 = 14.0;
    v2_42 = v9;
    v3_42 = v11;
    int128_t v0_67;
    int128_t v1_41;
    int128_t v2_43;
    int128_t v3_43;
    v0_67 = _objc_msgSend(obj_100, "setFrame:");
    v1_41 = 0.0;
    v2_43 = 0.0;
    v3_43 = 1.0;
    v0_67 = 0x3fe3333333333333;
    id obj_101 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_100, "setBackgroundColor:");
    _objc_release(obj_101);
    id obj_102;
    int128_t v0_68;
    obj_102 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_100, "layer"));
    v0_68 = 12.0;
    _objc_msgSend(obj_102, "setCornerRadius:");
    _objc_release(obj_102);
    int128_t v0_69;
    int128_t v1_42;
    int128_t v2_44;
    int128_t v3_44;
    v0_69 = _objc_msgSend(obj_100, "setTitle:forState:");
    v2_44 = 1.0;
    v3_44 = 1.0;
    v0_69 = 0x3feb333333333333;
    v1_42 = 0x3feccccccccccccd;
    id obj_103 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_100, "setTitleColor:forState:");
    _objc_release(obj_103);
    int128_t v0_70;
    v0_70 = 13.0;
    id obj_104 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    id obj_105 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_100, "titleLabel"));
    _objc_msgSend(obj_105, "setFont:");
    _objc_release(obj_105);
    _objc_release(obj_104);
    _objc_msgSend(obj_100, "addTarget:action:forControlEvents:");
    id obj_106 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "experimentInner"));
    _objc_msgSend(obj_106, "addSubview:");
    _objc_release(obj_106);
    id obj_107;
    int128_t v0_71;
    int128_t v1_43;
    int128_t v2_45;
    int128_t v3_45;
    obj_107 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:"));
    v1_43 = 0x4088600000000000;
    v0_71 = 14.0;
    v2_45 = v9;
    v3_45 = v11;
    int128_t v0_72;
    int128_t v1_44;
    int128_t v2_46;
    int128_t v3_46;
    v0_72 = _objc_msgSend(obj_107, "setFrame:");
    v1_44 = 0.25;
    v3_46 = 1.0;
    v0_72 = 0x3fd999999999999a;
    v2_46 = 0x3fb999999999999a;
    id obj_108 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_107, "setBackgroundColor:");
    _objc_release(obj_108);
    id obj_109;
    int128_t v0_73;
    obj_109 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_107, "layer"));
    v0_73 = 12.0;
    _objc_msgSend(obj_109, "setCornerRadius:");
    _objc_release(obj_109);
    int128_t v0_74;
    int128_t v1_45;
    int128_t v2_47;
    int128_t v3_47;
    v0_74 = _objc_msgSend(obj_107, "setTitle:forState:");
    v2_47 = 1.0;
    v3_47 = 1.0;
    v0_74 = 0x3feb333333333333;
    v1_45 = 0x3feccccccccccccd;
    id obj_110 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_107, "setTitleColor:forState:");
    _objc_release(obj_110);
    int128_t v0_75;
    v0_75 = 13.0;
    id obj_111 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    id obj_112 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_107, "titleLabel"));
    _objc_msgSend(obj_112, "setFont:");
    _objc_release(obj_112);
    _objc_release(obj_111);
    _objc_msgSend(obj_107, "addTarget:action:forControlEvents:");
    id obj_113 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "experimentInner"));
    _objc_msgSend(obj_113, "addSubview:");
    _objc_release(obj_113);
    id obj_114;
    int128_t v0_76;
    int128_t v1_46;
    int128_t v2_48;
    int128_t v3_48;
    obj_114 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:"));
    v1_46 = 0x4089f00000000000;
    v0_76 = 14.0;
    v2_48 = v9;
    v3_48 = v11;
    int128_t v0_77;
    int128_t v1_47;
    int128_t v2_49;
    int128_t v3_49;
    v0_77 = _objc_msgSend(obj_114, "setFrame:");
    v3_49 = 1.0;
    v0_77 = 0x3fc3333333333333;
    v1_47 = 0x3fd999999999999a;
    v2_49 = 0x3feccccccccccccd;
    id obj_115 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_114, "setBackgroundColor:");
    _objc_release(obj_115);
    id obj_116;
    int128_t v0_78;
    obj_116 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_114, "layer"));
    v0_78 = 12.0;
    _objc_msgSend(obj_116, "setCornerRadius:");
    _objc_release(obj_116);
    _objc_msgSend(obj_114, "setTag:");
    int128_t v0_79;
    int128_t v1_48;
    int128_t v2_50;
    int128_t v3_50;
    v0_79 = _objc_msgSend(obj_114, "setTitle:forState:");
    v2_50 = 1.0;
    v3_50 = 1.0;
    v0_79 = 0x3feb333333333333;
    v1_48 = 0x3feccccccccccccd;
    id obj_117 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_114, "setTitleColor:forState:");
    _objc_release(obj_117);
    int128_t v0_80;
    v0_80 = 13.0;
    id obj_118 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    id obj_119 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_114, "titleLabel"));
    _objc_msgSend(obj_119, "setFont:");
    _objc_release(obj_119);
    _objc_release(obj_118);
    _objc_msgSend(obj_114, "addTarget:action:forControlEvents:");
    id obj_120 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "experimentInner"));
    _objc_msgSend(obj_120, "addSubview:");
    _objc_release(obj_120);
    id obj_121;
    int128_t v0_81;
    int128_t v1_49;
    int128_t v2_51;
    int128_t v3_51;
    obj_121 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:"));
    v1_49 = 0x408b800000000000;
    v0_81 = 14.0;
    v2_51 = v9;
    v3_51 = v11;
    int128_t v0_82;
    int128_t v1_50;
    int128_t v2_52;
    int128_t v3_52;
    v0_82 = _objc_msgSend(obj_121, "setFrame:");
    v3_52 = 1.0;
    v0_82 = 0x3fe999999999999a;
    v1_50 = 0x3fe3333333333333;
    v2_52 = 0x3fb999999999999a;
    id obj_122 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_121, "setBackgroundColor:");
    _objc_release(obj_122);
    id obj_123;
    int128_t v0_83;
    obj_123 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_121, "layer"));
    v0_83 = 12.0;
    _objc_msgSend(obj_123, "setCornerRadius:");
    _objc_release(obj_123);
    _objc_msgSend(obj_121, "setTag:");
    int128_t v0_84;
    int128_t v1_51;
    int128_t v2_53;
    int128_t v3_53;
    v0_84 = _objc_msgSend(obj_121, "setTitle:forState:");
    v2_53 = 1.0;
    v3_53 = 1.0;
    v0_84 = 0x3feb333333333333;
    v1_51 = 0x3feccccccccccccd;
    id obj_124 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_121, "setTitleColor:forState:");
    _objc_release(obj_124);
    int128_t v0_85;
    v0_85 = 13.0;
    id obj_125 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    id obj_126 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_121, "titleLabel"));
    _objc_msgSend(obj_126, "setFont:");
    _objc_release(obj_126);
    _objc_release(obj_125);
    _objc_msgSend(obj_121, "addTarget:action:forControlEvents:");
    id obj_127 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "experimentInner"));
    _objc_msgSend(obj_127, "addSubview:");
    _objc_release(obj_127);
    id x0_441;
    int128_t v0_86;
    int128_t v1_52;
    int128_t v2_54;
    int128_t v3_54;
    x0_441 = _objc_alloc(clsRef_UILabel);
    v1_52 = 0x408d100000000000;
    v0_86 = 14.0;
    v3_54 = 22.0;
    v2_54 = v9;
    id obj_128 = _objc_msgSend(x0_441, "initWithFrame:");
    _objc_msgSend(obj_128, "setText:");
    int128_t v0_87;
    v0_87 = 14.0;
    id obj_129 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, "boldSystemFontOfSize:"));
    _objc_msgSend(obj_128, "setFont:");
    int128_t v0_88;
    int128_t v1_53;
    int128_t v2_55;
    int128_t v3_55;
    v0_88 = _objc_release(obj_129);
    v3_55 = 1.0;
    v0_88 = 0x3fb999999999999a;
    v1_53 = 0x3fe999999999999a;
    v2_55 = 0x3fee666666666666;
    id obj_130 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_128, "setTextColor:");
    _objc_release(obj_130);
    id obj_131 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "experimentInner"));
    _objc_msgSend(obj_131, "addSubview:");
    _objc_release(obj_131);
    struct __NSConstantString_UTF16* const var_1a0 = &cfstr_??_Crossbow_Rain;
    struct __NSConstantString_UTF16* const var_198 = &cfstr_??_RPG_Barrage;
    struct __NSConstantString_UTF16* const var_190 = &cfstr_?_Snowball_Fight;
    struct __NSConstantString_UTF16* const var_188 = &cfstr_??_Weapon_Cache;
    struct __NSConstantString_UTF16* const var_180 = &cfstr_??_Loot_Explosion;
    struct __NSConstantString_UTF16* const var_178 = &cfstr_??_Diamond_Shower;
    struct __NSConstantString_UTF16* const var_170 = &cfstr_??_Fire_Ring;
    struct __NSConstantString_UTF16* const var_168 = &cfstr_??_Tsunami_Wall;
    struct __NSConstantString_UTF16* const var_160 = &cfstr_??_Jetpack_Rain;
    struct __NSConstantString_UTF16* const var_158 = &cfstr_??_Ball_Pit;
    struct __NSConstantString_UTF16* const var_150 = &cfstr_??_Magnet_Pull;
    struct __NSConstantString_UTF16* const var_148 = &cfstr_??_Boombox_Party;
    struct __NSConstantString_UTF16* const var_140 = &cfstr_??_Potion_Storm;
    struct __NSConstantString_UTF16* const var_138 = &cfstr_??_Arrow_Rain;
    struct __NSConstantString_UTF16* const var_130 = &cfstr_??_Sword_Circle;
    struct __NSConstantString_UTF16* const var_128 = &cfstr_??_Money_Rain;
    struct __NSConstantString_UTF16* const var_120 = &cfstr_??_Food_Feast;
    struct __NSConstantString_UTF16* const var_118 = &cfstr_??_Shield_Wall;
    struct __NSConstantString_UTF16* const var_110 = &cfstr_??_Fishing_Frenzy;
    struct __NSConstantString_UTF16* const var_108 = &cfstr_??_Trophy_Shower;
    struct __NSConstantString_UTF16* const var_100 = &cfstr_??_Mine_Field;
    struct __NSConstantString_UTF16* const var_f8 = &cfstr_??_Party_Popper;
    struct __NSConstantString_UTF16* const var_f0 = &cfstr_??_UFO_Beam;
    struct __NSConstantString_UTF16* const var_e8 = &cfstr_??_Mask_Drop;
    struct __NSConstantString_UTF16* const var_e0 = &cfstr_??_Brick_House;
    struct __NSConstantString_UTF16* const var_d8 = &cfstr_??_Game_Drop;
    struct __NSConstantString_UTF16* const var_d0 = &cfstr_??_Ice_Fortress;
    struct __NSConstantString_UTF16* const var_c8 = &cfstr_??_Rainbow_Bridge;
    struct __NSConstantString_UTF16* const var_c0 = &cfstr_??_Volcano_Eruption;
    struct __NSConstantString_UTF16* const var_b8 = &cfstr_??_Crown_Rain;
    id obj_132;
    int64_t x2_142;
    int128_t v0_89;
    obj_132 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &var_1a0, 0x1e));
    v0_89 = 0x3fe6666666666666;
    id obj_133;
    int64_t x2_143;
    int128_t v0_90;
    obj_133 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_142));
    id obj_380 = obj_133;
    v0_90 = 0x3fc999999999999a;
    id obj_134;
    int64_t x2_144;
    int128_t v0_91;
    obj_134 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_143));
    id obj_381 = obj_134;
    v0_91 = 0x3fc999999999999a;
    id obj_135 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_144));
    id obj_382 = obj_135;
    id obj_136;
    int64_t x2_146;
    int128_t v0_92;
    obj_136 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &obj_380, 3));
    id obj_383 = obj_136;
    v0_92 = 0x3fe999999999999a;
    id obj_137;
    int64_t x2_147;
    int128_t v0_93;
    obj_137 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_146));
    id obj_377 = obj_137;
    v0_93 = 0x3fd3333333333333;
    id obj_138;
    int64_t x2_148;
    int128_t v0_94;
    obj_138 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_147));
    id obj_378 = obj_138;
    v0_94 = 0.0;
    id obj_139 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_148));
    id obj_379 = obj_139;
    id obj_140;
    int64_t x2_150;
    int128_t v0_95;
    obj_140 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &obj_377, 3));
    id obj_384 = obj_140;
    v0_95 = 0x3fe3333333333333;
    id obj_141;
    int64_t x2_151;
    int128_t v0_96;
    obj_141 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_150));
    id obj_374 = obj_141;
    v0_96 = 0x3fe999999999999a;
    id obj_142;
    int64_t x2_152;
    int128_t v0_97;
    obj_142 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_151));
    id obj_375 = obj_142;
    v0_97 = 0x3feccccccccccccd;
    id obj_143 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_152));
    id obj_376 = obj_143;
    id obj_144;
    int64_t x2_154;
    int128_t v0_98;
    obj_144 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &obj_374, 3));
    id obj_385 = obj_144;
    v0_98 = 0x3fd3333333333333;
    id obj_145;
    int64_t x2_155;
    int128_t v0_99;
    obj_145 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_154));
    id obj_371 = obj_145;
    v0_99 = 0x3fd3333333333333;
    id obj_146;
    int64_t x2_156;
    int128_t v0_100;
    obj_146 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_155));
    id obj_372 = obj_146;
    v0_100 = 0x3fd3333333333333;
    id obj_147 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_156));
    id obj_373 = obj_147;
    id obj_148;
    int64_t x2_158;
    int128_t v0_101;
    obj_148 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &obj_371, 3));
    id obj_386 = obj_148;
    v0_101 = 0x3feccccccccccccd;
    id obj_149;
    int64_t x2_159;
    int128_t v0_102;
    obj_149 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_158));
    id obj_368 = obj_149;
    v0_102 = 0x3fe6666666666666;
    id obj_150;
    int64_t x2_160;
    int128_t v0_103;
    obj_150 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_159));
    id obj_369 = obj_150;
    v0_103 = 0.0;
    id obj_151 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_160));
    id obj_370 = obj_151;
    id obj_152;
    int64_t x2_162;
    int128_t v0_104;
    obj_152 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &obj_368, 3));
    id obj_387 = obj_152;
    v0_104 = 0x3fd999999999999a;
    id obj_153;
    int64_t x2_163;
    int128_t v0_105;
    obj_153 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_162));
    id obj_365 = obj_153;
    v0_105 = 0x3fe6666666666666;
    id obj_154;
    int64_t x2_164;
    int128_t v0_106;
    obj_154 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_163));
    id obj_366 = obj_154;
    v0_106 = 0x3feccccccccccccd;
    id obj_155 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_164));
    id obj_367 = obj_155;
    id obj_156;
    int64_t x2_166;
    int128_t v0_107;
    obj_156 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &obj_365, 3));
    id obj_388 = obj_156;
    v0_107 = 0x3feccccccccccccd;
    id obj_157;
    int64_t x2_167;
    int128_t v0_108;
    obj_157 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_166));
    id obj_362 = obj_157;
    v0_108 = 0x3fd3333333333333;
    id obj_158;
    int64_t x2_168;
    int128_t v0_109;
    obj_158 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_167));
    id obj_363 = obj_158;
    v0_109 = 0.0;
    id obj_159 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_168));
    id obj_364 = obj_159;
    id obj_160;
    int64_t x2_170;
    int128_t v0_110;
    obj_160 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &obj_362, 3));
    id obj_389 = obj_160;
    v0_110 = 0x3fb999999999999a;
    id obj_161;
    int64_t x2_171;
    int128_t v0_111;
    obj_161 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_170));
    id obj_359 = obj_161;
    v0_111 = 0x3fd999999999999a;
    id obj_162;
    int64_t x2_172;
    int128_t v0_112;
    obj_162 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_171));
    id obj_360 = obj_162;
    v0_112 = 0x3fe999999999999a;
    id obj_163 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_172));
    id obj_361 = obj_163;
    id obj_164;
    int64_t x2_174;
    int128_t v0_113;
    obj_164 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &obj_359, 3));
    id obj_390 = obj_164;
    v0_113 = 0x3fd3333333333333;
    id obj_165;
    int64_t x2_175;
    int128_t v0_114;
    obj_165 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_174));
    id obj_356 = obj_165;
    v0_114 = 0x3fe3333333333333;
    id obj_166;
    int64_t x2_176;
    int128_t v0_115;
    obj_166 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_175));
    id obj_357 = obj_166;
    v0_115 = 0x3fd3333333333333;
    id obj_167 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_176));
    id obj_358 = obj_167;
    id obj_168;
    int64_t x2_178;
    int128_t v0_116;
    obj_168 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &obj_356, 3));
    id obj_391 = obj_168;
    v0_116 = 0x3feccccccccccccd;
    id obj_169;
    int64_t x2_179;
    int128_t v0_117;
    obj_169 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_178));
    id obj_353 = obj_169;
    v0_117 = 0.5;
    id obj_170;
    int64_t x2_180;
    int128_t v0_118;
    obj_170 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_179));
    id obj_354 = obj_170;
    v0_118 = 0x3fc999999999999a;
    id obj_171 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_180));
    id obj_355 = obj_171;
    id obj_172;
    int64_t x2_182;
    int128_t v0_119;
    obj_172 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &obj_353, 3));
    id obj_392 = obj_172;
    v0_119 = 0.5;
    id obj_173;
    int64_t x2_183;
    int128_t v0_120;
    obj_173 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_182));
    id obj_350 = obj_173;
    v0_120 = 0.5;
    id obj_174;
    int64_t x2_184;
    int128_t v0_121;
    obj_174 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_183));
    id obj_351 = obj_174;
    v0_121 = 0.5;
    id obj_175 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_184));
    id obj_352 = obj_175;
    id obj_176;
    int64_t x2_186;
    int128_t v0_122;
    obj_176 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &obj_350, 3));
    id obj_393 = obj_176;
    v0_122 = 0x3fe999999999999a;
    id obj_177;
    int64_t x2_187;
    int128_t v0_123;
    obj_177 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_186));
    id obj_347 = obj_177;
    v0_123 = 0x3fc999999999999a;
    id obj_178;
    int64_t x2_188;
    int128_t v0_124;
    obj_178 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_187));
    id obj_348 = obj_178;
    v0_124 = 0x3fe999999999999a;
    id obj_179 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_188));
    id obj_349 = obj_179;
    id obj_180;
    int64_t x2_190;
    int128_t v0_125;
    obj_180 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &obj_347, 3));
    id obj_394 = obj_180;
    v0_125 = 0x3fc999999999999a;
    id obj_181;
    int64_t x2_191;
    int128_t v0_126;
    obj_181 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_190));
    id obj_344 = obj_181;
    v0_126 = 0x3fe999999999999a;
    id obj_182;
    int64_t x2_192;
    int128_t v0_127;
    obj_182 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_191));
    id obj_345 = obj_182;
    v0_127 = 0x3fd3333333333333;
    id obj_183 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_192));
    id obj_346 = obj_183;
    id obj_184;
    int64_t x2_194;
    int128_t v0_128;
    obj_184 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &obj_344, 3));
    id obj_395 = obj_184;
    v0_128 = 0x3fe3333333333333;
    id obj_185;
    int64_t x2_195;
    int128_t v0_129;
    obj_185 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_194));
    id obj_341 = obj_185;
    v0_129 = 0x3fd999999999999a;
    id obj_186;
    int64_t x2_196;
    int128_t v0_130;
    obj_186 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_195));
    id obj_342 = obj_186;
    v0_130 = 0x3fc999999999999a;
    id obj_187 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_196));
    id obj_343 = obj_187;
    id obj_188;
    int64_t x2_198;
    int128_t v0_131;
    obj_188 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &obj_341, 3));
    id obj_396 = obj_188;
    v0_131 = 0x3fe6666666666666;
    id obj_189;
    int64_t x2_199;
    int128_t v0_132;
    obj_189 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_198));
    id obj_338 = obj_189;
    v0_132 = 0x3fb999999999999a;
    id obj_190;
    int64_t x2_200;
    int128_t v0_133;
    obj_190 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_199));
    id obj_339 = obj_190;
    v0_133 = 0x3fd3333333333333;
    id obj_191 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_200));
    id obj_340 = obj_191;
    id obj_192;
    int64_t x2_202;
    int128_t v0_134;
    obj_192 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &obj_338, 3));
    id obj_397 = obj_192;
    v0_134 = 0x3fc999999999999a;
    id obj_193;
    int64_t x2_203;
    int128_t v0_135;
    obj_193 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_202));
    id obj_335 = obj_193;
    v0_135 = 0x3fe6666666666666;
    id obj_194;
    int64_t x2_204;
    int128_t v0_136;
    obj_194 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_203));
    id obj_336 = obj_194;
    v0_136 = 0x3fc999999999999a;
    id obj_195 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_204));
    id obj_337 = obj_195;
    id obj_196;
    int64_t x2_206;
    int128_t v0_137;
    obj_196 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &obj_335, 3));
    id obj_398 = obj_196;
    v0_137 = 0x3feccccccccccccd;
    id obj_197;
    int64_t x2_207;
    int128_t v0_138;
    obj_197 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_206));
    id obj_332 = obj_197;
    v0_138 = 0x3fe3333333333333;
    id obj_198;
    int64_t x2_208;
    int128_t v0_139;
    obj_198 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_207));
    id obj_333 = obj_198;
    v0_139 = 0x3fc999999999999a;
    id obj_199 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_208));
    id obj_334 = obj_199;
    id obj_200;
    int64_t x2_210;
    int128_t v0_140;
    obj_200 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &obj_332, 3));
    id obj_399 = obj_200;
    v0_140 = 0x3fd999999999999a;
    id obj_201;
    int64_t x2_211;
    int128_t v0_141;
    obj_201 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_210));
    id obj_329 = obj_201;
    v0_141 = 0x3fd999999999999a;
    id obj_202;
    int64_t x2_212;
    int128_t v0_142;
    obj_202 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_211));
    id obj_330 = obj_202;
    v0_142 = 0x3fe3333333333333;
    id obj_203 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_212));
    id obj_331 = obj_203;
    id obj_204;
    int64_t x2_214;
    int128_t v0_143;
    obj_204 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &obj_329, 3));
    id obj_400 = obj_204;
    v0_143 = 0x3fb999999999999a;
    id obj_205;
    int64_t x2_215;
    int128_t v0_144;
    obj_205 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_214));
    id obj_326 = obj_205;
    v0_144 = 0.5;
    id obj_206;
    int64_t x2_216;
    int128_t v0_145;
    obj_206 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_215));
    id obj_327 = obj_206;
    v0_145 = 0x3fe999999999999a;
    id obj_207 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_216));
    id obj_328 = obj_207;
    id obj_208;
    int64_t x2_218;
    int128_t v0_146;
    obj_208 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &obj_326, 3));
    id obj_401 = obj_208;
    v0_146 = 0x3feccccccccccccd;
    id obj_209;
    int64_t x2_219;
    int128_t v0_147;
    obj_209 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_218));
    id obj_323 = obj_209;
    v0_147 = 0x3fe999999999999a;
    id obj_210;
    int64_t x2_220;
    int128_t v0_148;
    obj_210 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_219));
    id obj_324 = obj_210;
    v0_148 = 0.0;
    id obj_211 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_220));
    id obj_325 = obj_211;
    id obj_212;
    int64_t x2_222;
    int128_t v0_149;
    obj_212 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &obj_323, 3));
    id obj_402 = obj_212;
    v0_149 = 0.5;
    id obj_213;
    int64_t x2_223;
    int128_t v0_150;
    obj_213 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_222));
    id obj_320 = obj_213;
    v0_150 = 0x3fb999999999999a;
    id obj_214;
    int64_t x2_224;
    int128_t v0_151;
    obj_214 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_223));
    id obj_321 = obj_214;
    v0_151 = 0x3fb999999999999a;
    id obj_215 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_224));
    id obj_322 = obj_215;
    id obj_216;
    int64_t x2_226;
    int128_t v0_152;
    obj_216 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &obj_320, 3));
    id obj_403 = obj_216;
    v0_152 = 0x3feccccccccccccd;
    id obj_217;
    int64_t x2_227;
    int128_t v0_153;
    obj_217 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_226));
    id obj_317 = obj_217;
    v0_153 = 0x3fd999999999999a;
    id obj_218;
    int64_t x2_228;
    int128_t v0_154;
    obj_218 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_227));
    id obj_318 = obj_218;
    v0_154 = 0x3fe6666666666666;
    id obj_219 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_228));
    id obj_319 = obj_219;
    id obj_220;
    int64_t x2_230;
    int128_t v0_155;
    obj_220 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &obj_317, 3));
    id obj_404 = obj_220;
    v0_155 = 0x3fd3333333333333;
    id obj_221;
    int64_t x2_231;
    int128_t v0_156;
    obj_221 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_230));
    id obj_314 = obj_221;
    v0_156 = 0x3fe999999999999a;
    id obj_222;
    int64_t x2_232;
    int128_t v0_157;
    obj_222 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_231));
    id obj_315 = obj_222;
    v0_157 = 0x3fd3333333333333;
    id obj_223 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_232));
    id obj_316 = obj_223;
    id obj_224;
    int64_t x2_234;
    int128_t v0_158;
    obj_224 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &obj_314, 3));
    id obj_405 = obj_224;
    v0_158 = 0x3fe3333333333333;
    id obj_225;
    int64_t x2_235;
    int128_t v0_159;
    obj_225 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_234));
    id obj_311 = obj_225;
    v0_159 = 0x3fd3333333333333;
    id obj_226;
    int64_t x2_236;
    int128_t v0_160;
    obj_226 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_235));
    id obj_312 = obj_226;
    v0_160 = 0x3fe3333333333333;
    id obj_227 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_236));
    id obj_313 = obj_227;
    id obj_228;
    int64_t x2_238;
    int128_t v0_161;
    obj_228 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &obj_311, 3));
    id obj_406 = obj_228;
    v0_161 = 0x3fe3333333333333;
    id obj_229;
    int64_t x2_239;
    int128_t v0_162;
    obj_229 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_238));
    id obj_308 = obj_229;
    v0_162 = 0x3fd3333333333333;
    id obj_230;
    int64_t x2_240;
    int128_t v0_163;
    obj_230 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_239));
    id obj_309 = obj_230;
    v0_163 = 0x3fb999999999999a;
    id obj_231 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_240));
    id obj_310 = obj_231;
    id obj_232;
    int64_t x2_242;
    int128_t v0_164;
    obj_232 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &obj_308, 3));
    id obj_407 = obj_232;
    v0_164 = 0x3fc999999999999a;
    id obj_233;
    int64_t x2_243;
    int128_t v0_165;
    obj_233 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_242));
    id obj_305 = obj_233;
    v0_165 = 0x3fc999999999999a;
    id obj_234;
    int64_t x2_244;
    int128_t v0_166;
    obj_234 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_243));
    id obj_306 = obj_234;
    v0_166 = 0x3fe6666666666666;
    id obj_235 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_244));
    id obj_307 = obj_235;
    id obj_236;
    int64_t x2_246;
    int128_t v0_167;
    obj_236 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &obj_305, 3));
    id obj_408 = obj_236;
    v0_167 = 0.5;
    id obj_237;
    int64_t x2_247;
    int128_t v0_168;
    obj_237 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_246));
    id obj_302 = obj_237;
    v0_168 = 0x3fe999999999999a;
    id obj_238;
    int64_t x2_248;
    int128_t v0_169;
    obj_238 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_247));
    id obj_303 = obj_238;
    v0_169 = 0x3feccccccccccccd;
    id obj_239 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_248));
    id obj_304 = obj_239;
    id obj_240;
    int64_t x2_250;
    int128_t v0_170;
    obj_240 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &obj_302, 3));
    id obj_409 = obj_240;
    v0_170 = 0x3feccccccccccccd;
    id obj_241;
    int64_t x2_251;
    int128_t v0_171;
    obj_241 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_250));
    id obj_299 = obj_241;
    v0_171 = 0x3fd3333333333333;
    id obj_242;
    int64_t x2_252;
    int128_t v0_172;
    obj_242 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_251));
    id obj_300 = obj_242;
    v0_172 = 0x3fd3333333333333;
    id obj_243 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_252));
    id obj_301 = obj_243;
    id obj_244;
    int64_t x2_254;
    int128_t v0_173;
    obj_244 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &obj_299, 3));
    id obj_410 = obj_244;
    v0_173 = 0x3fe999999999999a;
    id obj_245;
    int64_t x2_255;
    int128_t v0_174;
    obj_245 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_254));
    id obj_296 = obj_245;
    v0_174 = 0x3fc999999999999a;
    id obj_246;
    int64_t x2_256;
    int128_t v0_175;
    obj_246 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_255));
    id obj_297 = obj_246;
    v0_175 = 0.0;
    id obj_247 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_256));
    id obj_298 = obj_247;
    id obj_248;
    int64_t x2_258;
    int128_t v0_176;
    obj_248 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &obj_296, 3));
    id obj_411 = obj_248;
    v0_176 = 0x3feccccccccccccd;
    id obj_249;
    int64_t x2_259;
    int128_t v0_177;
    obj_249 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_258));
    id obj_293 = obj_249;
    v0_177 = 0x3fe999999999999a;
    id obj_250;
    int64_t x2_260;
    int128_t v0_178;
    obj_250 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_259));
    id obj_294 = obj_250;
    v0_178 = 0x3fc999999999999a;
    id obj_251 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSNumber, 
        "numberWithDouble:", x2_260));
    id obj_295 = obj_251;
    id obj_252 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &obj_293, 3));
    id obj_412 = obj_252;
    id obj_253 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &obj_383, 0x1e));
    _objc_release(obj_252);
    _objc_release(obj_251);
    _objc_release(obj_250);
    _objc_release(obj_249);
    _objc_release(obj_248);
    _objc_release(obj_247);
    _objc_release(obj_246);
    _objc_release(obj_245);
    _objc_release(obj_244);
    _objc_release(obj_243);
    _objc_release(obj_242);
    _objc_release(obj_241);
    _objc_release(obj_240);
    _objc_release(obj_239);
    _objc_release(obj_238);
    _objc_release(obj_237);
    _objc_release(obj_236);
    _objc_release(obj_235);
    _objc_release(obj_234);
    _objc_release(obj_233);
    _objc_release(obj_232);
    _objc_release(obj_231);
    _objc_release(obj_230);
    _objc_release(obj_229);
    _objc_release(obj_228);
    _objc_release(obj_227);
    _objc_release(obj_226);
    _objc_release(obj_225);
    _objc_release(obj_224);
    _objc_release(obj_223);
    _objc_release(obj_222);
    _objc_release(obj_221);
    _objc_release(obj_220);
    _objc_release(obj_219);
    _objc_release(obj_218);
    _objc_release(obj_217);
    _objc_release(obj_216);
    _objc_release(obj_215);
    _objc_release(obj_214);
    _objc_release(obj_213);
    _objc_release(obj_212);
    _objc_release(obj_211);
    _objc_release(obj_210);
    _objc_release(obj_209);
    _objc_release(obj_208);
    _objc_release(obj_207);
    _objc_release(obj_206);
    _objc_release(obj_205);
    _objc_release(obj_204);
    _objc_release(obj_203);
    _objc_release(obj_202);
    _objc_release(obj_201);
    _objc_release(obj_200);
    _objc_release(obj_199);
    _objc_release(obj_198);
    _objc_release(obj_197);
    _objc_release(obj_196);
    _objc_release(obj_195);
    _objc_release(obj_194);
    _objc_release(obj_193);
    _objc_release(obj_192);
    _objc_release(obj_191);
    _objc_release(obj_190);
    _objc_release(obj_189);
    _objc_release(obj_188);
    _objc_release(obj_187);
    _objc_release(obj_186);
    _objc_release(obj_185);
    _objc_release(obj_184);
    _objc_release(obj_183);
    _objc_release(obj_182);
    _objc_release(obj_181);
    _objc_release(obj_180);
    _objc_release(obj_179);
    _objc_release(obj_178);
    _objc_release(obj_177);
    _objc_release(obj_176);
    _objc_release(obj_175);
    _objc_release(obj_174);
    _objc_release(obj_173);
    _objc_release(obj_172);
    _objc_release(obj_171);
    _objc_release(obj_170);
    _objc_release(obj_169);
    _objc_release(obj_168);
    _objc_release(obj_167);
    _objc_release(obj_166);
    _objc_release(obj_165);
    _objc_release(obj_164);
    _objc_release(obj_163);
    _objc_release(obj_162);
    _objc_release(obj_161);
    _objc_release(obj_160);
    _objc_release(obj_159);
    _objc_release(obj_158);
    _objc_release(obj_157);
    _objc_release(obj_156);
    _objc_release(obj_155);
    _objc_release(obj_154);
    _objc_release(obj_153);
    _objc_release(obj_152);
    _objc_release(obj_151);
    _objc_release(obj_150);
    _objc_release(obj_149);
    _objc_release(obj_148);
    _objc_release(obj_147);
    _objc_release(obj_146);
    _objc_release(obj_145);
    _objc_release(obj_144);
    _objc_release(obj_143);
    _objc_release(obj_142);
    _objc_release(obj_141);
    _objc_release(obj_140);
    _objc_release(obj_139);
    _objc_release(obj_138);
    _objc_release(obj_137);
    _objc_release(obj_136);
    _objc_release(obj_135);
    _objc_release(obj_134);
    _objc_release(obj_133);
    int64_t i = 0;
    double v8 = 956.0;
    
    do
    {
        id obj_254 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_253, 
            "objectAtIndexedSubscript:", i));
        id obj_255;
        int128_t v0_179;
        int128_t v1_54;
        int128_t v2_56;
        int128_t v3_56;
        obj_255 =
            _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:"));
        v3_56 = 0x4043000000000000;
        v0_179 = 14.0;
        v1_54 = v8;
        v2_56 = v9;
        _objc_msgSend(obj_255, "setFrame:");
        struct objc_class_t* clsRef_UIColor_1 = clsRef_UIColor;
        id obj_256 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_254, 
            "objectAtIndexedSubscript:", 0));
        _objc_msgSend(obj_256, "floatValue");
        id obj_257 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_254, 
            "objectAtIndexedSubscript:", 1));
        v11 = _objc_msgSend(obj_257, "floatValue");
        id obj_258 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_254, 
            "objectAtIndexedSubscript:", 2));
        int32_t v0_182;
        int128_t v1_55;
        int128_t v2_57;
        int128_t v3_57;
        v0_182 = _objc_msgSend(obj_258, "floatValue");
        v2_57 = v0_182;
        v3_57 = 1.0;
        v1_55 = v11;
        id obj_259 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor_1, 
            "colorWithRed:green:blue:alpha:"));
        _objc_msgSend(obj_255, "setBackgroundColor:");
        _objc_release(obj_259);
        _objc_release(obj_258);
        _objc_release(obj_257);
        _objc_release(obj_256);
        id obj_260;
        int128_t v0_183;
        obj_260 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_255, "layer"));
        v0_183 = 10.0;
        _objc_msgSend(obj_260, "setCornerRadius:");
        _objc_release(obj_260);
        id obj_261 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_132, 
            "objectAtIndexedSubscript:", i));
        _objc_msgSend(obj_255, "setTitle:forState:");
        int128_t v0_184;
        int128_t v1_56;
        int128_t v2_58;
        int128_t v3_58;
        v0_184 = _objc_release(obj_261);
        v2_58 = 1.0;
        v3_58 = 1.0;
        v0_184 = 0x3feb333333333333;
        v1_56 = 0x3feccccccccccccd;
        id obj_262 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
            "colorWithRed:green:blue:alpha:"));
        _objc_msgSend(obj_255, "setTitleColor:forState:");
        _objc_release(obj_262);
        int128_t v0_185;
        v0_185 = 12.0;
        id obj_263 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
            "boldSystemFontOfSize:"));
        id obj_264 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_255, "titleLabel"));
        _objc_msgSend(obj_264, "setFont:");
        _objc_release(obj_264);
        _objc_release(obj_263);
        id obj_265 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_255, "titleLabel"));
        _objc_msgSend(obj_265, "setAdjustsFontSizeToFitWidth:");
        _objc_release(obj_265);
        _objc_msgSend(obj_255, "setTag:");
        _objc_msgSend(obj_255, "addTarget:action:forControlEvents:");
        id obj_266 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "experimentInner"));
        _objc_msgSend(obj_266, "addSubview:");
        _objc_release(obj_266);
        v8 = v8 + 0x4047000000000000;
        _objc_release(obj_255);
        _objc_release(obj_254);
        i += 1;
    } while (i != 0x1e);
    
    id x0_862;
    int128_t v0_187;
    int128_t v1_57;
    int128_t v2_59;
    int128_t v3_59;
    x0_862 = _objc_alloc(clsRef_UITextView);
    v3_59 = 0x4054000000000000;
    v0_187 = 14.0;
    v1_57 = v8;
    v2_59 = v9;
    id obj_267;
    int128_t v1_58;
    int128_t v2_60;
    int128_t v3_60;
    obj_267 = _objc_msgSend(x0_862, "initWithFrame:");
    v2_60 = 0x3faeb851eb851eb8;
    v3_60 = 1.0;
    v1_58 = 0x3f947ae147ae147b;
    id obj_268 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_267, "setBackgroundColor:");
    _objc_release(obj_268);
    id obj_269;
    int128_t v0_188;
    obj_269 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_267, "layer"));
    v0_188 = 10.0;
    _objc_msgSend(obj_269, "setCornerRadius:");
    _objc_release(obj_269);
    id obj_270;
    int64_t x2_275;
    int128_t v0_189;
    obj_270 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_267, "layer"));
    v0_189 = 1.0;
    _objc_msgSend(obj_270, "setBorderWidth:", x2_275);
    int64_t x2_276;
    int64_t x3_56;
    int128_t v0_190;
    int128_t v1_59;
    x2_276 = _objc_release(obj_270);
    v1_59 = 1.0;
    v0_190 = 0x3fc3333333333333;
    id obj_271 = _objc_retainAutorelease(_objc_retainAutoreleasedReturnValue(_objc_msgSend(
        clsRef_UIColor, "colorWithWhite:alpha:", x2_276, x3_56)));
    id x0_876 = _objc_msgSend(obj_271, "CGColor");
    id obj_272 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_267, "layer"));
    _objc_msgSend(obj_272, "setBorderColor:", x0_876);
    _objc_release(obj_272);
    int128_t v0_191;
    int128_t v1_60;
    int128_t v2_61;
    int128_t v3_61;
    v0_191 = _objc_release(obj_271);
    v3_61 = 1.0;
    v0_191 = 0x3fd3333333333333;
    v1_60 = 0x3feb333333333333;
    v2_61 = 0x3fee666666666666;
    id obj_273 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_267, "setTextColor:");
    int64_t x3_57;
    int128_t v0_192;
    x3_57 = _objc_release(obj_273);
    v0_192 = 9.0;
    id obj_274 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
        "fontWithName:size:", &cfstr_Menlo, x3_57));
    _objc_msgSend(obj_267, "setFont:");
    _objc_release(obj_274);
    id obj_275 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_267, "font"));
    int64_t x2_280;
    int64_t x3_58;
    int128_t v0_193;
    int128_t v1_61;
    x2_280 = _objc_release(obj_275);
    
    if (!obj_275)
    {
        v1_61 = *_UIFontWeightRegular;
        v0_193 = 9.0;
        id obj_276 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
            "monospacedSystemFontOfSize:weight:", x2_280, x3_58));
        _objc_msgSend(obj_267, "setFont:");
        _objc_release(obj_276);
    }
    
    _objc_msgSend(obj_267, "setEditable:", 0);
    data_446a78;
    _objc_msgSend(obj_267, "setText:");
    _objc_msgSend(obj_267, "setTag:");
    id obj_277 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "experimentInner"));
    _objc_msgSend(obj_277, "addSubview:");
    _objc_release(obj_277);
    double v10 = v8 + 86.0;
    id x0_902;
    int128_t v0_194;
    int128_t v1_62;
    int128_t v2_62;
    int128_t v3_62;
    x0_902 = _objc_alloc(clsRef_UILabel);
    v0_194 = 14.0;
    v3_62 = 18.0;
    v1_62 = v10;
    v2_62 = v9;
    id obj_278 = _objc_msgSend(x0_902, "initWithFrame:");
    int64_t x2_286;
    int64_t x3_59;
    int128_t v0_195;
    int128_t v1_63;
    x2_286 = _objc_msgSend(obj_278, "setText:");
    v8 = *_UIFontWeightMedium;
    v0_195 = 11.0;
    v1_63 = v8;
    id obj_279 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
        "systemFontOfSize:weight:", x2_286, x3_59));
    _objc_msgSend(obj_278, "setFont:");
    int128_t v0_196;
    int128_t v1_64;
    int128_t v2_63;
    int128_t v3_63;
    v0_196 = _objc_release(obj_279);
    v1_64 = 0.5;
    v2_63 = 1.0;
    v3_63 = 1.0;
    v0_196 = 0x3fc999999999999a;
    id obj_280 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_278, "setTextColor:");
    _objc_release(obj_280);
    _objc_msgSend(obj_278, "setTextAlignment:", 1);
    id obj_281 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "experimentInner"));
    _objc_msgSend(obj_281, "addSubview:");
    _objc_release(obj_281);
    v10 = v10 + 18.0;
    id x0_916;
    int128_t v0_197;
    int128_t v1_65;
    int128_t v2_64;
    int128_t v3_64;
    x0_916 = _objc_alloc(clsRef_UILabel);
    v0_197 = 14.0;
    v3_64 = 16.0;
    v1_65 = v10;
    v2_64 = v9;
    id obj_282 = _objc_msgSend(x0_916, "initWithFrame:");
    int64_t x2_291;
    int64_t x3_60;
    int128_t v0_198;
    int128_t v1_66;
    x2_291 = _objc_msgSend(obj_282, "setText:");
    v0_198 = 10.0;
    v1_66 = v8;
    id obj_283 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
        "systemFontOfSize:weight:", x2_291, x3_60));
    _objc_msgSend(obj_282, "setFont:");
    int128_t v0_199;
    int128_t v1_67;
    int128_t v2_65;
    int128_t v3_65;
    v0_199 = _objc_release(obj_283);
    v1_67 = 0.5;
    v3_65 = 1.0;
    v0_199 = 0x3fdccccccccccccd;
    v2_65 = 0x3fee666666666666;
    id obj_284 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_282, "setTextColor:");
    _objc_release(obj_284);
    _objc_msgSend(obj_282, "setTextAlignment:", 1);
    id obj_285 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "experimentInner"));
    _objc_msgSend(obj_285, "addSubview:");
    _objc_release(obj_285);
    v8 = v10 + 16.0;
    id obj_286;
    int128_t v0_200;
    int128_t v1_68;
    int128_t v2_66;
    int128_t v3_66;
    obj_286 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:"));
    v0_200 = 14.0;
    v3_66 = 18.0;
    v1_68 = v8;
    v2_66 = v9;
    _objc_msgSend(obj_286, "setFrame:");
    int128_t v0_201;
    int128_t v1_69;
    int128_t v2_67;
    int128_t v3_67;
    v0_201 = _objc_msgSend(obj_286, "setTitle:forState:");
    v0_201 = 0x3fd6666666666666;
    v2_67 = 1.0;
    v3_67 = 1.0;
    v1_69 = 0x3fd999999999999a;
    id obj_287 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_286, "setTitleColor:forState:");
    int64_t x2_298;
    int64_t x3_63;
    int128_t v0_202;
    int128_t v1_70;
    x2_298 = _objc_release(obj_287);
    v1_70 = *_UIFontWeightBold;
    v0_202 = 11.0;
    id obj_288 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
        "systemFontOfSize:weight:", x2_298, x3_63));
    id obj_289 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_286, "titleLabel"));
    _objc_msgSend(obj_289, "setFont:");
    _objc_release(obj_289);
    _objc_release(obj_288);
    _objc_msgSend(obj_286, "addTarget:action:forControlEvents:");
    id obj_290 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "experimentInner"));
    _objc_msgSend(obj_290, "addSubview:");
    _objc_release(obj_290);
    v8 = v8 + 26.0;
    id obj_291;
    int128_t v0_204;
    int128_t v1_71;
    int128_t v2_68;
    int128_t v3_68;
    obj_291 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "experimentInner"));
    v0_204 = 0.0;
    v1_71 = 0.0;
    v2_68 = v2;
    v3_68 = v8;
    _objc_msgSend(obj_291, "setFrame:");
    _objc_release(obj_291);
    id obj_292;
    int64_t x2_302;
    int128_t v0_205;
    int128_t v1_72;
    obj_292 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "experimentScroll"));
    v0_205 = v2;
    v1_72 = v8;
    _objc_msgSend(obj_292, "setContentSize:", x2_302);
    _objc_release(obj_292);
    _objc_release(obj_286);
    _objc_release(obj_282);
    _objc_release(obj_278);
    _objc_release(obj_267);
    _objc_release(obj_253);
    _objc_release(obj_132);
    _objc_release(obj_128);
    _objc_release(obj_121);
    _objc_release(obj_114);
    _objc_release(obj_107);
    _objc_release(obj_100);
    _objc_release(obj_93);
    _objc_release(obj_86);
    _objc_release(obj_79);
    _objc_release(obj_72);
    _objc_release(obj_65);
    _objc_release(obj_58);
    _objc_release(obj_51);
    _objc_release(obj_44);
    _objc_release(obj_37);
    _objc_release(obj_30);
    _objc_release(obj_23);
    _objc_release(obj_16);
    _objc_release(obj_9);
    _objc_release(obj_5);
    _objc_release(obj_1);
    
    if (*___stack_chk_guard == x8)
        return;
    
    ___stack_chk_fail();
    /* no return */
}

id -[ACPanelController selectedItemNameOrDefault](struct ACPanelController* self, SEL sel)
{
    _objc_msgSend(self, "activeTab");
    id obj = _objc_retain(data_446a98);
    id x0_2 = _objc_msgSend(self, "selectedIndex");
    id x0_4;
    id x0_6;
    
    if (!(x0_2 & 0x8000000000000000))
    {
        x0_4 = _objc_msgSend(self, "selectedIndex");
        x0_6 = _objc_msgSend(obj, "count");
    }
    
    id x20_2;
    
    if (x0_2 & 0x8000000000000000 || x0_4 >= x0_6)
    {
        if (!_objc_msgSend(data_446a88, "count"))
            x20_2 = &cfstr_item_goldbar;
        else
        {
            id x20_1 = data_446a88;
            x20_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(x20_1, 
                "objectAtIndexedSubscript:", _arc4random_uniform(_objc_msgSend(x20_1, "count"))));
        }
    }
    else
        x20_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj, "objectAtIndexedSubscript:", 
            _objc_msgSend(self, "selectedIndex")));
    
    _objc_release(obj);
    /* tailcall */
    return _objc_autoreleaseReturnValue(x20_2);
}

void -[ACPanelController spawnBombTapped](struct ACPanelController* self, SEL sel)
{
    int64_t v14;
    int64_t var_78 = v14;
    int64_t v13;
    int64_t var_70 = v13;
    int64_t v12;
    int64_t var_68 = v12;
    float v0;
    int32_t v1;
    int32_t v2;
    v0 = sub_4113d8();
    int64_t v10;
    v10 = v2;
    sub_410c94(&cfstr_Spawn_Bomb:_50_random_items!);
    int32_t i_1 = 0x32;
    int64_t v11;
    v11 = -10f;
    int32_t i;
    
    do
    {
        id x21_1 = data_446a88;
        id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(x21_1, 
            "objectAtIndexedSubscript:", _arc4random_uniform(_objc_msgSend(x21_1, "count"))));
        v12 = 0x42c80000;
        v13 = _arc4random_uniform(0x7d0) / v12 + v11;
        v14 = _arc4random_uniform(0x3e8) / v12;
        uint32_t x0_7;
        int128_t v1_1;
        x0_7 = _arc4random_uniform(0x7d0);
        v1_1 = v1 + v14;
        sub_4114c8(obj, v0 + v13);
        _objc_release(obj);
        i = i_1;
        i_1 -= 1;
    } while (i != 1);
    /* tailcall */
    return sub_410c94(&cfstr_Spawn_Bomb_done!);
}

void -[ACPanelController spawnCircleTapped](struct ACPanelController* self, SEL sel)
{
    id x0_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "selectedItemNameOrDefault"));
    int32_t v0;
    int32_t v1;
    int32_t v2;
    v0 = sub_4113d8();
    int64_t v10;
    v10 = v1;
    int64_t var_68 = 0x18;
    int64_t var_60 = 0x4008000000000000;
    id var_70 = x0_1;
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
        "stringWithFormat:", &cfstr_Circle:_%@_(%d_pts,_r=%.1f)));
    sub_410c94(obj);
    _objc_release(obj);
    int32_t i = 0;
    double v0_1;
    v0_1 = 1f;
    v10 = v10 + v0_1;
    int64_t v11;
    v11 = 24f;
    int64_t v13;
    v13 = 3f;
    
    do
    {
        v0_1 = i;
        v0_1 = v0_1 / v11;
        v0_1 = v0_1 + v0_1;
        v0_1 = v0_1 * 3.1415926535897931;
        int32_t v0_2;
        int32_t v1_1;
        int128_t v2_1;
        v0_2 = ___sincosf_stret(v0_1);
        int32_t temp0_1 = vfma_f32(v0, v1_1, v13);
        v2_1 = vfma_f32(v2, v0_2, v13);
        sub_4114c8(x0_1, temp0_1);
        i += 1;
    } while (i != 0x18);
    
    sub_410c94(&cfstr_Circle_done!);
    /* tailcall */
    return _objc_release(x0_1);
}

void -[ACPanelController spawnTowerTapped](struct ACPanelController* self, SEL sel)
{
    id x0_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "selectedItemNameOrDefault"));
    int32_t v0;
    int32_t v1;
    int32_t v2;
    v0 = sub_4113d8();
    int64_t v10;
    v10 = v0;
    id var_50 = x0_1;
    int64_t var_48 = 0x14;
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
        "stringWithFormat:", &cfstr_Tower:_%@_(%d_high)));
    sub_410c94(obj);
    int128_t v1_1;
    int128_t v2_1;
    v1_1 = _objc_release(obj);
    int32_t i = 0;
    v10 = v10 + 2f;
    int64_t v11;
    v11 = 0.5f;
    
    do
    {
        v1_1 = vfma_f32(v1, i, v11);
        v2_1 = v2;
        v1_1 = sub_4114c8(x0_1, v10);
        i += 1;
    } while (i != 0x14);
    
    sub_410c94(&cfstr_Tower_done!);
    /* tailcall */
    return _objc_release(x0_1);
}

void -[ACPanelController spawnWallTapped](struct ACPanelController* self, SEL sel)
{
    id x0_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "selectedItemNameOrDefault"));
    int32_t v0;
    int32_t v1;
    int32_t v2;
    v0 = sub_4113d8();
    int64_t v10;
    v10 = v0;
    id var_70 = x0_1;
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
        "stringWithFormat:", &cfstr_Wall:_%@_(5x5)));
    sub_410c94(obj);
    int128_t v1_1;
    int128_t v2_1;
    v1_1 = _objc_release(obj);
    int32_t i = 0;
    int64_t v11;
    v11 = v10 + 2f;
    int64_t v12;
    v12 = 0.5f;
    
    do
    {
        int32_t j = 0;
        v10 = vfma_f32(v1, i, v12);
        
        do
        {
            v1_1 = v10;
            v2_1 = v2;
            v1_1 = sub_4114c8(x0_1, vfma_f32(v11, j, v12));
            j += 1;
        } while (j != 5);
        
        i += 1;
    } while (i != 5);
    
    sub_410c94(&cfstr_Wall_done!);
    /* tailcall */
    return _objc_release(x0_1);
}

void -[ACPanelController spawnSpiralTapped](struct ACPanelController* self, SEL sel)
{
    int64_t v14;
    int64_t var_68 = v14;
    int64_t v11;
    int64_t var_50 = v11;
    id x0_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "selectedItemNameOrDefault"));
    int32_t v0;
    int32_t v1;
    int32_t v2;
    v0 = sub_4113d8();
    int64_t v10;
    v10 = v2;
    id var_80 = x0_1;
    int64_t var_78 = 0x28;
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
        "stringWithFormat:", &cfstr_Spiral:_%@_(%d_pts)));
    sub_410c94(obj);
    _objc_release(obj);
    
    for (int32_t i = 0; i != 0x28; i += 1)
    {
        v11 = i;
        double v0_1;
        v0_1 = 0x42200000;
        v0_1 = v11 / v0_1;
        v0_1 = v0_1 * 4f;
        v0_1 = v0_1 * 3.1415926535897931;
        v14 = vfma_f32(0.5f, v11, 0.100000001f);
        int32_t v0_2;
        int32_t v1_2;
        int128_t v2_1;
        v0_2 = ___sincosf_stret(v0_1);
        int32_t temp0_2 = vfma_f32(v0, v1_2, v14);
        vfma_f32(v1, v11, 0.300000012f);
        v2_1 = vfma_f32(v10, v0_2, v14);
        sub_4114c8(x0_1, temp0_2);
    }
    
    sub_410c94(&cfstr_Spiral_done!);
    /* tailcall */
    return _objc_release(x0_1);
}

void -[ACPanelController monsterWaveTapped](struct ACPanelController* self, SEL sel)
{
    int64_t v14;
    int64_t var_78 = v14;
    int64_t v13;
    int64_t var_70 = v13;
    int64_t v12;
    int64_t var_68 = v12;
    int64_t v11;
    int64_t var_60 = v11;
    int32_t v0;
    int32_t v1;
    int32_t v2;
    v0 = sub_4113d8();
    int64_t v10;
    v10 = v2;
    struct objc_class_t* clsRef_NSString_1 = clsRef_NSString;
    id var_90 = _objc_msgSend(data_446a90, "count");
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString_1, 
        "stringWithFormat:", &cfstr_Monster_Wave:_%lu_types!));
    sub_410c94(obj);
    _objc_release(obj);
    
    if (_objc_msgSend(data_446a90, "count") >= 1)
    {
        int64_t x20_1 = 0;
        v14 = 8f;
        id x0_13;
        
        do
        {
            v11 = x20_1;
            id x0_8;
            double v0_1;
            x0_8 = _objc_msgSend(data_446a90, "count");
            v0_1 = x0_8;
            v0_1 = v11 / v0_1;
            v0_1 = v0_1 + v0_1;
            v0_1 = v0_1 * 3.1415926535897931;
            int32_t v0_2;
            int32_t v1_1;
            v0_2 = ___sincosf_stret(v0_1);
            v11 = vfma_f32(v0, v1_1, v14);
            v12 = vfma_f32(v10, v0_2, v14);
            id obj_1;
            int128_t v1_2;
            int128_t v2_1;
            obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(data_446a90, 
                "objectAtIndexedSubscript:", x20_1));
            v1_2 = v1;
            v2_1 = v12;
            sub_4114c8(obj_1, v11);
            _objc_release(obj_1);
            x20_1 += 1;
            x0_13 = _objc_msgSend(data_446a90, "count");
        } while (x20_1 < x0_13);
    }
    
    /* tailcall */
    return sub_410c94(&cfstr_Monster_Wave_done!);
}

void -[ACPanelController spawnStarTapped](struct ACPanelController* self, SEL sel)
{
    int64_t v14;
    int64_t var_68 = v14;
    int64_t v13;
    int64_t var_60 = v13;
    id x0_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "selectedItemNameOrDefault"));
    int32_t v0;
    int32_t v1;
    int32_t v2;
    v0 = sub_4113d8();
    int64_t v10;
    v10 = v1;
    id var_90 = x0_1;
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
        "stringWithFormat:", &cfstr_Star:_%@));
    sub_410c94(obj);
    _objc_release(obj);
    int32_t i = 0;
    double v0_1;
    v0_1 = 3f;
    int64_t v11;
    v11 = v10 + v0_1;
    int64_t v12;
    v12 = 10f;
    double v1_1 = -1.5707963267948966;
    double v2_1 = 3.1415926535897931;
    float v3 = 1.5f;
    float v4 = 4f;
    int64_t v15;
    v15 = 0.5f;
    
    do
    {
        v0_1 = i;
        v0_1 = v0_1 / v12;
        v0_1 = v0_1 + v0_1;
        v0_1 = vfma_f64(v1_1, v0_1, v2_1);
        
        if (!(i & 1))
            v13 = v4;
        else
            v13 = v3;
        
        int32_t v0_2;
        int32_t v1_2;
        v0_2 = ___sincosf_stret(v0_1);
        v10 = v1_2;
        int32_t temp0_2 = vfma_f32(v0, v1_2, v13);
        v14 = v13 * v0_2;
        vfma_f32(v11, v14, v15);
        sub_4114c8(x0_1, temp0_2);
        
        if (i == 9)
            break;
        
        i += 1;
        double v0_3;
        v0_3 = i;
        v0_3 = v0_3 / v12;
        v0_3 = v0_3 + v0_3;
        v0_3 = vfma_f64(-1.5707963267948966, v0_3, 3.1415926535897931);
        
        if (!(i & 1))
            v12 = 4f;
        else
            v12 = 1.5f;
        
        v10 = v13 * v10;
        v0_1 = ___sincosf_stret(v0_3);
        v13 = v12 * v1_1;
        v14 = v14 * v15;
        v0_1 = v12 * v0_1;
        v12 = v0_1 * v15;
        int32_t j = 1;
        v15 = 1f;
        
        do
        {
            v0_1 = j;
            v1_1 = 0.25f;
            v1_1 = v0_1 * v1_1;
            v2_1 = v15 - v1_1;
            v0_1 = vfma_f32(v0, v10, v2_1);
            v0_1 = vfma_f32(v0_1, v13, v1_1);
            v1_1 = v12 * v1_1;
            v1_1 = vfma_f32(v1_1, v14, v2_1);
            v1_1 = v11 + v1_1;
            v2_1 = v2;
            v0_1 = sub_4114c8(x0_1, v0_1);
            j += 1;
        } while (j != 4);
        
        v12 = 10f;
        v2_1 = 3.1415926535897931;
        v1_1 = -1.5707963267948966;
        v3 = 1.5f;
        v4 = 4f;
        v15 = 0.5f;
    } while (i != 0xa);
    
    sub_410c94(&cfstr_Star_done!);
    /* tailcall */
    return _objc_release(x0_1);
}

void -[ACPanelController spawnAtAllPresetsTapped](struct ACPanelController* self, SEL sel)
{
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "selectedItemNameOrDefault"));
    struct objc_class_t* clsRef_NSString_1 = clsRef_NSString;
    id obj_3 = obj;
    id var_68 = _objc_msgSend(data_4469d8, "count");
    id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString_1, 
        "stringWithFormat:", &cfstr_Spawning_%@_at_all_%lu_presets));
    sub_410c94(obj_1);
    _objc_release(obj_1);
    
    if (_objc_msgSend(data_4469d8, "count") >= 1)
    {
        int64_t x21_1 = 0;
        id x0_13;
        
        do
        {
            id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(data_4469d8, 
                "objectAtIndexedSubscript:", x21_1));
            int32_t var_60;
            _objc_msgSend(obj_2, "getValue:", &var_60);
            int128_t v1_1;
            int128_t v2_1;
            v1_1 = _objc_release(obj_2);
            int32_t var_5c;
            v1_1 = var_5c;
            int32_t var_58;
            v2_1 = var_58;
            sub_4114c8(obj, var_60);
            x21_1 += 1;
            x0_13 = _objc_msgSend(data_4469d8, "count");
        } while (x21_1 < x0_13);
    }
    
    sub_410c94(&cfstr_All_presets_done!);
    _objc_release(obj);
}

void -[ACPanelController giveawayBagTapped](struct ACPanelController* self, SEL sel)
{
    int64_t x8 = *___stack_chk_guard;
    float v0;
    int32_t v1;
    int32_t v2;
    v0 = sub_4113d8();
    float v8 = v0;
    int64_t v10;
    v10 = v1;
    int64_t v12;
    v12 = v2;
    sub_410c94(&cfstr_Giveaway_Mode:_spawning_5_rounds_of_giveaway_items!);
    struct __NSConstantString* const var_e8 = &cfstr_item_shredder;
    struct __NSConstantString* const var_e0 = &cfstr_item_rare_card;
    struct __NSConstantString* const var_d8 = &cfstr_item_pumpkin_pie;
    struct __NSConstantString* const var_d0 = &cfstr_item_timebomb;
    struct __NSConstantString* const var_c8 = &cfstr_item_backpack;
    struct __NSConstantString* const var_c0 = &cfstr_item_goldbar;
    struct __NSConstantString* const var_b8 = &cfstr_item_hh_key;
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &var_e8, 7));
    uint64_t x24 = 0;
    int32_t i = 0;
    float v0_1 = v10 + 1f;
    int64_t v13;
    v13 = -5f;
    
    do
    {
        if (_objc_msgSend(obj, "count") >= 1)
        {
            int64_t x23_1 = 0;
            float temp0_1 = vfma_f32(v0_1, i, 0.5f);
            float v9_1 = v8;
            int64_t x0_14;
            
            do
            {
                id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj, 
                    "objectAtIndexedSubscript:", x23_1));
                v10 = 0x42c80000;
                v8 = _arc4random_uniform(0x3e8) / v10 + v13;
                uint32_t x0_7;
                double v0_4;
                x0_7 = _arc4random_uniform(0x3e8);
                v0_4 = x0_7;
                v0_4 = v0_4 / v10;
                v0_4 = v0_4 + v13;
                v10 = v12 + v0_4;
                dispatch_time_t when = _dispatch_time(0, 
                    vcvtd_s64_f64((x24 + x23_1) * 0.059999999999999998 * 1000000000.0));
                _objc_retainAutorelease(__dispatch_main_q);
                void* (* const var_120)[0x20] = __NSConcreteStackBlock;
                int64_t var_118_1 = 0xc2000000;
                int64_t (* var_110_1)(void* arg1) = sub_41e990;
                void* const var_108_1 = &data_43c130;
                float var_f8_1 = v9_1 + v8;
                float var_f4_1 = temp0_1;
                int32_t var_f0_1 = v10;
                id obj_2 = _objc_retain(obj_1);
                _dispatch_after(when, __dispatch_main_q, &var_120);
                _objc_release(obj_1);
                _objc_release(obj_2);
                x23_1 += 1;
                x0_14 = _objc_msgSend(obj, "count");
            } while (x23_1 < x0_14);
            x24 = x24 + x23_1;
            v8 = v9_1;
        }
        
        i += 1;
    } while (i != 5);
    
    uint64_t var_150 = x24;
    id obj_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
        "stringWithFormat:", &cfstr_Giveaway:_%d_items_spawning_(5_rounds)!));
    sub_410c94(obj_3);
    _objc_release(obj_3);
    _objc_release(obj);
    
    if (*___stack_chk_guard == x8)
        return;
    
    ___stack_chk_fail();
    /* no return */
}

int64_t sub_41e990(void* arg1)
{
    int128_t v1;
    v1 = *(arg1 + 0x2c);
    int128_t v2;
    v2 = *(arg1 + 0x30);
    /* tailcall */
    return sub_4114c8(*(arg1 + 0x20), *(arg1 + 0x28));
}

void -[ACPanelController ringToggleTapped:](struct ACPanelController* self, SEL sel, id ringToggleTapped)
{
    id obj = _objc_retain(ringToggleTapped);
    uint32_t x9 = data_446b29;
    data_446b29 = x9 ^ 1;
    
    if (!x9)
    {
        int64_t x2_2;
        int64_t x3_1;
        int64_t x4_1;
        int64_t x5_1;
        int128_t v0_1;
        int128_t v2_1;
        int128_t v3_1;
        x2_2 = _objc_msgSend(obj, "setTitle:forState:", &cfstr_??_Ring_ACTIVE_(tap_to_stop), 0);
        v0_1 = 0x3fe999999999999a;
        v3_1 = 1.0;
        v2_1 = 0x3fc999999999999a;
        int64_t obj_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
            "colorWithRed:green:blue:alpha:", x2_2, x3_1, x4_1, x5_1));
        _objc_msgSend(obj, "setBackgroundColor:", obj_3);
        _objc_release(obj_3);
        sub_410c94(&cfstr_Ring_started_-_items_orbit_around_you);
        id var_38;
        _objc_initWeak(&var_38, self);
        struct objc_class_t* clsRef_NSTimer_1 = clsRef_NSTimer;
        void* (* const var_60)[0x20] = __NSConcreteStackBlock;
        int64_t var_58_1 = 0xc2000000;
        int64_t (* var_50_1)(void* arg1, id arg2) = sub_41ebcc;
        void* const var_48_1 = &data_43c3b0;
        id var_40;
        int64_t x4_2;
        int128_t v0_2;
        x4_2 = _objc_copyWeak(&var_40, &var_38);
        v0_2 = 1.5;
        id x0_16 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSTimer_1, 
            "scheduledTimerWithTimeInterval:repeats:block:", 1, &var_60, x4_2));
        id obj_4 = data_446a00;
        data_446a00 = x0_16;
        _objc_release(obj_4);
        _objc_destroyWeak(&var_40);
        _objc_destroyWeak(&var_38);
    }
    else
    {
        int64_t x2;
        int64_t x3;
        int64_t x4;
        int64_t x5;
        int128_t v0;
        int128_t v1_1;
        int128_t v2;
        int128_t v3;
        x2 = _objc_msgSend(obj, "setTitle:forState:", &cfstr_??_Ring_Around_Player_(toggle), 0);
        v0 = 0x3fb999999999999a;
        v1_1 = 0x3fe6666666666666;
        v2 = 0x3fe3333333333333;
        v3 = 1.0;
        id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
            "colorWithRed:green:blue:alpha:", x2, x3, x4, x5));
        _objc_msgSend(obj, "setBackgroundColor:", obj_1);
        _objc_release(obj_1);
        id x0_6 = data_446a00;
        
        if (x0_6)
        {
            _objc_msgSend(x0_6, "invalidate");
            id obj_2 = data_446a00;
            data_446a00 = 0;
            _objc_release(obj_2);
        }
        
        sub_410c94(&cfstr_Ring_stopped);
    }
    
    _objc_release(obj);
}

int64_t sub_41ebcc(void* arg1, id arg2)
{
    int64_t v13;
    int64_t var_50 = v13;
    int64_t v12;
    int64_t var_48 = v12;
    int64_t v11;
    int64_t var_40 = v11;
    int64_t v10;
    int64_t var_38 = v10;
    int64_t v9;
    int64_t var_30 = v9;
    int64_t v8;
    int64_t var_28 = v8;
    id x19;
    
    if (!data_446b29)
    {
        _objc_msgSend(arg2, "invalidate");
        x19 = data_446a00;
        data_446a00 = 0;
    }
    else
    {
        id obj = _objc_loadWeakRetained(arg1 + 0x20);
        x19 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj, "selectedItemNameOrDefault"));
        _objc_release(obj);
        double v0_1;
        int32_t v1_1;
        int32_t v2_1;
        v0_1 = sub_4113d8();
        v8 = v0_1;
        v9 = v2_1;
        int32_t i = 0;
        v0_1 = 1.5f;
        v10 = v1_1 + v0_1;
        v11 = 12f;
        v13 = 3f;
        
        do
        {
            v0_1 = i;
            v0_1 = v0_1 / v11;
            v0_1 = v0_1 + v0_1;
            v0_1 = v0_1 * 3.1415926535897931;
            int32_t v0_2;
            int32_t v1_2;
            int128_t v2_2;
            v0_2 = ___sincosf_stret(v0_1);
            int32_t temp0_1 = vfma_f32(v8, v1_2, v13);
            v2_2 = vfma_f32(v9, v0_2, v13);
            sub_4114c8(x19, temp0_1);
            i += 1;
        } while (i != 0xc);
    }
    
    /* tailcall */
    return _objc_release(x19);
}

void -[ACPanelController infiniteFlareTapped](struct ACPanelController* self, SEL sel)
{
    int64_t x8 = *___stack_chk_guard;
    float v0;
    int32_t v1;
    float v2;
    v0 = sub_4113d8();
    int64_t v10;
    v10 = v1;
    int128_t v1_1;
    int128_t v2_1;
    v1_1 = sub_410c94(&cfstr_Spawning_Infinite_Flare_Gun_kit!);
    int32_t i = 0;
    float v0_1 = 1f;
    int64_t v11;
    v11 = v10 + v0_1;
    int64_t v15;
    v15 = v2;
    int64_t v12;
    v12 = v2 + v0_1;
    int64_t v13;
    v13 = 0.5f;
    
    do
    {
        v1_1 = v11;
        v2_1 = v12;
        v1_1 = sub_4114c8(&cfstr_item_flaregun, vfma_f32(v0, i, v13));
        i += 1;
    } while (i != 3);
    
    struct __NSConstantString* const var_d0 = &cfstr_item_rpg_ammo;
    struct __NSConstantString* const var_c8 = &cfstr_item_shotgun_ammo;
    struct __NSConstantString* const var_c0 = &cfstr_item_revolver_ammo;
    struct __NSConstantString* const var_b8 = &cfstr_item_rpg_ammo_egg;
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &var_d0, 4));
    int64_t i_1 = 0;
    float v0_2 = v10 + 0.5f;
    v11 = -3f;
    v10 = v15;
    
    do
    {
        v15 = 0x42c80000;
        float v9 = _arc4random_uniform(0x258) / v15 + v11;
        v15 = v10 + _arc4random_uniform(0x258) / v15 + v11;
        id x0_5 = _objc_msgSend(obj, "count");
        id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj, 
            "objectAtIndexedSubscript:", i_1 % x0_5));
        dispatch_time_t when = _dispatch_time(0, vcvtd_s64_f64(i_1 * 0.02 * 1000000000.0));
        _objc_retainAutorelease(__dispatch_main_q);
        void* (* const var_108)[0x20] = __NSConcreteStackBlock;
        int64_t var_100_1 = 0xc2000000;
        int64_t (* var_f8_1)(void* arg1) = sub_41ef50;
        void* const var_f0_1 = &data_43c130;
        float var_e0_1 = v0 + v9;
        float var_dc_1 = v0_2;
        int32_t var_d8_1 = v15;
        id obj_2 = _objc_retain(obj_1);
        _dispatch_after(when, __dispatch_main_q, &var_108);
        _objc_release(obj_1);
        _objc_release(obj_2);
        i_1 += 1;
    } while (i_1 != 0x50);
    
    sub_410c94(&cfstr_3_Flare_guns_+_80_mixed_ammo_spawned!);
    _objc_release(obj);
    
    if (*___stack_chk_guard == x8)
        return;
    
    ___stack_chk_fail();
    /* no return */
}

int64_t sub_41ef50(void* arg1)
{
    int128_t v1;
    v1 = *(arg1 + 0x2c);
    int128_t v2;
    v2 = *(arg1 + 0x30);
    /* tailcall */
    return sub_4114c8(*(arg1 + 0x20), *(arg1 + 0x28));
}

void -[ACPanelController godKitTapped](struct ACPanelController* self, SEL sel)
{
    int64_t v13;
    int64_t var_80 = v13;
    int64_t v12;
    int64_t var_78 = v12;
    int64_t v11;
    int64_t var_70 = v11;
    int64_t x8 = *___stack_chk_guard;
    int32_t v0;
    int32_t v1;
    int32_t v2;
    v0 = sub_4113d8();
    int64_t v10;
    v10 = v1;
    sub_410c94(&cfstr_God_Kit:_spawning_OP_loadout!);
    struct __NSConstantString* const var_150 = &cfstr_item_jetpack;
    struct __NSConstantString* const var_148 = &cfstr_item_rpg;
    struct __NSConstantString* const var_140 = &cfstr_item_rpg_ammo;
    struct __NSConstantString* const var_138 = &cfstr_item_rpg_ammo;
    struct __NSConstantString* const var_130 = &cfstr_item_rpg_ammo;
    struct __NSConstantString* const var_128 = &cfstr_item_grenade_launcher;
    struct __NSConstantString* const var_120 = &cfstr_item_flamethrower_skull_ruby;
    struct __NSConstantString* const var_118 = &cfstr_item_demon_sword;
    struct __NSConstantString* const var_110 = &cfstr_item_great_sword;
    struct __NSConstantString* const var_108 = &cfstr_item_hookshot_sword;
    struct __NSConstantString* const var_100 = &cfstr_item_shield_viking_4;
    struct __NSConstantString* const var_f8 = &cfstr_item_teleport_gun;
    struct __NSConstantString* const var_f0 = &cfstr_item_hoverpad;
    struct __NSConstantString* const var_e8 = &cfstr_item_backpack_mega;
    struct __NSConstantString* const var_e0 = &cfstr_item_flashlight_mega;
    struct __NSConstantString* const var_d8 = &cfstr_item_ogre_hands;
    struct __NSConstantString* const var_d0 = &cfstr_item_shotgun;
    struct __NSConstantString* const var_c8 = &cfstr_item_shotgun_ammo;
    struct __NSConstantString* const var_c0 = &cfstr_item_shotgun_ammo;
    struct __NSConstantString* const var_b8 = &cfstr_item_revolver_gold;
    struct __NSConstantString* const var_b0 = &cfstr_item_revolver_ammo;
    struct __NSConstantString* const var_a8 = &cfstr_item_revolver_ammo;
    struct __NSConstantString* const var_a0 = &cfstr_item_stellarsword_gold;
    struct __NSConstantString* const var_98 = &cfstr_item_alphablade;
    struct __NSConstantString* const var_90 = &cfstr_item_bloodlust_vial;
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &var_150, 0x19));
    
    if (_objc_msgSend(obj, "count") >= 1)
    {
        int64_t x21_1 = 0;
        v10 = v10 + 1f;
        v13 = -3f;
        id x0_9;
        
        do
        {
            v11 = 0x42c80000;
            v12 = _arc4random_uniform(0x258) / v11 + v13;
            float v0_3 = _arc4random_uniform(0x258) / v11 + v13;
            v11 = v0 + v12;
            v12 = v2 + v0_3;
            id obj_1;
            int128_t v1_1;
            int128_t v2_1;
            obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj, 
                "objectAtIndexedSubscript:", x21_1));
            v1_1 = v10;
            v2_1 = v12;
            sub_4114c8(obj_1, v11);
            _objc_release(obj_1);
            x21_1 += 1;
            x0_9 = _objc_msgSend(obj, "count");
        } while (x21_1 < x0_9);
    }
    
    struct objc_class_t* clsRef_NSString_1 = clsRef_NSString;
    id var_160 = _objc_msgSend(obj, "count");
    id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString_1, 
        "stringWithFormat:", &cfstr_God_Kit:_%lu_items_spawned!));
    sub_410c94(obj_2);
    _objc_release(obj_2);
    _objc_release(obj);
    
    if (*___stack_chk_guard == x8)
        return;
    
    ___stack_chk_fail();
    /* no return */
}

void -[ACPanelController moneyPrinterTapped](struct ACPanelController* self, SEL sel)
{
    int64_t v12;
    int64_t var_88 = v12;
    float v0;
    int32_t v1;
    float v2;
    v0 = sub_4113d8();
    int64_t v10;
    v10 = v1;
    sub_410c94(&cfstr_Money_Printer:_printing_gold!);
    int32_t i = 0;
    float v0_1 = v10 + 0.5f;
    double v11 = 0.0;
    
    do
    {
        float v9_1 = 0x42c80000;
        v12 = -3f;
        v10 = _arc4random_uniform(0x258) / v9_1 + v12;
        float v0_3 = _arc4random_uniform(0x258) / v9_1 + v12;
        v9_1 = v0 + v10;
        v10 = vfma_f32(v0_1, i, 0.100000001f);
        v12 = v2 + v0_3;
        id obj;
        
        obj = (i & 0xff) * 0xaaaaaaab < 0x55555556 ? &cfstr_item_goldbar : &cfstr_item_goldcoin;
        
        id obj_1 = _objc_retain(obj);
        dispatch_time_t when =
            _dispatch_time(0, vcvtd_s64_f64(v11 * 0.050000000000000003 * 1000000000.0));
        _objc_retainAutorelease(__dispatch_main_q);
        void* (* const var_d8)[0x20] = __NSConcreteStackBlock;
        int64_t var_d0_1 = 0xc2000000;
        int64_t (* var_c8_1)(void* arg1) = sub_41f3dc;
        void* const var_c0_1 = &data_43c130;
        float var_b0_1 = v9_1;
        int32_t var_ac_1 = v10;
        int32_t var_a8_1 = v12;
        id obj_2 = _objc_retain(obj_1);
        _dispatch_after(when, __dispatch_main_q, &var_d8);
        _objc_release(obj_1);
        _objc_release(obj_2);
        v11 = v11 + 1.0;
        i += 1;
    } while (i != 0x1e);
    
    sub_410c94(&cfstr_Money_Printer:_30_gold_items_incoming!);
}

int64_t sub_41f3dc(void* arg1)
{
    int128_t v1;
    v1 = *(arg1 + 0x2c);
    int128_t v2;
    v2 = *(arg1 + 0x30);
    /* tailcall */
    return sub_4114c8(*(arg1 + 0x20), *(arg1 + 0x28));
}

void -[ACPanelController nukeZoneTapped](struct ACPanelController* self, SEL sel)
{
    int64_t v12;
    int64_t var_88 = v12;
    int64_t x8 = *___stack_chk_guard;
    int64_t v0;
    float v1;
    int32_t v2;
    int128_t v9;
    v0 = sub_4113d8();
    sub_410c94(&cfstr_?_MEGA_NUKE_INCOMING_?_TOTAL_ANNIHILATION_?);
    struct __NSConstantString* const var_1a0 = &cfstr_item_dynamite;
    struct __NSConstantString* const var_198 = &cfstr_item_grenade;
    struct __NSConstantString* const var_190 = &cfstr_item_cluster_grenade;
    struct __NSConstantString* const var_188 = &cfstr_item_rpg_ammo;
    struct __NSConstantString* const var_180 = &cfstr_item_pumpkin_bomb;
    struct __NSConstantString* const var_178 = &cfstr_item_landmine;
    struct __NSConstantString* const var_170 = &cfstr_item_sticky_dynamite;
    struct __NSConstantString* const var_168 = &cfstr_item_timebomb;
    struct __NSConstantString* const var_160 = &cfstr_item_flashbang;
    struct __NSConstantString* const var_158 = &cfstr_item_broccoli_grenade;
    struct __NSConstantString* const var_150 = &cfstr_item_tripwire_explosive;
    struct __NSConstantString* const var_148 = &cfstr_item_rpg_ammo_egg;
    struct __NSConstantString* const var_140 = &cfstr_item_rpg_ammo_spear;
    struct __NSConstantString* const var_138 = &cfstr_item_dynamite_cube;
    struct __NSConstantString* const var_130 = &cfstr_item_anti_gravity_grenade;
    struct __NSConstantString* const var_128 = &cfstr_item_impulse_grenade;
    struct __NSConstantString* const var_120 = &cfstr_item_tele_grenade;
    struct __NSConstantString* const var_118 = &cfstr_item_broccoli_shrink_grenade;
    struct __NSConstantString* const var_110 = &cfstr_item_flamethrower;
    struct __NSConstantString* const var_108 = &cfstr_item_flamethrower_skull;
    struct __NSConstantString* const var_100 = &cfstr_item_flamethrower_skull_ruby;
    struct __NSConstantString* const var_f8 = &cfstr_item_rpg;
    struct __NSConstantString* const var_f0 = &cfstr_item_rpg_cny;
    struct __NSConstantString* const var_e8 = &cfstr_item_rpg_easter;
    struct __NSConstantString* const var_e0 = &cfstr_item_rpg_smshr;
    struct __NSConstantString* const var_d8 = &cfstr_item_rpg_spear;
    struct __NSConstantString* const var_d0 = &cfstr_item_grenade_launcher;
    struct __NSConstantString* const var_c8 = &cfstr_item_grenade_gold;
    struct __NSConstantString* const var_c0 = &cfstr_item_radiation_gun;
    struct __NSConstantString* const var_b8 = &cfstr_item_pumpkinjack;
    id obj;
    int128_t v0_1;
    obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &var_1a0, 0x1e));
    *(&v0_1 + 4) = v1;
    int128_t var_330 = v0_1;
    v9 = 0.0;
    int32_t i_1 = 0x64;
    int128_t v14;
    v14 = 0x42c80000;
    *(&v14 + 4) = 0x42c80000;
    int128_t v15;
    v15 = 0x41000000c1a00000;
    double v8_1;
    int32_t i;
    
    do
    {
        v0_1 = v9 * 0.029999999999999999;
        v0_1 = v0_1 * 1000000000.0;
        uint64_t delta = vcvtd_s64_f64(v0_1);
        uint32_t x0_2 = _arc4random_uniform(0xfa0);
        v12 = _arc4random_uniform(0xfa0) / 0x42c80000 + -20f;
        uint32_t x0_4;
        int128_t v0_3;
        int128_t v1_3;
        x0_4 = _arc4random_uniform(0x5dc);
        v0_3 = x0_2;
        *(&v0_3 + 4) = x0_4;
        v8_1 = vadd_f32(var_330, vadd_f32(vdiv_f32(vcvt_f32_u32(v0_3), v14), v15));
        int128_t v0_6;
        v0_6 = v2;
        v12 = v0_6 + v12;
        id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj, 
            "objectAtIndexedSubscript:", _arc4random_uniform(_objc_msgSend(obj, "count"))));
        dispatch_time_t when = _dispatch_time(0, delta);
        _objc_retainAutorelease(__dispatch_main_q);
        void* (* const var_228)[0x20] = __NSConcreteStackBlock;
        int64_t var_220_1 = 0xc2000000;
        int64_t (* var_218_1)(void* arg1) = sub_41fd0c;
        void* const var_210_1 = &data_43c130;
        double var_200_1 = v8_1;
        int32_t var_1f8_1 = v12;
        id obj_2 = _objc_retain(obj_1);
        _dispatch_after(when, __dispatch_main_q, &var_228);
        _objc_release(obj_1);
        _objc_release(obj_2);
        v0_1 = 1.0;
        v9 = v9 + v0_1;
        i = i_1;
        i_1 -= 1;
    } while (i != 1);
    v0_1 = 0x400921fb54442d18;
    v12 = v2;
    v14 = 15f;
    
    do
    {
        v0_1 = i_1;
        v8_1 = 0x42c80000;
        v0_1 = v0_1 / v8_1;
        v0_1 = v0_1;
        v0_1 = v0_1 * 3.1415926535897931;
        v0_1 = v0_1 + v0_1;
        v9 = v0_1;
        v15 = _arc4random_uniform(0x7d0) / v8_1 + v14;
        int32_t v0_8;
        int32_t v1_4;
        v0_8 = ___sincosf_stret(v9);
        v9 = v1_4 * v15;
        v15 = v0_8 * v15;
        float v0_9 = _arc4random_uniform(0x7d0) / v8_1 + v14;
        v8_1 = v0 + v9;
        v9 = v1 + v0_9;
        v15 = v12 + v15;
        id obj_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj, 
            "objectAtIndexedSubscript:", _arc4random_uniform(_objc_msgSend(obj, "count"))));
        dispatch_time_t when_1 =
            _dispatch_time(0, vcvtd_s64_f64((i_1 + 0x64) * 0.029999999999999999 * 1000000000.0));
        _objc_retainAutorelease(__dispatch_main_q);
        void* (* const var_260)[0x20] = __NSConcreteStackBlock;
        int64_t var_258_1 = 0xc2000000;
        int64_t (* var_250_1)(void* arg1) = sub_41fd20;
        void* const var_248_1 = &data_43c130;
        int32_t var_238_1 = v8_1;
        int32_t var_234_1 = v9;
        int32_t var_230_1 = v15;
        id obj_4 = _objc_retain(obj_3);
        _dispatch_after(when_1, __dispatch_main_q, &var_260);
        _objc_release(obj_3);
        _objc_release(obj_4);
        i_1 += 1;
    } while (i_1 != 0x64);
    
    int32_t i_2 = 0xc8;
    v9 = 0x42c80000;
    *(&v9 + 4) = 0x42c80000;
    v14 = 0x41f00000c2700000;
    double v15_1;
    
    do
    {
        v0_1 = i_2;
        v0_1 = v0_1 * 0.029999999999999999;
        v0_1 = v0_1 * 1000000000.0;
        uint64_t delta_1 = vcvtd_s64_f64(v0_1);
        uint32_t x0_27 = _arc4random_uniform(0x2ee0);
        v8_1 = _arc4random_uniform(0x2ee0) / 0x42c80000 + 0xc2700000;
        uint32_t x0_29;
        int128_t v0_12;
        int128_t v1_7;
        x0_29 = _arc4random_uniform(0xfa0);
        v0_12 = x0_27;
        *(&v0_12 + 4) = x0_29;
        v15_1 = vadd_f32(var_330, vadd_f32(vdiv_f32(vcvt_f32_u32(v0_12), v9), v14));
        v8_1 = v12 + v8_1;
        id obj_5 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj, 
            "objectAtIndexedSubscript:", _arc4random_uniform(_objc_msgSend(obj, "count"))));
        dispatch_time_t when_2 = _dispatch_time(0, delta_1);
        _objc_retainAutorelease(__dispatch_main_q);
        void* (* const var_298)[0x20] = __NSConcreteStackBlock;
        int64_t var_290_1 = 0xc2000000;
        int64_t (* var_288_1)(void* arg1) = sub_41fd34;
        void* const var_280_1 = &data_43c130;
        double var_270_1 = v15_1;
        int32_t var_268_1 = v8_1;
        id obj_6 = _objc_retain(obj_5);
        _dispatch_after(when_2, __dispatch_main_q, &var_298);
        _objc_release(obj_5);
        _objc_release(obj_6);
        i_2 += 1;
    } while (i_2 != 0x12c);
    
    v0_1 = 2f;
    int64_t v13;
    v13 = v1 + v0_1;
    v14 = -2f;
    
    do
    {
        v8_1 = 0x42c80000;
        v15_1 = _arc4random_uniform(0x190) / v8_1 + v14;
        float v0_17 = _arc4random_uniform(0x190) / v8_1 + v14;
        v8_1 = v0 + v15_1;
        v15_1 = v12 + v0_17;
        id obj_7 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj, 
            "objectAtIndexedSubscript:", _arc4random_uniform(_objc_msgSend(obj, "count"))));
        dispatch_time_t when_3 =
            _dispatch_time(0, vcvtd_s64_f64(i_2 * 0.040000000000000001 * 1000000000.0));
        _objc_retainAutorelease(__dispatch_main_q);
        void* (* const var_2d0)[0x20] = __NSConcreteStackBlock;
        int64_t var_2c8_1 = 0xc2000000;
        int64_t (* var_2c0_1)(void* arg1) = sub_41fd48;
        void* const var_2b8_1 = &data_43c130;
        int32_t var_2a8_1 = v8_1;
        int32_t var_2a4_1 = v13;
        int32_t var_2a0_1 = v15_1;
        id obj_8 = _objc_retain(obj_7);
        _dispatch_after(when_3, __dispatch_main_q, &var_2d0);
        _objc_release(obj_7);
        _objc_release(obj_8);
        i_2 += 1;
    } while (i_2 != 0x15e);
    
    struct __NSConstantString* const var_1f0 = &cfstr_item_rpg;
    struct __NSConstantString* const var_1e8 = &cfstr_item_rpg_cny;
    struct __NSConstantString* const var_1e0 = &cfstr_item_rpg_easter;
    struct __NSConstantString* const var_1d8 = &cfstr_item_rpg_smshr;
    struct __NSConstantString* const var_1d0 = &cfstr_item_rpg_spear;
    struct __NSConstantString* const var_1c8 = &cfstr_item_grenade_launcher;
    struct __NSConstantString* const var_1c0 = &cfstr_item_flamethrower;
    struct __NSConstantString* const var_1b8 = &cfstr_item_flamethrower_skull;
    struct __NSConstantString* const var_1b0 = &cfstr_item_flamethrower_skull_ruby;
    struct __NSConstantString* const var_1a8 = &cfstr_item_radiation_gun;
    id obj_9;
    double v0_19;
    obj_9 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:"));
    int32_t i_3 = 0;
    v0_19 = 20f;
    v0_19 = v1 + v0_19;
    var_330 = v0_19;
    v14 = v12;
    
    do
    {
        v8_1 = i_3;
        v0_19 = 0x42480000;
        v0_19 = v8_1 / v0_19;
        v0_19 = v0_19 * 3.1415926535897931;
        v0_19 = v0_19 + v0_19;
        v12 = vfma_f32(5f, i_3 - (((i_3 & 0xff) * 0xcd) >> 0xb) * 0xa, 3f);
        int32_t v0_20;
        int32_t v1_11;
        v0_20 = ___sincosf_stret(v0_19);
        v15_1 = vfma_f32(v0, v1_11, v12);
        v8_1 = vfma_f32(var_330, v8_1, 0.5f);
        v12 = vfma_f32(v14, v0_20, v12);
        id obj_10 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_9, 
            "objectAtIndexedSubscript:", _arc4random_uniform(_objc_msgSend(obj_9, "count"))));
        dispatch_time_t when_4 =
            _dispatch_time(0, vcvtd_s64_f64((i_3 + 0x15e) * 0.040000000000000001 * 1000000000.0));
        _objc_retainAutorelease(__dispatch_main_q);
        void* (* const var_308)[0x20] = __NSConcreteStackBlock;
        int64_t var_300_1 = 0xc2000000;
        int64_t (* var_2f8_1)(void* arg1) = sub_41fd5c;
        void* const var_2f0_1 = &data_43c130;
        int32_t var_2e0_1 = v15_1;
        int32_t var_2dc_1 = v8_1;
        int32_t var_2d8_1 = v12;
        id obj_11 = _objc_retain(obj_10);
        _dispatch_after(when_4, __dispatch_main_q, &var_308);
        _objc_release(obj_10);
        _objc_release(obj_11);
        i_3 += 1;
    } while (i_3 != 0x32);
    
    sub_410c94(&cfstr_?_MEGA_NUKE:_400_explosives_in_5_waves_?_RIP_SERVER_?);
    _objc_release(obj_9);
    _objc_release(obj);
    
    if (*___stack_chk_guard == x8)
        return;
    
    ___stack_chk_fail();
    /* no return */
}

int64_t sub_41fd0c(void* arg1)
{
    int128_t v1;
    v1 = *(arg1 + 0x2c);
    int128_t v2;
    v2 = *(arg1 + 0x30);
    /* tailcall */
    return sub_4114c8(*(arg1 + 0x20), *(arg1 + 0x28));
}

int64_t sub_41fd20(void* arg1)
{
    int128_t v1;
    v1 = *(arg1 + 0x2c);
    int128_t v2;
    v2 = *(arg1 + 0x30);
    /* tailcall */
    return sub_4114c8(*(arg1 + 0x20), *(arg1 + 0x28));
}

int64_t sub_41fd34(void* arg1)
{
    int128_t v1;
    v1 = *(arg1 + 0x2c);
    int128_t v2;
    v2 = *(arg1 + 0x30);
    /* tailcall */
    return sub_4114c8(*(arg1 + 0x20), *(arg1 + 0x28));
}

int64_t sub_41fd48(void* arg1)
{
    int128_t v1;
    v1 = *(arg1 + 0x2c);
    int128_t v2;
    v2 = *(arg1 + 0x30);
    /* tailcall */
    return sub_4114c8(*(arg1 + 0x20), *(arg1 + 0x28));
}

int64_t sub_41fd5c(void* arg1)
{
    int128_t v1;
    v1 = *(arg1 + 0x2c);
    int128_t v2;
    v2 = *(arg1 + 0x30);
    /* tailcall */
    return sub_4114c8(*(arg1 + 0x20), *(arg1 + 0x28));
}

void -[ACPanelController flyToggleTapped:](struct ACPanelController* self, SEL sel, id flyToggleTapped)
{
    uint32_t x24 = data_446b2a;
    data_446b2a = x24 ^ 1;
    struct objc_class_t* clsRef_UIColor_1 = clsRef_UIColor;
    id obj;
    int64_t x2;
    int64_t x3;
    int64_t x4;
    int64_t x5;
    int128_t v0;
    int128_t v1;
    int128_t v2;
    int128_t v3;
    obj = _objc_retain(flyToggleTapped);
    
    if (x24)
    {
        v0 = 0x3fc3333333333333;
        v1 = 0x3fd999999999999a;
        v2 = 0x3feccccccccccccd;
        v3 = 1.0;
        id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor_1, 
            "colorWithRed:green:blue:alpha:", x2, x3, x4, x5));
        _objc_msgSend(flyToggleTapped, "setBackgroundColor:", obj_1);
        _objc_release(obj_1);
        _objc_msgSend(flyToggleTapped, "setTitle:forState:", &cfstr_??_Fly_/_Noclip_Mode, 0);
        _objc_release(obj);
        sub_410c94(&cfstr_Fly_mode_DISABLED);
        _objc_msgSend(self, "hideFlyControls");
        _objc_msgSend(data_446a68, "invalidate");
        id x0_9 = data_446a68;
        data_446a68 = 0;
        /* tailcall */
        return _objc_release(x0_9);
    }
    
    v0 = 0x3fb999999999999a;
    v1 = 0x3fe999999999999a;
    v2 = 0x3fd3333333333333;
    v3 = 1.0;
    id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor_1, 
        "colorWithRed:green:blue:alpha:", x2, x3, x4, x5));
    _objc_msgSend(flyToggleTapped, "setBackgroundColor:", obj_2);
    _objc_release(obj_2);
    _objc_msgSend(flyToggleTapped, "setTitle:forState:", &cfstr_??_Fly_Mode:_ON, 0);
    _objc_release(obj);
    sub_410c94(&cfstr_Fly_mode_ENABLED_-_use_controls_to_fly);
    int64_t x4_2;
    int128_t v0_2;
    x4_2 = _objc_msgSend(self, "showFlyControls");
    struct objc_class_t* clsRef_NSTimer_1 = clsRef_NSTimer;
    void* (* const var_68)[0x20] = __NSConcreteStackBlock;
    v0_2 = 0xc2000000;
    int64_t var_60 = 0xc2000000;
    int64_t (* var_58)(void* arg1, id arg2) = sub_41ff9c;
    void* const var_50 = &data_43c3e0;
    struct ACPanelController* self_1 = self;
    v0_2 = 0x3fa999999999999a;
    id x0_19 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSTimer_1, 
        "scheduledTimerWithTimeInterval:repeats:block:", 1, &var_68, x4_2));
    id obj_3 = data_446a68;
    data_446a68 = x0_19;
    _objc_release(obj_3);
}

int64_t sub_41ff9c(void* arg1, id arg2)
{
    if (data_446b2a)
        /* tailcall */
        return _objc_msgSend(*(arg1 + 0x20), "flyTick");
    
    _objc_msgSend(arg2, "invalidate");
    id x0_3 = data_446a68;
    data_446a68 = 0;
    /* tailcall */
    return _objc_release(x0_3);
}

void -[ACPanelController showFlyControls](struct ACPanelController* self, SEL sel)
{
    int64_t v13;
    int64_t var_90 = v13;
    int64_t v12;
    int64_t var_88 = v12;
    int64_t v11;
    int64_t var_80 = v11;
    double v10;
    double var_78 = v10;
    double v9;
    double var_70 = v9;
    int64_t v8;
    int64_t var_68 = v8;
    int64_t x8 = *___stack_chk_guard;
    int128_t var_1e0;
    __builtin_memset(&var_1e0, 0, 0x18);
    int128_t var_1c0;
    __builtin_memset(&var_1c0, 0, 0x20);
    id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIApplication, 
        "sharedApplication"));
    id obj_26 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_1, "connectedScenes"));
    _objc_release(obj_1);
    void var_120;
    id i_2 = _objc_msgSend(obj_26, "countByEnumeratingWithState:objects:count:", &var_1e0, 
        &var_120, 0x10);
    
    if (!i_2)
        _objc_release(obj_26);
    else
    {
        id i_1 = i_2;
        id obj = nullptr;
        int64_t* var_1d0;
        int64_t x19_1 = *var_1d0;
        id i;
        
        do
        {
            int64_t x25_1 = 0;
            
            do
            {
                if (*var_1d0 != x19_1)
                    _objc_enumerationMutation(obj_26);
                
                void* x26_1 = *(*(&var_1e0 + 8) + (x25_1 << 3));
                _objc_msgSend(clsRef_UIWindowScene, "class");
                
                if (_objc_msgSend(x26_1, "isKindOfClass:"))
                {
                    int128_t var_220;
                    __builtin_memset(&var_220, 0, 0x40);
                    id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(x26_1, "windows"));
                    int64_t j_2 =
                        _objc_msgSend(obj_2, "countByEnumeratingWithState:objects:count:");
                    
                    if (j_2)
                    {
                        int64_t j_1 = j_2;
                        int64_t x21 = *0;
                        int64_t j;
                        
                        do
                        {
                            int64_t x19_2 = 0;
                            
                            do
                            {
                                if (*0 != x21)
                                    _objc_enumerationMutation(obj_2);
                                
                                id obj_25 = *(x19_2 << 3);
                                
                                if (_objc_msgSend(obj_25, "isKeyWindow"))
                                {
                                    id obj_27 = _objc_retain(obj_25);
                                    _objc_release(obj);
                                    obj = obj_27;
                                    goto label_420208;
                                }
                                
                                x19_2 += 1;
                            } while (j_1 != x19_2);
                            
                            j = _objc_msgSend(obj_2, "countByEnumeratingWithState:objects:count:");
                            j_1 = j;
                        } while (j);
                    }
                    
                label_420208:
                    _objc_release(obj_2);
                }
                
                x25_1 += 1;
            } while (x25_1 != i_1);
            
            i = _objc_msgSend(obj_26, "countByEnumeratingWithState:objects:count:");
            i_1 = i;
        } while (i);
        _objc_release(obj_26);
        
        if (obj)
        {
            id x0_23 = _objc_alloc(clsRef_UIView);
            _objc_msgSend(obj, "bounds");
            int64_t x2_2;
            int128_t v2_2;
            double v3_1;
            x2_2 = _objc_msgSend(obj, "bounds");
            v2_2 = 0x4051800000000000;
            id obj_3 = _objc_msgSend(x0_23, "initWithFrame:", x2_2);
            _objc_msgSend(obj_3, "setTag:", 0x12fd1);
            id obj_4;
            int64_t x2_3;
            int128_t v0_3;
            int128_t v1_2;
            int128_t v2_3;
            int128_t v3_2;
            obj_4 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, 
                "buttonWithType:", 0));
            v10 = 0x4049000000000000;
            v0_3 = 0.0;
            v1_2 = 0.0;
            v2_3 = 0x4051800000000000;
            v3_2 = v10;
            int64_t x2_4;
            int64_t x3_1;
            int64_t x4_4;
            int64_t x5_1;
            int128_t v0_4;
            int128_t v1_3;
            int128_t v2_4;
            int128_t v3_3;
            x2_4 = _objc_msgSend(obj_4, "setFrame:", x2_3);
            v1_3 = 0.5;
            v0_4 = 0x3fb999999999999a;
            v2_4 = 0x3feccccccccccccd;
            v3_3 = 0x3fe999999999999a;
            int64_t obj_5 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
                "colorWithRed:green:blue:alpha:", x2_4, x3_1, x4_4, x5_1));
            _objc_msgSend(obj_4, "setBackgroundColor:", obj_5);
            _objc_release(obj_5);
            id obj_6;
            int64_t x2_6;
            int128_t v0_5;
            obj_6 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_4, "layer"));
            v0_5 = 12.0;
            _objc_msgSend(obj_6, "setCornerRadius:", x2_6);
            _objc_release(obj_6);
            int64_t x2_7;
            int128_t v0_6;
            x2_7 = _objc_msgSend(obj_4, "setTitle:forState:", &cfstr_?_UP, 0);
            v0_6 = 14.0;
            int64_t obj_7 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
                "boldSystemFontOfSize:", x2_7));
            id obj_8 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_4, "titleLabel"));
            _objc_msgSend(obj_8, "setFont:", obj_7);
            _objc_release(obj_8);
            _objc_release(obj_7);
            _objc_msgSend(obj_4, "addTarget:action:forControlEvents:", self, "flyUpStart", 1);
            _objc_msgSend(obj_4, "addTarget:action:forControlEvents:", self, "flyStop", 0xc0);
            _objc_msgSend(obj_3, "addSubview:", obj_4);
            id obj_9;
            int64_t x2_13;
            int128_t v0_7;
            int128_t v1_4;
            int128_t v2_5;
            int128_t v3_4;
            obj_9 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, 
                "buttonWithType:"));
            v1_4 = 0x404c000000000000;
            v0_7 = 0.0;
            v2_5 = 0x4051800000000000;
            v3_4 = v10;
            int128_t v0_8;
            int128_t v1_5;
            int128_t v2_6;
            int128_t v3_5;
            v0_8 = _objc_msgSend(obj_9, "setFrame:", x2_13);
            v0_8 = 0x3feccccccccccccd;
            v1_5 = 0x3fd3333333333333;
            v2_6 = 0x3fb999999999999a;
            v3_5 = 0x3fe999999999999a;
            int64_t obj_10 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
                "colorWithRed:green:blue:alpha:"));
            _objc_msgSend(obj_9, "setBackgroundColor:", obj_10);
            _objc_release(obj_10);
            id obj_11;
            int64_t x2_15;
            int128_t v0_9;
            obj_11 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_9, "layer"));
            v0_9 = 12.0;
            _objc_msgSend(obj_11, "setCornerRadius:", x2_15);
            _objc_release(obj_11);
            _objc_msgSend(obj_9, "setTitle:forState:");
            int128_t v0_10;
            v0_10 = 14.0;
            id obj_12 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
                "boldSystemFontOfSize:"));
            id obj_13 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_9, "titleLabel"));
            _objc_msgSend(obj_13, "setFont:");
            _objc_release(obj_13);
            _objc_release(obj_12);
            _objc_msgSend(obj_9, "addTarget:action:forControlEvents:", self, "flyDownStart", 1);
            _objc_msgSend(obj_9, "addTarget:action:forControlEvents:", self, "flyStop", 0xc0);
            _objc_msgSend(obj_3, "addSubview:");
            id obj_14;
            int128_t v0_11;
            int128_t v1_6;
            int128_t v2_7;
            int128_t v3_6;
            obj_14 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, 
                "buttonWithType:"));
            v1_6 = 0x405c000000000000;
            v0_11 = 0.0;
            v2_7 = 0x4051800000000000;
            v3_6 = v10;
            int128_t v0_12;
            int128_t v1_7;
            int128_t v2_8;
            int128_t v3_7;
            v0_12 = _objc_msgSend(obj_14, "setFrame:");
            v0_12 = 0x3fc999999999999a;
            v1_7 = 0x3fe6666666666666;
            v2_8 = 0x3fd3333333333333;
            v3_7 = 0x3fe999999999999a;
            id obj_15 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
                "colorWithRed:green:blue:alpha:"));
            _objc_msgSend(obj_14, "setBackgroundColor:");
            _objc_release(obj_15);
            id obj_16;
            int128_t v0_13;
            obj_16 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_14, "layer"));
            v0_13 = 12.0;
            _objc_msgSend(obj_16, "setCornerRadius:");
            _objc_release(obj_16);
            _objc_msgSend(obj_14, "setTitle:forState:");
            int128_t v0_14;
            v0_14 = 14.0;
            id obj_17 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
                "boldSystemFontOfSize:"));
            id obj_18 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_14, "titleLabel"));
            _objc_msgSend(obj_18, "setFont:");
            _objc_release(obj_18);
            _objc_release(obj_17);
            _objc_msgSend(obj_14, "addTarget:action:forControlEvents:");
            _objc_msgSend(obj_14, "addTarget:action:forControlEvents:");
            _objc_msgSend(obj_3, "addSubview:");
            id obj_19;
            int128_t v0_15;
            int128_t v1_8;
            int128_t v2_9;
            int128_t v3_8;
            obj_19 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, 
                "buttonWithType:"));
            v1_8 = 0x4065000000000000;
            v3_8 = 0x4047000000000000;
            v0_15 = 0.0;
            v2_9 = 0x4051800000000000;
            int128_t v0_16;
            int128_t v1_9;
            int128_t v2_10;
            int128_t v3_9;
            v0_16 = _objc_msgSend(obj_19, "setFrame:");
            v0_16 = 0x3fe3333333333333;
            v1_9 = 0x3fd3333333333333;
            v2_10 = 0x3fe999999999999a;
            v3_9 = 0x3fe999999999999a;
            id obj_20 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
                "colorWithRed:green:blue:alpha:"));
            _objc_msgSend(obj_19, "setBackgroundColor:");
            _objc_release(obj_20);
            id obj_21;
            int128_t v0_17;
            obj_21 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_19, "layer"));
            v0_17 = 12.0;
            _objc_msgSend(obj_21, "setCornerRadius:");
            _objc_release(obj_21);
            double v0_18;
            v0_18 = data_446784;
            double var_2c0_1 = v0_18;
            id obj_22 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
                "stringWithFormat:", &cfstr_x%.0f));
            _objc_msgSend(obj_19, "setTitle:forState:");
            _objc_release(obj_22);
            int128_t v0_19;
            v0_19 = 14.0;
            id obj_23 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
                "boldSystemFontOfSize:"));
            id obj_24 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_19, "titleLabel"));
            _objc_msgSend(obj_24, "setFont:");
            _objc_release(obj_24);
            _objc_release(obj_23);
            _objc_msgSend(obj_19, "setTag:");
            _objc_msgSend(obj_19, "addTarget:action:forControlEvents:");
            _objc_msgSend(obj_3, "addSubview:");
            _objc_msgSend(obj, "addSubview:");
            _objc_release(obj_19);
            _objc_release(obj_14);
            _objc_release(obj_9);
            _objc_release(obj_4);
            _objc_release(obj_3);
            _objc_release(obj);
        }
    }
    
    if (*___stack_chk_guard == x8)
        return;
    
    ___stack_chk_fail();
    /* no return */
}

void -[ACPanelController hideFlyControls](struct ACPanelController* self, SEL sel)
{
    int64_t x8 = *___stack_chk_guard;
    int128_t var_1b0;
    __builtin_memset(&var_1b0, 0, 0x18);
    int128_t var_190;
    __builtin_memset(&var_190, 0, 0x20);
    id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIApplication, 
        "sharedApplication"));
    id obj_5 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_1, "connectedScenes"));
    _objc_release(obj_1);
    void var_f0;
    id i_2 =
        _objc_msgSend(obj_5, "countByEnumeratingWithState:objects:count:", &var_1b0, &var_f0, 0x10);
    
    if (!i_2)
        _objc_release(obj_5);
    else
    {
        id i_1 = i_2;
        id obj = nullptr;
        int64_t* var_1a0;
        int64_t x21_1 = *var_1a0;
        id i;
        
        do
        {
            int64_t x25_1 = 0;
            
            do
            {
                if (*var_1a0 != x21_1)
                    _objc_enumerationMutation(obj_5);
                
                void* x26_1 = *(*(&var_1b0 + 8) + (x25_1 << 3));
                _objc_msgSend(clsRef_UIWindowScene, "class");
                
                if (_objc_msgSend(x26_1, "isKindOfClass:"))
                {
                    int128_t var_1f0;
                    __builtin_memset(&var_1f0, 0, 0x40);
                    id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(x26_1, "windows"));
                    int64_t j_2 =
                        _objc_msgSend(obj_2, "countByEnumeratingWithState:objects:count:");
                    
                    if (j_2)
                    {
                        int64_t j_1 = j_2;
                        int64_t x21_2 = *0;
                        int64_t j;
                        
                        do
                        {
                            int64_t x20 = 0;
                            
                            do
                            {
                                if (*0 != x21_2)
                                    _objc_enumerationMutation(obj_2);
                                
                                id obj_4 = *(x20 << 3);
                                
                                if (_objc_msgSend(obj_4, "isKeyWindow"))
                                {
                                    id obj_6 = _objc_retain(obj_4);
                                    _objc_release(obj);
                                    obj = obj_6;
                                    goto label_420c24;
                                }
                                
                                x20 += 1;
                            } while (j_1 != x20);
                            
                            j = _objc_msgSend(obj_2, "countByEnumeratingWithState:objects:count:");
                            j_1 = j;
                        } while (j);
                    }
                    
                label_420c24:
                    _objc_release(obj_2);
                }
                
                x25_1 += 1;
            } while (x25_1 != i_1);
            
            i = _objc_msgSend(obj_5, "countByEnumeratingWithState:objects:count:");
            i_1 = i;
        } while (i);
        _objc_release(obj_5);
        
        if (obj)
        {
            id obj_3 =
                _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj, "viewWithTag:", 0x12fd1));
            _objc_msgSend(obj_3, "removeFromSuperview");
            _objc_release(obj_3);
            _objc_release(obj);
        }
    }
    
    if (*___stack_chk_guard == x8)
        return;
    
    ___stack_chk_fail();
    /* no return */
}

void -[ACPanelController flyUpStart](struct ACPanelController* self, SEL sel)
{
    data_446b2c = data_446784;
    data_446b30 = 0;
}

void -[ACPanelController flyDownStart](struct ACPanelController* self, SEL sel)
{
    data_446b2c = -(data_446784);
    data_446b30 = 0;
}

void -[ACPanelController flyForwardStart](struct ACPanelController* self, SEL sel)
{
    int32_t v0 = data_446784;
    data_446b2c = 0;
    data_446b30 = v0;
}

void -[ACPanelController flyStop](struct ACPanelController* self, SEL sel)
{
    data_446b2c = 0;
    data_446b30 = 0;
}

void -[ACPanelController flyCycleSpeed:](struct ACPanelController* self, SEL sel, id flyCycleSpeed)
{
    float v0 = data_446784;
    float v3 = 2f;
    float v6 = 6f;
    float v17 = 11f;
    float v18 = 21f;
    v0 - v18;
    bool cond:1 = v0 < v18;
    double v19;
    v19 = 1f;
    
    v18 = v0 < v18 ? 0x42480000 : v19;
    
    v19 = cond:1 ? 0x4049000000000000 : 1.0;
    
    v0 - v17;
    float v16;
    
    v16 = v0 < v17 ? 20f : v18;
    
    double v7;
    
    v7 = v0 < v17 ? 20.0 : v19;
    
    v0 - v6;
    float v5;
    
    v5 = v0 < v6 ? 10f : v16;
    
    double v4;
    
    v4 = v0 < v6 ? 10.0 : v7;
    
    v0 - v3;
    bool cond:4 = v0 < v3;
    
    v0 = v0 < v3 ? 5f : v5;
    
    double v8;
    
    v8 = cond:4 ? 5.0 : v4;
    
    data_446784 = v0;
    struct objc_class_t* clsRef_NSString_1 = clsRef_NSString;
    id obj = _objc_retain(flyCycleSpeed);
    double var_60 = v8;
    id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString_1, 
        "stringWithFormat:", &cfstr_x%.0f));
    _objc_msgSend(flyCycleSpeed, "setTitle:forState:", obj_1, 0);
    _objc_release(obj);
    _objc_release(obj_1);
    double v0_1;
    v0_1 = data_446784;
    double var_60_1 = v0_1;
    id x0_8 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
        "stringWithFormat:", &cfstr_Fly_speed:_%.0f));
    sub_410c94(x0_8);
    /* tailcall */
    return _objc_release(x0_8);
}

void -[ACPanelController flyTick](struct ACPanelController* self, SEL sel)
{
    int64_t x8 = *___stack_chk_guard;
    
    if (data_446b2a)
    {
        int32_t v0 = data_446b2c;
        
        if (v0 != 0f)
        {
        label_420ef4:
            int64_t x0 = data_446b38;
            bool z_1;
            
            if (x0)
                z_1 = !data_446b40;
            else
                z_1 = true;
            
            if (!z_1)
            {
                int64_t var_48 = 0;
                int64_t x0_1 = data_446b08(x0, 0, 0, &var_48, v0);
                bool z_2;
                
                z_2 = x0_1 ? !var_48 : false;
                
                if (z_2)
                {
                    var_48 = 0;
                    int64_t x0_3;
                    int128_t v4_1;
                    x0_3 = data_446b08(data_446b40, x0_1, 0, &var_48);
                    bool z_3;
                    
                    z_3 = x0_3 ? !var_48 : false;
                    
                    if (z_3)
                    {
                        float var_50_1 = 0f;
                        int64_t var_58 = 0;
                        int64_t x8_7 = data_446b48;
                        float v0_1;
                        float v1_1;
                        float v2_1;
                        
                        if (!x8_7)
                        {
                            v0_1 = 0f;
                            v1_1 = 0f;
                            v2_1 = 0f;
                        }
                        else
                        {
                            x8_7(x0_3, &var_58);
                            v1_1 = *(&var_58 + 4);
                            v0_1 = var_50_1;
                            v2_1 = var_58 + 0f;
                        }
                        
                        float v3_1 = data_446b2c;
                        v4_1 = 0x3d4ccccd;
                        float temp0_1 = vfma_f32(v1_1, v3_1, 0.0500000007f);
                        var_58 = v2_1;
                        *(&var_58 + 4) = temp0_1;
                        v1_1 = data_446b30;
                        float temp0_2 = vfma_f32(v0_1, v1_1, 0.0500000007f);
                        float var_50_2 = temp0_2;
                        int64_t x8_8 = data_446b50;
                        
                        if (!x8_8)
                        {
                            int64_t x0_7 = data_446b10(data_446b58, "set_position", 1);
                            
                            if (x0_7)
                            {
                                int64_t* var_40 = &var_58;
                                int64_t var_60 = 0;
                                data_446b08(x0_7, x0_3, &var_40, &var_60);
                            }
                        }
                        else
                            x8_8(x0_3, &var_58, temp0_2, v1_1, v2_1, v3_1, v4_1);
                    }
                }
            }
        }
        else
        {
            v0 = data_446b30;
            
            if (!(v0 == 0f))
                goto label_420ef4;
        }
    }
    
    if (*___stack_chk_guard == x8)
        return;
    
    ___stack_chk_fail();
    /* no return */
}

void -[ACPanelController godModeToggleTapped:](struct ACPanelController* self, SEL sel, id godModeToggleTapped)
{
    uint32_t x25 = data_446b60;
    data_446b60 = x25 ^ 1;
    struct objc_class_t* clsRef_UIColor_1 = clsRef_UIColor;
    id obj;
    int64_t x2;
    int64_t x3;
    int64_t x4;
    int64_t x5;
    int128_t v0;
    int128_t v1;
    int128_t v2;
    int128_t v3;
    obj = _objc_retain(godModeToggleTapped);
    
    if (x25)
    {
        v0 = 0x3fe999999999999a;
        v1 = 0x3fe3333333333333;
        v2 = 0x3fb999999999999a;
        v3 = 1.0;
        id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor_1, 
            "colorWithRed:green:blue:alpha:", x2, x3, x4, x5));
        _objc_msgSend(godModeToggleTapped, "setBackgroundColor:", obj_1);
        _objc_release(obj_1);
        int64_t x2_2;
        int64_t x3_1;
        int64_t x4_1;
        int64_t x5_1;
        int128_t v0_1;
        int128_t v1_1;
        int128_t v2_1;
        int128_t v3_1;
        x2_2 = _objc_msgSend(godModeToggleTapped, "setTitle:forState:", &cfstr_??_God_Mode, 0);
        v0_1 = 0x3feb333333333333;
        v1_1 = 0x3feccccccccccccd;
        v2_1 = 1.0;
        v3_1 = 1.0;
        id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
            "colorWithRed:green:blue:alpha:", x2_2, x3_1, x4_1, x5_1));
        _objc_msgSend(godModeToggleTapped, "setTitleColor:forState:", obj_2, 0);
        _objc_release(obj);
        _objc_release(obj_2);
        sub_410c94(&cfstr_God_Mode_DISABLED);
        _objc_msgSend(data_446a70, "invalidate");
        id x0_12 = data_446a70;
        data_446a70 = 0;
        /* tailcall */
        return _objc_release(x0_12);
    }
    
    v1 = 0x3feae147ae147ae1;
    v0 = 1.0;
    v2 = 0.0;
    v3 = 1.0;
    id obj_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor_1, 
        "colorWithRed:green:blue:alpha:", x2, x3, x4, x5));
    _objc_msgSend(godModeToggleTapped, "setBackgroundColor:", obj_3);
    _objc_release(obj_3);
    _objc_msgSend(godModeToggleTapped, "setTitle:forState:", &cfstr_??_God_Mode:_ON, 0);
    id obj_4 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, "blackColor"));
    _objc_msgSend(godModeToggleTapped, "setTitleColor:forState:", obj_4, 0);
    _objc_release(obj);
    _objc_release(obj_4);
    int64_t x4_3;
    int128_t v0_3;
    x4_3 = sub_410c94(&cfstr_God_Mode_ENABLED);
    struct objc_class_t* clsRef_NSTimer_1 = clsRef_NSTimer;
    void* (* const var_78)[0x20] = __NSConcreteStackBlock;
    v0_3 = 0xc2000000;
    int64_t var_70 = 0xc2000000;
    int64_t (* var_68)(void* arg1, id arg2) = sub_4212f0;
    void* const var_60 = &data_43c3e0;
    struct ACPanelController* self_1 = self;
    v0_3 = 0.5;
    id x0_25 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSTimer_1, 
        "scheduledTimerWithTimeInterval:repeats:block:", 1, &var_78, x4_3));
    id obj_5 = data_446a70;
    data_446a70 = x0_25;
    _objc_release(obj_5);
}

int64_t sub_4212f0(void* arg1, id arg2)
{
    if (data_446b60)
        /* tailcall */
        return _objc_msgSend(*(arg1 + 0x20), "godModeTick");
    
    _objc_msgSend(arg2, "invalidate");
    id x0_3 = data_446a70;
    data_446a70 = 0;
    /* tailcall */
    return _objc_release(x0_3);
}

void -[ACPanelController godModeTick](struct ACPanelController* self, SEL sel)
{
    int64_t x8 = *___stack_chk_guard;
    bool z;
    
    if (data_446b60)
        z = !data_446ae8;
    else
        z = true;
    
    if (!z)
    {
        int64_t x19_1 = data_446b68;
        uint32_t var_c0;
        float var_98;
        
        if (x19_1)
        {
            int64_t x0_1 = sub_42172c(x19_1);
            
            if (x0_1)
            {
                for (int64_t i = 0; i != 0x50; i += 8)
                {
                    int64_t x0_3 = data_446b18(x19_1, *(&data_43c4b0 + i));
                    int64_t x0_5 = data_446b18(x19_1, *(&data_43c460 + i));
                    
                    if (x0_5)
                    {
                        var_98 = 100f;
                        
                        if (x0_3)
                        {
                            data_446b20(x0_1, x0_3, &var_98);
                            
                            if (!(var_98 > 0f))
                                var_98 = 100f;
                        }
                        
                        data_446b70(x0_1, x0_5, &var_98);
                        var_c0 = vcvts_s32_f32(var_98);
                        data_446b70(x0_1, x0_5, &var_c0);
                    }
                }
            }
        }
        
        for (int64_t i_1 = 0; i_1 != 0xa; i_1 += 1)
        {
            int64_t x0_9 = data_446ae8;
            
            if (x0_9)
            {
                int64_t x22_2 = (&data_43c410)[i_1];
                int64_t x0_10 = data_446ae0(x0_9, &cstr_, x22_2);
                int64_t x21_2 = x0_10;
                int64_t x0_12;
                
                if (!x0_10)
                {
                    x0_12 = data_446ae0(data_446ae8, "AnimalCompany", x22_2);
                    x21_2 = x0_12;
                }
                
                if (x0_10 || x0_12)
                {
                    int64_t x0_14 = sub_42172c(x21_2);
                    
                    if (x0_14)
                    {
                        for (int64_t j = 0; j != 0x50; j += 8)
                        {
                            int64_t x0_16 = data_446b18(x21_2, *(&data_43c4b0 + j));
                            int64_t x0_18 = data_446b18(x21_2, *(&data_43c460 + j));
                            
                            if (x0_18)
                            {
                                var_98 = 100f;
                                
                                if (x0_16)
                                {
                                    data_446b20(x0_14, x0_16, &var_98);
                                    
                                    if (!(var_98 > 0f))
                                        var_98 = 100f;
                                }
                                
                                data_446b70(x0_14, x0_18, &var_98);
                                var_c0 = vcvts_s32_f32(var_98);
                                data_446b70(x0_14, x0_18, &var_c0);
                            }
                        }
                        
                        char const* const x23_2 = "Heal";
                        var_98 = "Heal";
                        char const* const var_90_1 = "FullHeal";
                        char const* const var_88_1 = "SetHealth";
                        char const* const var_80_1 = "ResetHealth";
                        int64_t x24_2 = 8;
                        char const* const var_78_1 = "SetInvincible";
                        char const* const var_70_1 = "SetGodMode";
                        int64_t var_d0;
                        
                        while (true)
                        {
                            int64_t x0_23 = data_446b10(x21_2, x23_2, 0);
                            
                            if (x0_23)
                            {
                                var_c0 = 0;
                                data_446b08(x0_23, x0_14, 0, &var_c0);
                            }
                            
                            int64_t x0_25 = data_446b10(x21_2, x23_2, 1);
                            
                            if (x0_25)
                            {
                                int32_t var_c4 = 0x461c3c00;
                                var_c0 = &var_c4;
                                var_d0 = 0;
                                data_446b08(x0_25, x0_14, &var_c0, &var_d0);
                            }
                            
                            if (x24_2 == 0x30)
                                break;
                            
                            x23_2 = *(&var_98 + x24_2);
                            x24_2 += 8;
                        }
                        
                        int64_t x23_3 = 0;
                        var_c0 = "invincible";
                        char const* const var_b8 = "isInvincible";
                        char const* const var_b0_1 = "godMode";
                        char const* const var_a8_1 = "isGodMode";
                        char const* const var_a0_1 = "immortal";
                        
                        while (true)
                        {
                            int64_t x0_27 = data_446b18(x21_2);
                            
                            if (x0_27)
                            {
                                var_d0 = 1;
                                data_446b70(x0_14, x0_27, &var_d0);
                            }
                            
                            if (x23_3 == 0x20)
                                break;
                            
                            x23_3 += 8;
                        }
                    }
                }
            }
        }
    }
    
    if (*___stack_chk_guard == x8)
        return;
    
    ___stack_chk_fail();
    /* no return */
}

void sub_42172c(int64_t arg1)
{
    int64_t x8 = *___stack_chk_guard;
    
    if (arg1 && data_446af8())
    {
        arg1 = data_446b00();
        
        if (arg1)
        {
            int64_t var_28 = 0;
            int64_t x0 = data_446bd0;
            
            if (x0)
            {
                int64_t var_20 = arg1;
                data_446b08(x0, 0, &var_20, &var_28);
            }
        }
    }
    
    if (*___stack_chk_guard == x8)
        return;
    
    ___stack_chk_fail();
    /* no return */
}

void -[ACPanelController vrPlatformTapped](struct ACPanelController* self, SEL sel)
{
    int64_t v12;
    int64_t var_58 = v12;
    int64_t v11;
    int64_t var_50 = v11;
    int64_t v10;
    int64_t var_48 = v10;
    int64_t v9;
    int64_t var_40 = v9;
    int64_t v8;
    int64_t var_38 = v8;
    uint32_t x9 = data_446b78;
    data_446b78 = x9 ^ 1;
    
    if (x9)
    {
        sub_410c94(&cfstr_VR_Platform_OFF);
        id x0 = data_446a08;
        
        if (x0)
        {
            _objc_msgSend(x0, "invalidate");
            id x0_1 = data_446a08;
            data_446a08 = 0;
            /* tailcall */
            return _objc_release(x0_1);
        }
        
        return;
    }
    
    sub_410c94(&cfstr_VR_Platform_ON_?_planks_follow_your_feet!);
    id var_68;
    _objc_initWeak(&var_68, self);
    struct objc_class_t* clsRef_NSTimer_1 = clsRef_NSTimer;
    void* (* const var_90)[0x20] = __NSConcreteStackBlock;
    int64_t var_88_1 = 0xc2000000;
    int64_t (* var_80_1)(void* arg1, id arg2) = sub_4219ac;
    void* const var_78_1 = &data_43c3b0;
    id var_70;
    int64_t x4_2;
    int128_t v0_2;
    x4_2 = _objc_copyWeak(&var_70, &var_68);
    v0_2 = 0x3fe999999999999a;
    id x0_7 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSTimer_1, 
        "scheduledTimerWithTimeInterval:repeats:block:", 1, &var_90, x4_2));
    id obj = data_446a08;
    data_446a08 = x0_7;
    _objc_release(obj);
    float v0_3;
    int32_t v1_2;
    int32_t v2_2;
    v0_3 = sub_4113d8();
    v8 = v0_3;
    v9 = v2_2;
    v10 = v1_2 + -0.5f;
    
    for (int32_t i = -1; i != 2; i += 1)
    {
        v11 = vfma_f32(v8, i, 0.699999988f);
        
        for (int32_t j = -1; j != 2; j += 1)
        {
            vfma_f32(v9, j, 0.699999988f);
            sub_4114c8(&cfstr_item_plank, v11);
        }
    }
    
    _objc_destroyWeak(&var_70);
    _objc_destroyWeak(&var_68);
}

int64_t sub_421988(struct _Unwind_Exception* arg1, id* arg2 @ x19)
{
    _objc_destroyWeak(arg2);
    void location;
    _objc_destroyWeak(&location);
    void* x0_3;
    id x1;
    x0_3 = __Unwind_Resume(arg1);
    /* tailcall */
    return sub_4219ac(x0_3, x1);
}

int64_t sub_4219ac(void* arg1, id arg2)
{
    int64_t v12;
    int64_t var_58 = v12;
    int64_t v11;
    int64_t var_50 = v11;
    int64_t v10;
    int64_t var_48 = v10;
    int64_t v9;
    int64_t var_40 = v9;
    int64_t v8;
    int64_t var_38 = v8;
    id x0_1 = _objc_retain(arg2);
    _objc_release(_objc_loadWeakRetained(arg1 + 0x20));
    
    if (!data_446b78)
    {
        _objc_msgSend(x0_1, "invalidate");
        id obj = data_446a08;
        data_446a08 = 0;
        _objc_release(obj);
    }
    else
    {
        float v0_1;
        int32_t v1_1;
        int32_t v2_1;
        v0_1 = sub_4113d8();
        v8 = v0_1;
        v9 = v2_1;
        v10 = v1_1 + -0.5f;
        
        for (int32_t i = -1; i != 2; i += 1)
        {
            v11 = vfma_f32(v8, i, 0.699999988f);
            
            for (int32_t j = -1; j != 2; j += 1)
            {
                vfma_f32(v9, j, 0.699999988f);
                sub_4114c8(&cfstr_item_plank, v11);
            }
        }
    }
    
    /* tailcall */
    return _objc_release(x0_1);
}

void -[ACPanelController extraExpTapped:](struct ACPanelController* self, SEL sel, id extraExpTapped)
{
    int64_t v14;
    int64_t var_98 = v14;
    int64_t v13;
    int64_t var_90 = v13;
    double v12;
    double var_88 = v12;
    double v11;
    double var_80 = v11;
    int64_t x8 = *___stack_chk_guard;
    id x0_1 = _objc_msgSend(extraExpTapped, "tag");
    int32_t v0;
    int32_t v1;
    int32_t v2;
    double v8;
    double v9;
    v0 = sub_4113d8();
    v9 = v0;
    int64_t v10;
    v10 = v1;
    int64_t v15;
    v15 = v2;
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "selectedItemNameOrDefault"));
    
    if (x0_1 - 0xfa0 > 0x1d)
    {
        void* __offset(objc_object, -0xf9f) var_820_1 = x0_1 - 0xf9f;
        id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
            "stringWithFormat:", &cfstr_Experiment_%ld_fired!));
        sub_410c94(obj_1);
        _objc_release(obj_1);
        v10 = v10 + 5f;
        int32_t i_31 = 0x14;
        v8 = -5f;
        v12 = v9;
        int32_t i;
        
        do
        {
            v9 = 0x42c80000;
            v11 = _arc4random_uniform(0x3e8) / v9 + v8;
            uint32_t x0_12;
            int128_t v2_1;
            x0_12 = _arc4random_uniform(0x3e8);
            v2_1 = v15 + x0_12 / v9 + v8;
            sub_4114c8(obj, v12 + v11);
            i = i_31;
            i_31 -= 1;
        } while (i != 1);
    }
    else
    {
        v14 = v9;
        int32_t var_7e0;
        int64_t var_7d8;
        int32_t var_7d0;
        id obj_36;
        
        switch (x0_1)
        {
            case 0xfa0:
            {
                sub_410c94(&cfstr_Crossbow_Rain!);
                float v0_1 = v10 + 15f;
                v11 = 0.0;
                int32_t i_33 = 0x19;
                v13 = -10f;
                int32_t i_1;
                
                do
                {
                    v8 = 0x42c80000;
                    v10 = _arc4random_uniform(0x7d0) / v8 + v13;
                    uint32_t x0_5;
                    double v0_3;
                    x0_5 = _arc4random_uniform(0x7d0);
                    v0_3 = x0_5;
                    v0_3 = v0_3 / v8;
                    v0_3 = v0_3 + v13;
                    v8 = v9 + v10;
                    v10 = v15 + v0_3;
                    dispatch_time_t when =
                        _dispatch_time(0, vcvtd_s64_f64(v11 * 0.080000000000000002 * 1000000000.0));
                    _objc_retainAutorelease(__dispatch_main_q);
                    void* (* const var_400)[0x20] = __NSConcreteStackBlock;
                    int64_t var_3f8_1 = 0xc0000000;
                    int64_t (* var_3f0_1)(void* arg1) = sub_4242d4;
                    void* const var_3e8_1 = &data_43c190;
                    int32_t var_3e0_1 = v8;
                    float var_3dc_1 = v0_1;
                    int32_t var_3d8_1 = v10;
                    _dispatch_after(when, __dispatch_main_q, &var_400);
                    v11 = v11 + 1.0;
                    i_1 = i_33;
                    i_33 -= 1;
                } while (i_1 != 1);
                break;
            }
            case 0xfa1:
            {
                sub_410c94(&cfstr_RPG_Barrage!);
                float v0_9 = v10 + 12f;
                v11 = 0.0;
                int32_t i_34 = 0x14;
                v13 = -8f;
                int32_t i_2;
                
                do
                {
                    v8 = 0x42c80000;
                    v10 = _arc4random_uniform(0x640) / v8 + v13;
                    uint32_t x0_15;
                    double v0_11;
                    x0_15 = _arc4random_uniform(0x640);
                    v0_11 = x0_15;
                    v0_11 = v0_11 / v8;
                    v0_11 = v0_11 + v13;
                    v8 = v9 + v10;
                    v10 = v15 + v0_11;
                    dispatch_time_t when_1 =
                        _dispatch_time(0, vcvtd_s64_f64(v11 * 0.10000000000000001 * 1000000000.0));
                    _objc_retainAutorelease(__dispatch_main_q);
                    void* (* const var_430)[0x20] = __NSConcreteStackBlock;
                    int64_t var_428_1 = 0xc0000000;
                    int64_t (* var_420_1)(void* arg1) = sub_4242e8;
                    void* const var_418_1 = &data_43c190;
                    int32_t var_410_1 = v8;
                    float var_40c_1 = v0_9;
                    int32_t var_408_1 = v10;
                    _dispatch_after(when_1, __dispatch_main_q, &var_430);
                    v11 = v11 + 1.0;
                    i_2 = i_34;
                    i_34 -= 1;
                } while (i_2 != 1);
                break;
            }
            case 0xfa2:
            {
                sub_410c94(&cfstr_Snowball_Fight!);
                v11 = 0.0;
                int32_t i_35 = 0x28;
                var_7d0 = 0x3fa999999999999a;
                int32_t i_3;
                
                do
                {
                    v8 = 0x42c80000;
                    v13 = -5f;
                    v12 = _arc4random_uniform(0x3e8) / v8 + v13;
                    v13 = _arc4random_uniform(0x3e8) / v8 + v13;
                    uint32_t x0_20;
                    double v0_16;
                    x0_20 = _arc4random_uniform(0x1f4);
                    v0_16 = x0_20;
                    v0_16 = v0_16 / v8;
                    v8 = v9 + v12;
                    v12 = v10 + v0_16;
                    v13 = v15 + v13;
                    dispatch_time_t when_2 =
                        _dispatch_time(0, vcvtd_s64_f64(v11 * 0.050000000000000003 * 1000000000.0));
                    _objc_retainAutorelease(__dispatch_main_q);
                    void* (* const var_460)[0x20] = __NSConcreteStackBlock;
                    int64_t var_458_1 = 0xc0000000;
                    int64_t (* var_450_1)(void* arg1) = sub_4242fc;
                    void* const var_448_1 = &data_43c190;
                    int32_t var_440_1 = v8;
                    int32_t var_43c_1 = v12;
                    int32_t var_438_1 = v13;
                    _dispatch_after(when_2, __dispatch_main_q, &var_460);
                    v11 = v11 + 1.0;
                    i_3 = i_35;
                    i_35 -= 1;
                } while (i_3 != 1);
                break;
            }
            case 0xfa3:
            {
                sub_410c94(&cfstr_Weapon_Cache!);
                struct __NSConstantString* const var_100 = &cfstr_item_shotgun;
                struct __NSConstantString* const var_f8_1 = &cfstr_item_revolver;
                struct __NSConstantString* const var_f0_1 = &cfstr_item_rpg;
                struct __NSConstantString* const var_e8_1 = &cfstr_item_crossbow;
                struct __NSConstantString* const var_e0_1 = &cfstr_item_flamethrower;
                struct __NSConstantString* const var_d8_1 = &cfstr_item_grenade_launcher;
                struct __NSConstantString* const var_d0_1 = &cfstr_item_demon_sword;
                struct __NSConstantString* const var_c8_1 = &cfstr_item_great_sword;
                struct __NSConstantString* const var_c0_1 = &cfstr_item_alphablade;
                struct __NSConstantString* const var_b8_1 = &cfstr_item_pistol_dragon;
                id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
                    "arrayWithObjects:count:", &var_100, 0xa));
                
                if (_objc_msgSend(obj_2, "count") >= 1)
                {
                    int64_t i_4 = 0;
                    v10 = v10 + 1f;
                    v8 = -2f;
                    int32_t x0_32;
                    
                    do
                    {
                        v11 = 0x42c80000;
                        v12 = _arc4random_uniform(0x190) / v11 + v8;
                        float v0_20 = _arc4random_uniform(0x190) / v11 + v8;
                        v11 = v9 + v12;
                        v12 = v15 + v0_20;
                        id obj_3;
                        int128_t v1_2;
                        int128_t v2_2;
                        obj_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_2, 
                            "objectAtIndexedSubscript:", i_4));
                        v1_2 = v10;
                        v2_2 = v12;
                        sub_4114c8(obj_3, v11);
                        _objc_release(obj_3);
                        i_4 += 1;
                        x0_32 = _objc_msgSend(obj_2, "count");
                    } while (i_4 < x0_32);
                }
                
                _objc_release(obj_2);
                break;
            }
            case 0xfa4:
            {
                sub_410c94(&cfstr_Loot_Explosion!);
                int32_t i_5 = 0;
                v12 = 0.0;
                var_7d0 = 0x400921fb54442d18;
                
                do
                {
                    double v0_22;
                    v0_22 = i_5;
                    v0_22 = v0_22 / 30f;
                    v0_22 = v0_22 + v0_22;
                    v11 = v0_22 * 3.1415926535897931;
                    v8 = 0x42c80000;
                    v13 = _arc4random_uniform(0x1f4) / v8 + 1f;
                    v8 = _arc4random_uniform(0x320) / v8;
                    int32_t v0_25;
                    int32_t v1_5;
                    v0_25 = ___sincosf_stret(v11);
                    v11 = vfma_f32(v9, v1_5, v13);
                    v8 = v10 + v8;
                    v13 = vfma_f32(v15, v0_25, v13);
                    id x23_1 = data_446a88;
                    id obj_4 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(x23_1, 
                        "objectAtIndexedSubscript:", 
                        _arc4random_uniform(_objc_msgSend(x23_1, "count"))));
                    dispatch_time_t when_3 =
                        _dispatch_time(0, vcvtd_s64_f64(v12 * 0.029999999999999999 * 1000000000.0));
                    _objc_retainAutorelease(__dispatch_main_q);
                    void* (* const var_498)[0x20] = __NSConcreteStackBlock;
                    int64_t var_490_1 = 0xc2000000;
                    int64_t (* var_488_1)(void* arg1) = sub_424310;
                    void* const var_480_1 = &data_43c130;
                    int32_t var_470_1 = v11;
                    int32_t var_46c_1 = v8;
                    int32_t var_468_1 = v13;
                    id obj_5 = _objc_retain(obj_4);
                    _dispatch_after(when_3, __dispatch_main_q, &var_498);
                    _objc_release(obj_4);
                    _objc_release(obj_5);
                    v12 = v12 + 1.0;
                    i_5 += 1;
                } while (i_5 != 0x1e);
                break;
            }
            case 0xfa5:
            {
                sub_410c94(&cfstr_Diamond_Shower!);
                struct __NSConstantString* const var_128 = &cfstr_item_ruby;
                struct __NSConstantString* const var_120_1 = &cfstr_item_goldbar;
                struct __NSConstantString* const var_118_1 = &cfstr_item_goldcoin;
                struct __NSConstantString* const var_110_1 = &cfstr_item_diamond_jade_koi;
                struct __NSConstantString* const var_108_1 = &cfstr_item_ore_gold_l;
                obj_36 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
                    "arrayWithObjects:count:", &var_128, 5));
                float v0_27 = v10 + 15f;
                v11 = 0.0;
                int32_t i_39 = 0x1e;
                v12 = v9;
                v9 = v15;
                v13 = -10f;
                int32_t i_6;
                
                do
                {
                    v8 = 0x42c80000;
                    v10 = _arc4random_uniform(0x7d0) / v8 + v13;
                    float v0_29 = _arc4random_uniform(0x7d0) / v8 + v13;
                    v8 = v12 + v10;
                    v10 = v9 + v0_29;
                    id obj_6 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_36, 
                        "objectAtIndexedSubscript:", 
                        _arc4random_uniform(_objc_msgSend(obj_36, "count"))));
                    dispatch_time_t when_4 =
                        _dispatch_time(0, vcvtd_s64_f64(v11 * 0.059999999999999998 * 1000000000.0));
                    _objc_retainAutorelease(__dispatch_main_q);
                    void* (* const var_4d0)[0x20] = __NSConcreteStackBlock;
                    int64_t var_4c8_1 = 0xc2000000;
                    int64_t (* var_4c0_1)(void* arg1) = sub_424324;
                    void* const var_4b8_1 = &data_43c130;
                    int32_t var_4a8_1 = v8;
                    float var_4a4_1 = v0_27;
                    int32_t var_4a0_1 = v10;
                    id obj_7 = _objc_retain(obj_6);
                    _dispatch_after(when_4, __dispatch_main_q, &var_4d0);
                    _objc_release(obj_6);
                    _objc_release(obj_7);
                    v11 = v11 + 1.0;
                    i_6 = i_39;
                    i_39 -= 1;
                } while (i_6 != 1);
                _objc_release(obj_36);
                break;
            }
            case 0xfa6:
            {
                sub_410c94(&cfstr_Fire_Ring!);
                int32_t i_7 = 0;
                double v0_33;
                v0_33 = 0.5f;
                v10 = v10 + v0_33;
                v11 = 4f;
                
                do
                {
                    v0_33 = i_7;
                    v0_33 = v0_33 * 0x3d800000;
                    v0_33 = v0_33 + v0_33;
                    v0_33 = v0_33 * 3.1415926535897931;
                    int32_t v0_34;
                    int32_t v1_7;
                    int128_t v2_3;
                    v0_34 = ___sincosf_stret(v0_33);
                    int32_t temp0_3 = vfma_f32(v9, v1_7, v11);
                    v2_3 = vfma_f32(v15, v0_34, v11);
                    sub_4114c8(&cfstr_item_flamethrower, temp0_3);
                    i_7 += 1;
                } while (i_7 != 0x10);
                break;
            }
            case 0xfa7:
            {
                sub_410c94(&cfstr_Tsunami_Wall!);
                int32_t i_8 = 0;
                float v1_8 = v9;
                v9 = v15 + 5f;
                v8 = -5f;
                v12 = 0.5f;
                
                do
                {
                    int32_t j = 0;
                    v11 = v1_8 + i_8 + v8;
                    
                    do
                    {
                        vfma_f32(v10, j, v12);
                        int128_t v2_4;
                        v2_4 = v9;
                        sub_4114c8(&cfstr_item_metal_plate, v11);
                        j += 1;
                    } while (j != 5);
                    
                    i_8 += 1;
                    v1_8 = v14;
                } while (i_8 != 0xa);
                break;
            }
            case 0xfa8:
            {
                sub_410c94(&cfstr_Jetpack_Rain!);
                float v0_36 = v10 + 10f;
                v11 = 0.0;
                int32_t i_36 = 0xf;
                v13 = -8f;
                int32_t i_9;
                
                do
                {
                    v8 = 0x42c80000;
                    v10 = _arc4random_uniform(0x640) / v8 + v13;
                    uint32_t x0_61;
                    double v0_38;
                    x0_61 = _arc4random_uniform(0x640);
                    v0_38 = x0_61;
                    v0_38 = v0_38 / v8;
                    v0_38 = v0_38 + v13;
                    v8 = v9 + v10;
                    v10 = v15 + v0_38;
                    dispatch_time_t when_5 =
                        _dispatch_time(0, vcvtd_s64_f64(v11 * 0.10000000000000001 * 1000000000.0));
                    _objc_retainAutorelease(__dispatch_main_q);
                    void* (* const var_500)[0x20] = __NSConcreteStackBlock;
                    int64_t var_4f8_1 = 0xc0000000;
                    int64_t (* var_4f0_1)(void* arg1) = sub_424338;
                    void* const var_4e8_1 = &data_43c190;
                    int32_t var_4e0_1 = v8;
                    float var_4dc_1 = v0_36;
                    int32_t var_4d8_1 = v10;
                    _dispatch_after(when_5, __dispatch_main_q, &var_500);
                    v11 = v11 + 1.0;
                    i_9 = i_36;
                    i_36 -= 1;
                } while (i_9 != 1);
                break;
            }
            case 0xfa9:
            {
                sub_410c94(&cfstr_Ball_Pit!);
                struct __NSConstantString* const var_150 = &cfstr_item_football;
                struct __NSConstantString* const var_148_1 = &cfstr_item_d20;
                struct __NSConstantString* const var_140_1 = &cfstr_item_metal_ball;
                struct __NSConstantString* const var_138_1 = &cfstr_item_egg;
                struct __NSConstantString* const var_130_1 = &cfstr_item_coconut_shell;
                obj_36 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
                    "arrayWithObjects:count:", &var_150, 5));
                float v0_41 = v10 + 5f;
                v11 = 0.0;
                int32_t i_40 = 0x28;
                int32_t i_10;
                
                do
                {
                    v8 = 0x42c80000;
                    v12 = -3f;
                    v10 = _arc4random_uniform(0x258) / v8 + v12;
                    v12 = _arc4random_uniform(0x258) / v8 + v12;
                    v10 = v9 + v10;
                    v8 = v0_41 + _arc4random_uniform(0x1f4) / v8;
                    v12 = v15 + v12;
                    id obj_8 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_36, 
                        "objectAtIndexedSubscript:", 
                        _arc4random_uniform(_objc_msgSend(obj_36, "count"))));
                    dispatch_time_t when_6 =
                        _dispatch_time(0, vcvtd_s64_f64(v11 * 0.040000000000000001 * 1000000000.0));
                    _objc_retainAutorelease(__dispatch_main_q);
                    void* (* const var_538)[0x20] = __NSConcreteStackBlock;
                    int64_t var_530_1 = 0xc2000000;
                    int64_t (* var_528_1)(void* arg1) = sub_42434c;
                    void* const var_520_1 = &data_43c130;
                    int32_t var_510_1 = v10;
                    int32_t var_50c_1 = v8;
                    int32_t var_508_1 = v12;
                    id obj_9 = _objc_retain(obj_8);
                    _dispatch_after(when_6, __dispatch_main_q, &var_538);
                    _objc_release(obj_8);
                    _objc_release(obj_9);
                    v11 = v11 + 1.0;
                    i_10 = i_40;
                    i_40 -= 1;
                } while (i_10 != 1);
                _objc_release(obj_36);
                break;
            }
            case 0xfaa:
            {
                sub_410c94(&cfstr_Magnet_Pull!);
                int32_t i_11 = 0;
                double v0_47;
                v0_47 = 1f;
                v10 = v10 + v0_47;
                double v1_10 = 0.0;
                var_7d8 = 0xbf99999a;
                float v4_1 = 0.125f;
                v11 = v9;
                v13 = v15;
                
                do
                {
                    int32_t j_1 = 0;
                    v0_47 = i_11;
                    v15 = vfma_f32(5f, v0_47, -1.20000005f);
                    var_7d0 = v1_10;
                    uint64_t delta = vcvtd_s64_f64(v1_10 * 0.29999999999999999 * 1000000000.0);
                    
                    do
                    {
                        v0_47 = j_1;
                        v0_47 = v0_47 * v4_1;
                        v0_47 = v0_47 + v0_47;
                        v0_47 = v0_47 * 3.1415926535897931;
                        int32_t v0_48;
                        int32_t v1_11;
                        v0_48 = ___sincosf_stret(v0_47);
                        v8 = vfma_f32(v11, v1_11, v15);
                        v9 = vfma_f32(v13, v0_48, v15);
                        dispatch_time_t when_7 = _dispatch_time(0, delta);
                        _objc_retainAutorelease(__dispatch_main_q);
                        void* (* const var_570)[0x20] = __NSConcreteStackBlock;
                        int64_t var_568_1 = 0xc2000000;
                        int64_t (* var_560_1)(void* arg1) = sub_424360;
                        void* const var_558_1 = &data_43c130;
                        id obj_10 = _objc_retain(obj);
                        int32_t var_548_1 = v8;
                        int32_t var_544_1 = v10;
                        int32_t var_540_1 = v9;
                        _dispatch_after(when_7, __dispatch_main_q, &var_570);
                        _objc_release(obj_10);
                        v4_1 = 0.125f;
                        j_1 += 1;
                    } while (j_1 != 8);
                    
                    v1_10 = var_7d0 + 1.0;
                    i_11 += 1;
                } while (i_11 != 4);
                break;
            }
            case 0xfab:
            {
                sub_410c94(&cfstr_Boombox_Party!);
                int32_t i_12 = 0;
                double v0_49;
                v0_49 = 0.5f;
                v10 = v10 + v0_49;
                v8 = 12f;
                v12 = 3f;
                
                do
                {
                    v0_49 = i_12;
                    v0_49 = v0_49 / v8;
                    v0_49 = v0_49 + v0_49;
                    v0_49 = v0_49 * 3.1415926535897931;
                    int32_t v0_50;
                    int32_t v1_12;
                    int128_t v2_5;
                    v0_50 = ___sincosf_stret(v0_49);
                    int32_t temp0_9 = vfma_f32(v9, v1_12, v12);
                    v2_5 = vfma_f32(v15, v0_50, v12);
                    struct __NSConstantString* const x0_84;
                    
                    x0_84 = !(i_12 & 1) ? &cfstr_item_boombox : &cfstr_item_boombox_neon;
                    
                    sub_4114c8(x0_84, temp0_9);
                    i_12 += 1;
                } while (i_12 != 0xc);
                break;
            }
            case 0xfac:
            {
                sub_410c94(&cfstr_Potion_Storm!);
                struct __NSConstantString* const var_180 = &cfstr_item_bloodlust_vial;
                struct __NSConstantString* const var_178_1 = &cfstr_item_hot_cocoa;
                struct __NSConstantString* const var_170_1 = &cfstr_item_ac_cola;
                struct __NSConstantString* const var_168_1 = &cfstr_item_cola;
                struct __NSConstantString* const var_160_1 = &cfstr_item_cola_large;
                struct __NSConstantString* const var_158_1 = &cfstr_item_big_cup;
                obj_36 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
                    "arrayWithObjects:count:", &var_180, 6));
                float v0_51 = v10 + 10f;
                v11 = 0.0;
                int32_t i_41 = 0x19;
                v10 = v9;
                v13 = -7f;
                int32_t i_13;
                
                do
                {
                    v8 = 0x42c80000;
                    v9 = _arc4random_uniform(0x578) / v8 + v13;
                    float v0_53 = _arc4random_uniform(0x578) / v8 + v13;
                    v8 = v10 + v9;
                    v9 = v15 + v0_53;
                    id obj_11 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_36, 
                        "objectAtIndexedSubscript:", 
                        _arc4random_uniform(_objc_msgSend(obj_36, "count"))));
                    dispatch_time_t when_8 =
                        _dispatch_time(0, vcvtd_s64_f64(v11 * 0.070000000000000007 * 1000000000.0));
                    _objc_retainAutorelease(__dispatch_main_q);
                    void* (* const var_5a8)[0x20] = __NSConcreteStackBlock;
                    int64_t var_5a0_1 = 0xc2000000;
                    int64_t (* var_598_1)(void* arg1) = sub_424374;
                    void* const var_590_1 = &data_43c130;
                    int32_t var_580_1 = v8;
                    float var_57c_1 = v0_51;
                    int32_t var_578_1 = v9;
                    id obj_12 = _objc_retain(obj_11);
                    _dispatch_after(when_8, __dispatch_main_q, &var_5a8);
                    _objc_release(obj_11);
                    _objc_release(obj_12);
                    v11 = v11 + 1.0;
                    i_13 = i_41;
                    i_41 -= 1;
                } while (i_13 != 1);
                _objc_release(obj_36);
                break;
            }
            case 0xfad:
            {
                sub_410c94(&cfstr_Arrow_Rain!);
                struct __NSConstantString* const var_1a8 = &cfstr_item_arrow;
                struct __NSConstantString* const var_1a0_1 = &cfstr_item_arrow_bomb;
                struct __NSConstantString* const var_198_1 = &cfstr_item_arrow_heart;
                struct __NSConstantString* const var_190_1 = &cfstr_item_arrow_lightbulb;
                struct __NSConstantString* const var_188_1 = &cfstr_item_arrow_teleport;
                obj_36 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
                    "arrayWithObjects:count:", &var_1a8, 5));
                float v0_57 = v10 + 20f;
                v11 = 0.0;
                int32_t i_42 = 0x23;
                v10 = v9;
                v13 = -10f;
                int32_t i_14;
                
                do
                {
                    v8 = 0x42c80000;
                    v9 = _arc4random_uniform(0x7d0) / v8 + v13;
                    float v0_59 = _arc4random_uniform(0x7d0) / v8 + v13;
                    v8 = v10 + v9;
                    v9 = v15 + v0_59;
                    id obj_13 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_36, 
                        "objectAtIndexedSubscript:", 
                        _arc4random_uniform(_objc_msgSend(obj_36, "count"))));
                    dispatch_time_t when_9 =
                        _dispatch_time(0, vcvtd_s64_f64(v11 * 0.050000000000000003 * 1000000000.0));
                    _objc_retainAutorelease(__dispatch_main_q);
                    void* (* const var_5e0)[0x20] = __NSConcreteStackBlock;
                    int64_t var_5d8_1 = 0xc2000000;
                    int64_t (* var_5d0_1)(void* arg1) = sub_424388;
                    void* const var_5c8_1 = &data_43c130;
                    int32_t var_5b8_1 = v8;
                    float var_5b4_1 = v0_57;
                    int32_t var_5b0_1 = v9;
                    id obj_14 = _objc_retain(obj_13);
                    _dispatch_after(when_9, __dispatch_main_q, &var_5e0);
                    _objc_release(obj_13);
                    _objc_release(obj_14);
                    v11 = v11 + 1.0;
                    i_14 = i_42;
                    i_42 -= 1;
                } while (i_14 != 1);
                _objc_release(obj_36);
                break;
            }
            case 0xfae:
            {
                sub_410c94(&cfstr_Sword_Circle!);
                struct __NSConstantString* const var_1e0 = &cfstr_item_demon_sword;
                struct __NSConstantString* const var_1d8_1 = &cfstr_item_great_sword;
                struct __NSConstantString* const var_1d0_1 = &cfstr_item_alphablade;
                struct __NSConstantString* const var_1c8_1 = &cfstr_item_stellarsword_blue;
                struct __NSConstantString* const var_1c0_1 = &cfstr_item_stellarsword_gold;
                struct __NSConstantString* const var_1b8_1 = &cfstr_item_hookshot_sword;
                struct __NSConstantString* const var_1b0_1 = &cfstr_item_lance;
                id obj_15 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
                    "arrayWithObjects:count:", &var_1e0, 7));
                
                if (_objc_msgSend(obj_15, "count") >= 1)
                {
                    int64_t i_15 = 0;
                    v10 = v10 + 1.5f;
                    v14 = 3f;
                    int32_t x8_4;
                    
                    do
                    {
                        v8 = i_15;
                        id x0_119;
                        double v0_64;
                        x0_119 = _objc_msgSend(obj_15, "count");
                        v0_64 = x0_119;
                        v0_64 = v0_64 + v0_64;
                        v0_64 = v8 / v0_64;
                        v0_64 = v0_64 + v0_64;
                        v0_64 = v0_64 * 3.1415926535897931;
                        int32_t v0_65;
                        int32_t v1_13;
                        v0_65 = ___sincosf_stret(v0_64);
                        v11 = vfma_f32(v9, v1_13, v14);
                        v12 = vfma_f32(v15, v0_65, v14);
                        id x0_121 = _objc_msgSend(obj_15, "count");
                        id obj_16;
                        int128_t v1_14;
                        int128_t v2_6;
                        obj_16 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_15, 
                            "objectAtIndexedSubscript:", i_15 % x0_121));
                        v1_14 = v10;
                        v2_6 = v12;
                        sub_4114c8(obj_16, v11);
                        _objc_release(obj_16);
                        i_15 += 1;
                        x8_4 = _objc_msgSend(obj_15, "count") << 1;
                    } while (i_15 < x8_4);
                }
                
                _objc_release(obj_15);
                break;
            }
            case 0xfaf:
            {
                sub_410c94(&cfstr_Money_Rain!);
                int32_t i_16 = 0;
                v9 = 0.0;
                
                do
                {
                    v15 = 0xc2c80000;
                    v14 = 0x437a0000;
                    v8 = vfma_f32(v15, _arc4random_uniform(0x2710) / 10000f, v14);
                    v14 = vfma_f32(v15, _arc4random_uniform(0x2710) / 10000f, v14);
                    id obj_17;
                    
                    obj_17 = (i_16 & 0xff) * 0xaaaaaaab < 0x55555556 ? &cfstr_item_goldbar
                        : &cfstr_item_goldcoin;
                    
                    id obj_18 = _objc_retain(obj_17);
                    dispatch_time_t when_10 =
                        _dispatch_time(0, vcvtd_s64_f64(v9 * 0.040000000000000001 * 1000000000.0));
                    _objc_retainAutorelease(__dispatch_main_q);
                    void* (* const var_618)[0x20] = __NSConcreteStackBlock;
                    int64_t var_610_1 = 0xc2000000;
                    int64_t (* var_608_1)(void* arg1) = sub_42439c;
                    void* const var_600_1 = &data_43c130;
                    int32_t var_5f0_1 = v8;
                    float var_5ec_1 = v10 + 20f;
                    int32_t var_5e8_1 = v14;
                    id obj_19 = _objc_retain(obj_18);
                    _dispatch_after(when_10, __dispatch_main_q, &var_618);
                    _objc_release(obj_18);
                    _objc_release(obj_19);
                    v9 = v9 + 1.0;
                    i_16 += 1;
                } while (i_16 != 0x32);
                break;
            }
            case 0xfb0:
            {
                sub_410c94(&cfstr_Food_Feast!);
                struct __NSConstantString* const var_230 = &cfstr_item_apple;
                struct __NSConstantString* const var_228_1 = &cfstr_item_banana;
                struct __NSConstantString* const var_220_1 = &cfstr_item_pineapple;
                struct __NSConstantString* const var_218_1 = &cfstr_item_burrito;
                struct __NSConstantString* const var_210_1 = &cfstr_item_turkey_leg;
                struct __NSConstantString* const var_208_1 = &cfstr_item_turkey_whole;
                struct __NSConstantString* const var_200_1 = &cfstr_item_pumpkin_pie;
                struct __NSConstantString* const var_1f8_1 = &cfstr_item_popcorn;
                struct __NSConstantString* const var_1f0_1 = &cfstr_item_banana_chips;
                struct __NSConstantString* const var_1e8_1 = &cfstr_item_beans;
                obj_36 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
                    "arrayWithObjects:count:", &var_230, 0xa));
                v10 = v10 + 1f;
                int32_t i_38 = 0x1e;
                v13 = -4f;
                int32_t i_17;
                
                do
                {
                    v8 = 0x42c80000;
                    v9 = _arc4random_uniform(0x320) / v8 + v13;
                    v11 = v14 + v9;
                    v12 = v15 + _arc4random_uniform(0x320) / v8 + v13;
                    id obj_20;
                    int128_t v1_15;
                    int128_t v2_7;
                    obj_20 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_36, 
                        "objectAtIndexedSubscript:", 
                        _arc4random_uniform(_objc_msgSend(obj_36, "count"))));
                    v1_15 = v10;
                    v2_7 = v12;
                    sub_4114c8(obj_20, v11);
                    _objc_release(obj_20);
                    i_17 = i_38;
                    i_38 -= 1;
                } while (i_17 != 1);
                _objc_release(obj_36);
                break;
            }
            case 0xfb1:
            {
                sub_410c94(&cfstr_Shield_Wall!);
                struct __NSConstantString* const var_268 = &cfstr_item_shield;
                struct __NSConstantString* const var_260_1 = &cfstr_item_shield_bones;
                struct __NSConstantString* const var_258_1 = &cfstr_item_shield_police;
                struct __NSConstantString* const var_250_1 = &cfstr_item_shield_viking_1;
                struct __NSConstantString* const var_248_1 = &cfstr_item_shield_viking_2;
                struct __NSConstantString* const var_240_1 = &cfstr_item_shield_viking_3;
                struct __NSConstantString* const var_238_1 = &cfstr_item_shield_viking_4;
                obj_36 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
                    "arrayWithObjects:count:", &var_268, 7));
                int64_t i_18 = 0;
                int32_t v1_16 = v15;
                v15 = v9;
                v9 = v1_16 + 3f;
                v8 = -3f;
                v13 = 1.5f;
                v14 = 0.5f;
                
                do
                {
                    int32_t x8_8 = (i_18 & 0xff) * 0x25;
                    uint32_t x8_10 = (((i_18 - (x8_8 >> 8)) >> 1 & 0x7f) + (x8_8 >> 8)) >> 2;
                    v11 = v15 + i_18 + x8_10 - (x8_10 << 3) + v8;
                    v12 = vfma_f32(v10, x8_10, v13) + v14;
                    id x0_149 = _objc_msgSend(obj_36, "count");
                    id obj_21;
                    int128_t v1_17;
                    int128_t v2_8;
                    obj_21 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_36, 
                        "objectAtIndexedSubscript:", i_18 % x0_149));
                    v1_17 = v12;
                    v2_8 = v9;
                    sub_4114c8(obj_21, v11);
                    _objc_release(obj_21);
                    i_18 += 1;
                } while (i_18 != 0xe);
                
                _objc_release(obj_36);
                break;
            }
            case 0xfb2:
            {
                sub_410c94(&cfstr_Fishing_Frenzy!);
                struct __NSConstantString* const var_2a8 = &cfstr_item_fish_dumb_fish;
                struct __NSConstantString* const var_2a0_1 = &cfstr_item_goopfish;
                struct __NSConstantString* const var_298_1 = &cfstr_item_kissy;
                struct __NSConstantString* const var_290_1 = &cfstr_item_crappie;
                struct __NSConstantString* const var_288_1 = &cfstr_item_carp;
                struct __NSConstantString* const var_280_1 = &cfstr_item_diamond_jade_koi;
                struct __NSConstantString* const var_278_1 = &cfstr_item_rotten_fish;
                struct __NSConstantString* const var_270_1 = &cfstr_item_basic_fishing_rod;
                obj_36 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
                    "arrayWithObjects:count:", &var_2a8, 8));
                float v0_79 = v10 + 8f;
                v11 = 0.0;
                int32_t i_43 = 0x1e;
                v10 = v9;
                v13 = -5f;
                int32_t i_19;
                
                do
                {
                    v8 = 0x42c80000;
                    v9 = _arc4random_uniform(0x3e8) / v8 + v13;
                    float v0_81 = _arc4random_uniform(0x3e8) / v8 + v13;
                    v8 = v10 + v9;
                    v9 = v15 + v0_81;
                    id obj_22 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_36, 
                        "objectAtIndexedSubscript:", 
                        _arc4random_uniform(_objc_msgSend(obj_36, "count"))));
                    dispatch_time_t when_11 =
                        _dispatch_time(0, vcvtd_s64_f64(v11 * 0.059999999999999998 * 1000000000.0));
                    _objc_retainAutorelease(__dispatch_main_q);
                    void* (* const var_650)[0x20] = __NSConcreteStackBlock;
                    int64_t var_648_1 = 0xc2000000;
                    int64_t (* var_640_1)(void* arg1) = sub_4243b0;
                    void* const var_638_1 = &data_43c130;
                    int32_t var_628_1 = v8;
                    float var_624_1 = v0_79;
                    int32_t var_620_1 = v9;
                    id obj_23 = _objc_retain(obj_22);
                    _dispatch_after(when_11, __dispatch_main_q, &var_650);
                    _objc_release(obj_22);
                    _objc_release(obj_23);
                    v11 = v11 + 1.0;
                    i_19 = i_43;
                    i_43 -= 1;
                } while (i_19 != 1);
                _objc_release(obj_36);
                break;
            }
            case 0xfb3:
            {
                sub_410c94(&cfstr_Trophy_Shower!);
                float v0_85 = v10 + 12f;
                v11 = 0.0;
                int32_t i_37 = 0x14;
                v10 = v9;
                v13 = -6f;
                int32_t i_20;
                
                do
                {
                    v8 = 0x42c80000;
                    v9 = _arc4random_uniform(0x4b0) / v8 + v13;
                    uint32_t x0_169;
                    double v0_87;
                    x0_169 = _arc4random_uniform(0x4b0);
                    v0_87 = x0_169;
                    v0_87 = v0_87 / v8;
                    v0_87 = v0_87 + v13;
                    v8 = v10 + v9;
                    v9 = v15 + v0_87;
                    dispatch_time_t when_12 =
                        _dispatch_time(0, vcvtd_s64_f64(v11 * 0.080000000000000002 * 1000000000.0));
                    _objc_retainAutorelease(__dispatch_main_q);
                    void* (* const var_680)[0x20] = __NSConcreteStackBlock;
                    int64_t var_678_1 = 0xc0000000;
                    int64_t (* var_670_1)(void* arg1) = sub_4243c4;
                    void* const var_668_1 = &data_43c190;
                    int32_t var_660_1 = v8;
                    float var_65c_1 = v0_85;
                    int32_t var_658_1 = v9;
                    _dispatch_after(when_12, __dispatch_main_q, &var_680);
                    v11 = v11 + 1.0;
                    i_20 = i_37;
                    i_37 -= 1;
                } while (i_20 != 1);
                break;
            }
            case 0xfb4:
            {
                sub_410c94(&cfstr_Mine_Field!);
                v10 = v10 + 0.100000001f;
                int32_t i_32 = 0x19;
                v8 = -10f;
                v12 = v9;
                int32_t i_21;
                
                do
                {
                    v9 = 0x42c80000;
                    v11 = _arc4random_uniform(0x7d0) / v9 + v8;
                    uint32_t x0_173;
                    int128_t v2_9;
                    x0_173 = _arc4random_uniform(0x7d0);
                    v2_9 = v15 + x0_173 / v9 + v8;
                    sub_4114c8(&cfstr_item_landmine, v12 + v11);
                    i_21 = i_32;
                    i_32 -= 1;
                } while (i_21 != 1);
                break;
            }
            case 0xfb5:
            {
                sub_410c94(&cfstr_Party_Popper!);
                struct __NSConstantString* const var_2d8 = &cfstr_item_balloon;
                struct __NSConstantString* const var_2d0_1 = &cfstr_item_balloon_heart;
                struct __NSConstantString* const var_2c8_1 = &cfstr_item_glowstick;
                struct __NSConstantString* const var_2c0_1 = &cfstr_item_clapper;
                struct __NSConstantString* const var_2b8_1 = &cfstr_item_ukulele;
                struct __NSConstantString* const var_2b0_1 = &cfstr_item_confetti_grenade;
                obj_36 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
                    "arrayWithObjects:count:", &var_2d8, 6));
                int32_t i_22 = 0;
                v11 = 0.0;
                var_7d0 = 0x400921fb54442d18;
                var_7d8 = 0x3e19999a;
                var_7e0 = 0x3e99999a;
                v13 = v15;
                v15 = v9;
                
                do
                {
                    v8 = i_22;
                    double v0_92;
                    v0_92 = 30f;
                    v0_92 = v8 / v0_92;
                    v0_92 = v0_92 + v0_92;
                    v0_92 = v0_92 * 3.1415926535897931;
                    v9 = vfma_f32(1f, v8, 0.150000006f);
                    int32_t v0_93;
                    int32_t v1_19;
                    v0_93 = ___sincosf_stret(v0_92);
                    v12 = vfma_f32(v15, v1_19, v9);
                    v8 = vfma_f32(v10, v8, 0.300000012f);
                    v9 = vfma_f32(v13, v0_93, v9);
                    id obj_24 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_36, 
                        "objectAtIndexedSubscript:", 
                        _arc4random_uniform(_objc_msgSend(obj_36, "count"))));
                    dispatch_time_t when_13 =
                        _dispatch_time(0, vcvtd_s64_f64(v11 * 0.050000000000000003 * 1000000000.0));
                    _objc_retainAutorelease(__dispatch_main_q);
                    void* (* const var_6b8)[0x20] = __NSConcreteStackBlock;
                    int64_t var_6b0_1 = 0xc2000000;
                    int64_t (* var_6a8_1)(void* arg1) = sub_4243d8;
                    void* const var_6a0_1 = &data_43c130;
                    int32_t var_690_1 = v12;
                    int32_t var_68c_1 = v8;
                    int32_t var_688_1 = v9;
                    id obj_25 = _objc_retain(obj_24);
                    _dispatch_after(when_13, __dispatch_main_q, &var_6b8);
                    _objc_release(obj_24);
                    _objc_release(obj_25);
                    v11 = v11 + 1.0;
                    i_22 += 1;
                } while (i_22 != 0x1e);
                
                _objc_release(obj_36);
                break;
            }
            case 0xfb6:
            {
                double v0_95;
                double v1_20;
                v0_95 = sub_410c94(&cfstr_UFO_Beam!);
                int32_t i_23 = 0;
                v0_95 = 10f;
                v0_95 = v10 + v0_95;
                var_7e0 = v0_95;
                double v2_11 = 0.0;
                int64_t var_7e8;
                var_7e8 = 0x3e99999a;
                int64_t var_7f0;
                var_7f0 = 0x3e19999a;
                float v4_2 = 6f;
                v11 = v15;
                
                do
                {
                    int32_t j_2 = 0;
                    v0_95 = i_23;
                    v1_20 = 0x3e99999a;
                    v15 = vfma_f32(0.300000012f, v0_95, 0.150000006f);
                    v1_20 = 0x3e4ccccd;
                    v1_20 = v0_95 * 0.200000003f;
                    var_7d0 = v1_20;
                    v1_20 = var_7e0;
                    v8 = vfma_f32(v1_20, v0_95, -0.5f);
                    int64_t delta_1 = vcvtd_s64_f64(v2_11 * 0.080000000000000002 * 1000000000.0);
                    
                    do
                    {
                        v0_95 = j_2;
                        v0_95 = v0_95 / v4_2;
                        v0_95 = v0_95 + v0_95;
                        v0_95 = vfma_f64(var_7d0, v0_95, 3.1415926535897931);
                        int32_t v0_96;
                        int32_t v1_21;
                        v0_96 = ___sincosf_stret(v0_95);
                        v13 = vfma_f32(v9, v1_21, v15);
                        v10 = vfma_f32(v11, v0_96, v15);
                        dispatch_time_t when_14 = _dispatch_time(0, delta_1);
                        _objc_retainAutorelease(__dispatch_main_q);
                        void* (* const var_6e8)[0x20] = __NSConcreteStackBlock;
                        int64_t var_6e0_1 = 0xc0000000;
                        int64_t (* var_6d8_1)(void* arg1) = sub_4243ec;
                        void* const var_6d0_1 = &data_43c190;
                        int32_t var_6c8_1 = v13;
                        int32_t var_6c4_1 = v8;
                        int32_t var_6c0_1 = v10;
                        v0_95 = _dispatch_after(when_14, __dispatch_main_q, &var_6e8);
                        v4_2 = 6f;
                        j_2 += 1;
                    } while (j_2 != 6);
                    
                    v2_11 = v2_11 + 1.0;
                    i_23 += 1;
                } while (i_23 != 0x14);
                break;
            }
            case 0xfb7:
            {
                sub_410c94(&cfstr_Mask_Drop!);
                struct __NSConstantString* const var_2f8 = &cfstr_item_pumpkinjack;
                struct __NSConstantString* const var_2f0_1 = &cfstr_item_pumpkinjack_small;
                struct __NSConstantString* const var_2e8_1 = &cfstr_item_robot_head;
                struct __NSConstantString* const var_2e0_1 = &cfstr_item_bighead_larva;
                obj_36 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
                    "arrayWithObjects:count:", &var_2f8, 4));
                float v0_97 = v10 + 8f;
                v11 = 0.0;
                int32_t i_44 = 0x14;
                v10 = v9;
                v13 = -6f;
                int32_t i_24;
                
                do
                {
                    v8 = 0x42c80000;
                    v9 = _arc4random_uniform(0x4b0) / v8 + v13;
                    float v0_99 = _arc4random_uniform(0x4b0) / v8 + v13;
                    v8 = v10 + v9;
                    v9 = v15 + v0_99;
                    id obj_26 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_36, 
                        "objectAtIndexedSubscript:", 
                        _arc4random_uniform(_objc_msgSend(obj_36, "count"))));
                    dispatch_time_t when_15 =
                        _dispatch_time(0, vcvtd_s64_f64(v11 * 0.080000000000000002 * 1000000000.0));
                    _objc_retainAutorelease(__dispatch_main_q);
                    void* (* const var_720)[0x20] = __NSConcreteStackBlock;
                    int64_t var_718_1 = 0xc2000000;
                    int64_t (* var_710_1)(void* arg1) = sub_424400;
                    void* const var_708_1 = &data_43c130;
                    int32_t var_6f8_1 = v8;
                    float var_6f4_1 = v0_97;
                    int32_t var_6f0_1 = v9;
                    id obj_27 = _objc_retain(obj_26);
                    _dispatch_after(when_15, __dispatch_main_q, &var_720);
                    _objc_release(obj_26);
                    _objc_release(obj_27);
                    v11 = v11 + 1.0;
                    i_24 = i_44;
                    i_44 -= 1;
                } while (i_24 != 1);
                _objc_release(obj_36);
                break;
            }
            case 0xfb8:
            {
                sub_410c94(&cfstr_Brick_House!);
                int32_t i_25 = 0;
                int32_t v1_22 = v9;
                v9 = v15 + 3f;
                
                do
                {
                    int32_t j_3 = 0;
                    v11 = vfma_f32(v1_22, i_25, 0.400000006f) + -1.60000002f;
                    
                    do
                    {
                        vfma_f32(v10, j_3, 0.400000006f);
                        int128_t v2_12;
                        v2_12 = v9;
                        sub_4114c8(&cfstr_item_brick, v11);
                        j_3 += 1;
                    } while (j_3 != 6);
                    
                    i_25 += 1;
                    v1_22 = v14;
                } while (i_25 != 8);
                break;
            }
            case 0xfb9:
            {
                sub_410c94(&cfstr_Game_Drop!);
                struct __NSConstantString* const var_338 = &cfstr_item_gameboy;
                struct __NSConstantString* const var_330_1 = &cfstr_item_joystick;
                struct __NSConstantString* const var_328_1 = &cfstr_item_disc;
                struct __NSConstantString* const var_320_1 = &cfstr_item_floppy3;
                struct __NSConstantString* const var_318_1 = &cfstr_item_floppy5;
                struct __NSConstantString* const var_310_1 = &cfstr_item_harddrive;
                struct __NSConstantString* const var_308_1 = &cfstr_item_tablet;
                struct __NSConstantString* const var_300_1 = &cfstr_item_calculator;
                obj_36 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
                    "arrayWithObjects:count:", &var_338, 8));
                float v0_104 = v10 + 6f;
                v11 = 0.0;
                int32_t i_45 = 0x14;
                v10 = v9;
                v13 = -4f;
                int32_t i_26;
                
                do
                {
                    v8 = 0x42c80000;
                    v9 = _arc4random_uniform(0x320) / v8 + v13;
                    float v0_106 = _arc4random_uniform(0x320) / v8 + v13;
                    v8 = v10 + v9;
                    v9 = v15 + v0_106;
                    id obj_28 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_36, 
                        "objectAtIndexedSubscript:", 
                        _arc4random_uniform(_objc_msgSend(obj_36, "count"))));
                    dispatch_time_t when_16 =
                        _dispatch_time(0, vcvtd_s64_f64(v11 * 0.059999999999999998 * 1000000000.0));
                    _objc_retainAutorelease(__dispatch_main_q);
                    void* (* const var_758)[0x20] = __NSConcreteStackBlock;
                    int64_t var_750_1 = 0xc2000000;
                    int64_t (* var_748_1)(void* arg1) = sub_424414;
                    void* const var_740_1 = &data_43c130;
                    int32_t var_730_1 = v8;
                    float var_72c_1 = v0_104;
                    int32_t var_728_1 = v9;
                    id obj_29 = _objc_retain(obj_28);
                    _dispatch_after(when_16, __dispatch_main_q, &var_758);
                    _objc_release(obj_28);
                    _objc_release(obj_29);
                    v11 = v11 + 1.0;
                    i_26 = i_45;
                    i_45 -= 1;
                } while (i_26 != 1);
                _objc_release(obj_36);
                break;
            }
            case 0xfba:
            {
                sub_410c94(&cfstr_Ice_Fortress!);
                int32_t i_27 = 0;
                int32_t x22_4 = 0xc;
                var_7d0 = 0x400921fb54442d18;
                v13 = 0.5f;
                
                do
                {
                    int32_t x23_7 = 0;
                    double v0_110;
                    v0_110 = i_27;
                    v8 = vfma_f32(3f, v0_110, 1.5f);
                    v14 = (i_27 << 2) + 0xc;
                    
                    do
                    {
                        v0_110 = x23_7;
                        v0_110 = v0_110 / v14;
                        v0_110 = v0_110 + v0_110;
                        v0_110 = v0_110 * 3.1415926535897931;
                        float v1_23;
                        v0_110 = ___sincosf_stret(v0_110);
                        int32_t j_4 = 0;
                        v11 = vfma_f32(v9, v1_23, v8);
                        v12 = vfma_f32(v15, v0_110, v8);
                        
                        do
                        {
                            v0_110 = j_4;
                            vfma_f32(v10, v0_110, v13);
                            v0_110 = v11;
                            sub_4114c8(&cfstr_item_snowball, v0_110);
                            j_4 += 1;
                        } while (j_4 != 3);
                        
                        x23_7 += 1;
                    } while (x23_7 != x22_4);
                    
                    i_27 += 1;
                    x22_4 += 4;
                } while (i_27 != 3);
                break;
            }
            case 0xfbb:
            {
                sub_410c94(&cfstr_Rainbow_Bridge!);
                struct __NSConstantString* const var_370 = &cfstr_item_balloon;
                struct __NSConstantString* const var_368_1 = &cfstr_item_balloon_heart;
                struct __NSConstantString* const var_360_1 = &cfstr_item_glowstick;
                struct __NSConstantString* const var_358_1 = &cfstr_item_goldbar;
                struct __NSConstantString* const var_350_1 = &cfstr_item_ruby;
                struct __NSConstantString* const var_348_1 = &cfstr_item_broccoli_grenade;
                struct __NSConstantString* const var_340_1 = &cfstr_item_disc;
                id obj_30;
                double v0_111;
                obj_30 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
                    "arrayWithObjects:count:", &var_370, 7));
                int64_t i_28 = 0;
                v0_111 = 5f;
                v8 = v9;
                v9 = v15 + v0_111;
                v15 = 10f;
                v14 = 1f;
                
                do
                {
                    v0_111 = i_28;
                    v0_111 = v0_111 / 30f;
                    v11 = vfma_f32(-5f, v0_111, v15);
                    v0_111 = v0_111 * 3.1415926535897931;
                    v11 = v8 + v11;
                    v12 = v10 + _sinf(v0_111) * 5f + v14;
                    id x0_222 = _objc_msgSend(obj_30, "count");
                    id obj_31;
                    int128_t v1_26;
                    int128_t v2_14;
                    obj_31 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_30, 
                        "objectAtIndexedSubscript:", i_28 % x0_222));
                    v1_26 = v12;
                    v2_14 = v9;
                    sub_4114c8(obj_31, v11);
                    _objc_release(obj_31);
                    i_28 += 1;
                } while (i_28 != 0x1e);
                
                _objc_release(obj_30);
                break;
            }
            case 0xfbc:
            {
                sub_410c94(&cfstr_Volcano_Eruption!);
                struct __NSConstantString* const var_3a0 = &cfstr_item_dynamite;
                struct __NSConstantString* const var_398_1 = &cfstr_item_flamethrower;
                struct __NSConstantString* const var_390_1 = &cfstr_item_ore_hell;
                struct __NSConstantString* const var_388_1 = &cfstr_item_brain_chunk;
                struct __NSConstantString* const var_380_1 = &cfstr_item_heart_chunk;
                struct __NSConstantString* const var_378_1 = &cfstr_item_sludge;
                obj_36 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
                    "arrayWithObjects:count:", &var_3a0, 6));
                v12 = 0.0;
                int32_t i_46 = 0x23;
                v14 = v15;
                v15 = v9;
                int32_t i_29;
                
                do
                {
                    v11 = _arc4random_uniform(0xe10) / 573f;
                    v8 = 0x42c80000;
                    v9 = _arc4random_uniform(0x12c) / v8;
                    v8 = _arc4random_uniform(0x5dc) / v8 + 5f;
                    int32_t v0_117;
                    int32_t v1_28;
                    v0_117 = ___sincosf_stret(v11);
                    v11 = vfma_f32(v15, v1_28, v9);
                    v8 = v10 + v8;
                    v9 = vfma_f32(v14, v0_117, v9);
                    id obj_32 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_36, 
                        "objectAtIndexedSubscript:", 
                        _arc4random_uniform(_objc_msgSend(obj_36, "count"))));
                    dispatch_time_t when_17 =
                        _dispatch_time(0, vcvtd_s64_f64(v12 * 0.059999999999999998 * 1000000000.0));
                    _objc_retainAutorelease(__dispatch_main_q);
                    void* (* const var_790)[0x20] = __NSConcreteStackBlock;
                    int64_t var_788_1 = 0xc2000000;
                    int64_t (* var_780_1)(void* arg1) = sub_424428;
                    void* const var_778_1 = &data_43c130;
                    int32_t var_768_1 = v11;
                    int32_t var_764_1 = v8;
                    int32_t var_760_1 = v9;
                    id obj_33 = _objc_retain(obj_32);
                    _dispatch_after(when_17, __dispatch_main_q, &var_790);
                    _objc_release(obj_32);
                    _objc_release(obj_33);
                    v12 = v12 + 1.0;
                    i_29 = i_46;
                    i_46 -= 1;
                } while (i_29 != 1);
                _objc_release(obj_36);
                break;
            }
            case 0xfbd:
            {
                sub_410c94(&cfstr_Crown_Rain!);
                struct __NSConstantString* const var_3d0 = &cfstr_item_trophy;
                struct __NSConstantString* const var_3c8_1 = &cfstr_item_rare_card;
                struct __NSConstantString* const var_3c0_1 = &cfstr_item_ceo_plaque;
                struct __NSConstantString* const var_3b8_1 = &cfstr_item_goldbar;
                struct __NSConstantString* const var_3b0_1 = &cfstr_item_stellarsword_gold;
                struct __NSConstantString* const var_3a8_1 = &cfstr_item_ukulele_gold;
                obj_36 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
                    "arrayWithObjects:count:", &var_3d0, 6));
                v8 = 0.0;
                int32_t i_47 = 0x19;
                int32_t i_30;
                
                do
                {
                    v14 = 0xc2c80000;
                    v15 = 0x437a0000;
                    v13 = vfma_f32(v14, _arc4random_uniform(0x2710) / 10000f, v15);
                    v14 = vfma_f32(v14, _arc4random_uniform(0x2710) / 10000f, v15);
                    id obj_34 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_36, 
                        "objectAtIndexedSubscript:", 
                        _arc4random_uniform(_objc_msgSend(obj_36, "count"))));
                    dispatch_time_t when_18 =
                        _dispatch_time(0, vcvtd_s64_f64(v8 * 0.080000000000000002 * 1000000000.0));
                    _objc_retainAutorelease(__dispatch_main_q);
                    void* (* const var_7c8)[0x20] = __NSConcreteStackBlock;
                    int64_t var_7c0_1 = 0xc2000000;
                    int64_t (* var_7b8_1)(void* arg1) = sub_42443c;
                    void* const var_7b0_1 = &data_43c130;
                    int32_t var_7a0_1 = v13;
                    int32_t var_79c_1 = 0x41f00000;
                    int32_t var_798_1 = v14;
                    id obj_35 = _objc_retain(obj_34);
                    _dispatch_after(when_18, __dispatch_main_q, &var_7c8);
                    _objc_release(obj_34);
                    _objc_release(obj_35);
                    v8 = v8 + 1.0;
                    i_30 = i_47;
                    i_47 -= 1;
                } while (i_30 != 1);
                _objc_release(obj_36);
                break;
            }
        }
    }
    
    _objc_release(obj);
    
    if (*___stack_chk_guard == x8)
        return;
    
    ___stack_chk_fail();
    /* no return */
}

int64_t sub_4242d4(void* arg1)
{
    int128_t v1;
    v1 = *(arg1 + 0x24);
    int128_t v2;
    v2 = *(arg1 + 0x28);
    /* tailcall */
    return sub_4114c8(&cfstr_item_crossbow, *(arg1 + 0x20));
}

int64_t sub_4242e8(void* arg1)
{
    int128_t v1;
    v1 = *(arg1 + 0x24);
    int128_t v2;
    v2 = *(arg1 + 0x28);
    /* tailcall */
    return sub_4114c8(&cfstr_item_rpg, *(arg1 + 0x20));
}

int64_t sub_4242fc(void* arg1)
{
    int128_t v1;
    v1 = *(arg1 + 0x24);
    int128_t v2;
    v2 = *(arg1 + 0x28);
    /* tailcall */
    return sub_4114c8(&cfstr_item_snowball, *(arg1 + 0x20));
}

int64_t sub_424310(void* arg1)
{
    int128_t v1;
    v1 = *(arg1 + 0x2c);
    int128_t v2;
    v2 = *(arg1 + 0x30);
    /* tailcall */
    return sub_4114c8(*(arg1 + 0x20), *(arg1 + 0x28));
}

int64_t sub_424324(void* arg1)
{
    int128_t v1;
    v1 = *(arg1 + 0x2c);
    int128_t v2;
    v2 = *(arg1 + 0x30);
    /* tailcall */
    return sub_4114c8(*(arg1 + 0x20), *(arg1 + 0x28));
}

int64_t sub_424338(void* arg1)
{
    int128_t v1;
    v1 = *(arg1 + 0x24);
    int128_t v2;
    v2 = *(arg1 + 0x28);
    /* tailcall */
    return sub_4114c8(&cfstr_item_jetpack, *(arg1 + 0x20));
}

int64_t sub_42434c(void* arg1)
{
    int128_t v1;
    v1 = *(arg1 + 0x2c);
    int128_t v2;
    v2 = *(arg1 + 0x30);
    /* tailcall */
    return sub_4114c8(*(arg1 + 0x20), *(arg1 + 0x28));
}

int64_t sub_424360(void* arg1)
{
    int128_t v1;
    v1 = *(arg1 + 0x2c);
    int128_t v2;
    v2 = *(arg1 + 0x30);
    /* tailcall */
    return sub_4114c8(*(arg1 + 0x20), *(arg1 + 0x28));
}

int64_t sub_424374(void* arg1)
{
    int128_t v1;
    v1 = *(arg1 + 0x2c);
    int128_t v2;
    v2 = *(arg1 + 0x30);
    /* tailcall */
    return sub_4114c8(*(arg1 + 0x20), *(arg1 + 0x28));
}

int64_t sub_424388(void* arg1)
{
    int128_t v1;
    v1 = *(arg1 + 0x2c);
    int128_t v2;
    v2 = *(arg1 + 0x30);
    /* tailcall */
    return sub_4114c8(*(arg1 + 0x20), *(arg1 + 0x28));
}

int64_t sub_42439c(void* arg1)
{
    int128_t v1;
    v1 = *(arg1 + 0x2c);
    int128_t v2;
    v2 = *(arg1 + 0x30);
    /* tailcall */
    return sub_4114c8(*(arg1 + 0x20), *(arg1 + 0x28));
}

int64_t sub_4243b0(void* arg1)
{
    int128_t v1;
    v1 = *(arg1 + 0x2c);
    int128_t v2;
    v2 = *(arg1 + 0x30);
    /* tailcall */
    return sub_4114c8(*(arg1 + 0x20), *(arg1 + 0x28));
}

int64_t sub_4243c4(void* arg1)
{
    int128_t v1;
    v1 = *(arg1 + 0x24);
    int128_t v2;
    v2 = *(arg1 + 0x28);
    /* tailcall */
    return sub_4114c8(&cfstr_item_trophy, *(arg1 + 0x20));
}

int64_t sub_4243d8(void* arg1)
{
    int128_t v1;
    v1 = *(arg1 + 0x2c);
    int128_t v2;
    v2 = *(arg1 + 0x30);
    /* tailcall */
    return sub_4114c8(*(arg1 + 0x20), *(arg1 + 0x28));
}

int64_t sub_4243ec(void* arg1)
{
    int128_t v1;
    v1 = *(arg1 + 0x24);
    int128_t v2;
    v2 = *(arg1 + 0x28);
    /* tailcall */
    return sub_4114c8(&cfstr_item_glowstick, *(arg1 + 0x20));
}

int64_t sub_424400(void* arg1)
{
    int128_t v1;
    v1 = *(arg1 + 0x2c);
    int128_t v2;
    v2 = *(arg1 + 0x30);
    /* tailcall */
    return sub_4114c8(*(arg1 + 0x20), *(arg1 + 0x28));
}

int64_t sub_424414(void* arg1)
{
    int128_t v1;
    v1 = *(arg1 + 0x2c);
    int128_t v2;
    v2 = *(arg1 + 0x30);
    /* tailcall */
    return sub_4114c8(*(arg1 + 0x20), *(arg1 + 0x28));
}

int64_t sub_424428(void* arg1)
{
    int128_t v1;
    v1 = *(arg1 + 0x2c);
    int128_t v2;
    v2 = *(arg1 + 0x30);
    /* tailcall */
    return sub_4114c8(*(arg1 + 0x20), *(arg1 + 0x28));
}

int64_t sub_42443c(void* arg1)
{
    int128_t v1;
    v1 = *(arg1 + 0x2c);
    int128_t v2;
    v2 = *(arg1 + 0x30);
    /* tailcall */
    return sub_4114c8(*(arg1 + 0x20), *(arg1 + 0x28));
}

void -[ACPanelController heartTapped](struct ACPanelController* self, SEL sel)
{
    int64_t v8;
    int64_t var_68 = v8;
    sub_412450();
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIAlertController, 
        "alertControllerWithTitle:message:preferredStyle:", &cfstr_??_Heart_Target, 
        &cfstr_Select_a_player_to_spawn_a_heart_above:, 1));
    
    if (_objc_msgSend(data_4469e0, "count") > 0)
    {
        int64_t x24_1 = 0;
        id x0_13;
        
        do
        {
            id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(data_4469e0, 
                "objectAtIndexedSubscript:"));
            id clsRef_UIAlertAction_1 = clsRef_UIAlertAction;
            void* (* const var_a8)[0x20] = __NSConcreteStackBlock;
            int64_t var_a0_1 = 0xc2000000;
            int64_t (* var_98_1)(void* arg1) = sub_424668;
            void* const var_90_1 = &data_43c500;
            struct ACPanelController* self_1 = self;
            int64_t var_78_1 = x24_1;
            int64_t obj_2 = _objc_retain(obj_1);
            int64_t obj_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(
                clsRef_UIAlertAction_1, "actionWithTitle:style:handler:", obj_2, 0, &var_a8));
            _objc_msgSend(obj, "addAction:", obj_3);
            _objc_release(obj_3);
            _objc_release(obj_1);
            _objc_release(obj_2);
            x24_1 += 1;
            x0_13 = _objc_msgSend(data_4469e0, "count");
        } while (x24_1 < x0_13);
    }
    
    int64_t obj_4 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIAlertAction, 
        "actionWithTitle:style:handler:", &cfstr_Cancel, 1, 0));
    _objc_msgSend(obj, "addAction:", obj_4);
    _objc_release(obj_4);
    _objc_msgSend(self, "presentViewController:animated:completion:", obj, 1, 0);
    _objc_release(obj);
}

int64_t sub_424668(void* arg1)
{
    data_446788 = *(arg1 + 0x30);
    int64_t var_30 = *(arg1 + 0x20);
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
        "stringWithFormat:", &cfstr_OK_player_selected:_%@));
    sub_410c94(obj);
    _objc_release(obj);
    /* tailcall */
    return _objc_msgSend(*(arg1 + 0x28), "doHeartSpawn");
}

void -[ACPanelController doHeartSpawn](struct ACPanelController* self, SEL sel)
{
    int64_t v15;
    int64_t var_90 = v15;
    int64_t v14;
    int64_t var_88 = v14;
    int64_t v13;
    int64_t var_80 = v13;
    int64_t v12;
    int64_t var_78 = v12;
    int64_t v11;
    int64_t var_70 = v11;
    int64_t v10;
    int64_t var_68 = v10;
    int64_t v9;
    int64_t var_60 = v9;
    int64_t v8;
    int64_t var_58 = v8;
    id x0_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "currentList"));
    id x0_3 = _objc_msgSend(self, "selectedIndex");
    id x0_5;
    id x0_7;
    
    if (!(x0_3 & 0x8000000000000000))
    {
        x0_5 = _objc_msgSend(self, "selectedIndex");
        x0_7 = _objc_msgSend(x0_1, "count");
    }
    
    if (!(x0_3 & 0x8000000000000000) && x0_5 < x0_7)
        goto label_4247c4;
    
    if (_objc_msgSend(x0_1, "count"))
    {
        _objc_msgSend(self, "setSelectedIndex:", 0);
    label_4247c4:
        id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(x0_1, 
            "objectAtIndexedSubscript:", _objc_msgSend(self, "selectedIndex")));
        
        if (data_446ad2 != 1)
        {
            int64_t x24_1 = data_446788;
            id x0_16;
            
            if (!(x24_1 & 0x8000000000000000))
                x0_16 = _objc_msgSend(data_4469e8, "count");
            
            if (x24_1 & 0x8000000000000000 || x24_1 >= x0_16)
            {
                int32_t v0_2;
                int32_t v1_2;
                int32_t v2_2;
                v0_2 = sub_4113d8();
                v15 = v0_2;
                v10 = v1_2;
                v8 = v2_2;
            }
            else
            {
                id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(data_4469e8, 
                    "objectAtIndexedSubscript:", data_446788));
                int32_t v0_1;
                int32_t v1_1;
                int32_t v2_1;
                
                if (!_objc_msgSend(obj_1, "isKindOfClass:", _objc_msgSend(clsRef_NSValue, "class")))
                    v0_1 = sub_4113d8();
                else
                    v0_1 = sub_4127a8(_objc_msgSend(obj_1, "pointerValue"));
                
                v15 = v0_1;
                v10 = v1_1;
                v8 = v2_1;
                _objc_release(obj_1);
            }
        }
        else
        {
            v15 = *data_446ad4;
            v10 = *(data_446ad4 + 4);
            v8 = data_446adc;
        }
        
        int64_t x24_3 = data_446788;
        id x0_27;
        
        if (!(x24_3 & 0x8000000000000000))
            x0_27 = _objc_msgSend(data_4469e0, "count");
        
        id obj_4;
        
        if (x24_3 & 0x8000000000000000 || x24_3 >= x0_27)
            obj_4 = &cfstr_Local;
        else
            obj_4 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(data_4469e0, 
                "objectAtIndexedSubscript:", data_446788));
        
        id obj_6 = obj_4;
        int64_t var_a0_1 = 0x1e;
        id obj_5 = obj;
        id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
            "stringWithFormat:", &cfstr_Heart:_%@_above_%@_(%d_pts)));
        sub_410c94(obj_2);
        _objc_release(obj_2);
        int32_t i = 0;
        double v0_3;
        v0_3 = 5f;
        v12 = v10 + v0_3;
        
        do
        {
            v0_3 = i;
            v0_3 = v0_3 / 30f;
            v0_3 = v0_3 + v0_3;
            v10 = v0_3 * 3.1415926535897931;
            v0_3 = v10;
            float v0_4;
            float v1_4;
            v0_4 = ___sincosf_stret(v0_3);
            v11 = v1_4;
            v13 = v0_4 * v0_4 * v0_4 * 16f;
            v11 = vfma_f32(_cosf(v10 + v10) * -5f, v11, 13f);
            v11 = vfma_f32(v11, _cosf(v10 * 3f), -2f);
            float v0_7;
            int128_t v2_3;
            v0_7 = _cosf(v10 * 4f);
            float temp0_3 = vfma_f32(v15, v13, 0.150000006f);
            vfma_f32(v12, v11 - v0_7, 0.150000006f);
            v2_3 = v8;
            sub_4114c8(obj, temp0_3);
            i += 1;
        } while (i != 0x1e);
        
        int64_t x6_1;
        int128_t v0_8;
        x6_1 = sub_410c94(&cfstr_Heart_shape_done!);
        
        if (data_446b28 && !data_4469f0)
        {
            v0_8 = 3.0;
            id x0_37 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSTimer, 
                "scheduledTimerWithTimeInterval:target:selector:userInfo:repeats:", self, 
                "heartLoopTick", 0, 1, x6_1));
            id obj_3 = data_4469f0;
            data_4469f0 = x0_37;
            _objc_release(obj_3);
            sub_410c94(&cfstr_Heart_loop_started_(3s_interval));
        }
        
        _objc_release(obj_4);
        _objc_release(obj);
    }
    
    /* tailcall */
    return _objc_release(x0_1);
}

void -[ACPanelController heartLoopTick](struct ACPanelController* self, SEL sel)
{
    if (data_446b28)
        /* tailcall */
        return _objc_msgSend(self, "doHeartSpawn");
    
    _objc_msgSend(data_4469f0, "invalidate");
    id obj = data_4469f0;
    data_4469f0 = 0;
    _objc_release(obj);
    /* tailcall */
    return sub_410c94(&cfstr_Heart_loop_stopped);
}

void -[ACPanelController rainTapped](struct ACPanelController* self, SEL sel)
{
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "rainTimer"));
    _objc_release(obj);
    
    if (obj)
    {
        id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "rainTimer"));
        _objc_msgSend(obj_1, "invalidate");
        _objc_release(obj_1);
        _objc_msgSend(self, "setRainTimer:", 0);
        id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "rainBtn"));
        _objc_msgSend(obj_2, "setTitle:forState:", &cfstr_??_Rain, 0);
        _objc_release(obj_2);
        /* tailcall */
        return sub_410c94(&cfstr_Rain_stopped);
    }
    
    id x0_11 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "currentList"));
    id x0_13 = _objc_msgSend(self, "selectedIndex");
    id x0_15;
    id x0_17;
    
    if (!(x0_13 & 0x8000000000000000))
    {
        x0_15 = _objc_msgSend(self, "selectedIndex");
        x0_17 = _objc_msgSend(x0_11, "count");
    }
    
    if (!(x0_13 & 0x8000000000000000) && x0_15 < x0_17)
        goto label_424c78;
    
    if (_objc_msgSend(x0_11, "count"))
    {
        _objc_msgSend(self, "setSelectedIndex:", 0);
    label_424c78:
        _objc_msgSend(self, "setRainRemaining:", _objc_msgSend(self, "spawnQuantity"));
        id obj_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "rainBtn"));
        _objc_msgSend(obj_3, "setTitle:forState:", &cfstr_Stop_Rain, 0);
        _objc_release(obj_3);
        struct objc_class_t* clsRef_NSString_1 = clsRef_NSString;
        id obj_4 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(x0_11, 
            "objectAtIndexedSubscript:", _objc_msgSend(self, "selectedIndex")));
        id obj_7 = obj_4;
        id var_48_1 = _objc_msgSend(self, "rainRemaining");
        id obj_5 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString_1, 
            "stringWithFormat:", &cfstr_Rain:_%@_x%d));
        sub_410c94(obj_5);
        _objc_release(obj_5);
        int64_t x6_2;
        int128_t v0_2;
        x6_2 = _objc_release(obj_4);
        v0_2 = 0x3fb999999999999a;
        id obj_6 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSTimer, 
            "scheduledTimerWithTimeInterval:target:selector:userInfo:repeats:", self, "rainTick", 
            0, 1, x6_2));
        _objc_msgSend(self, "setRainTimer:", obj_6);
        _objc_release(obj_6);
    }
    
    /* tailcall */
    return _objc_release(x0_11);
}

void -[ACPanelController rainTick](struct ACPanelController* self, SEL sel)
{
    int64_t v9;
    int64_t var_50 = v9;
    int64_t v8;
    int64_t var_48 = v8;
    
    if (_objc_msgSend(self, "rainRemaining") <= 0)
    {
        id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "rainTimer"));
        _objc_msgSend(obj_1, "invalidate");
        _objc_release(obj_1);
        _objc_msgSend(self, "setRainTimer:", 0);
        id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "rainBtn"));
        _objc_msgSend(obj_2, "setTitle:forState:", &cfstr_??_Rain, 0);
        _objc_release(obj_2);
        /* tailcall */
        return sub_410c94(&cfstr_Rain_finished);
    }
    
    id x0_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "currentList"));
    
    if (!(_objc_msgSend(self, "selectedIndex") & 0x8000000000000000)
        && _objc_msgSend(self, "selectedIndex") < _objc_msgSend(x0_3, "count"))
    {
        id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(x0_3, 
            "objectAtIndexedSubscript:", _objc_msgSend(self, "selectedIndex")));
        int32_t x0_15 = _objc_msgSend(self, "spawnQuantity");
        int32_t x0_17 = _objc_msgSend(self, "rainRemaining");
        int32_t x8_3;
        
        x8_3 = x0_15 > 0x27 ? x0_15 / 0x14 : 1;
        
        int32_t x8_6;
        
        x8_6 = 0x14 - x0_17 / x8_3 > 0 ? 0x14 - x0_17 / x8_3 : 0;
        
        int32_t x8_7;
        
        x8_7 = x8_6 < 0x13 ? x8_6 : 0x13;
        
        v9 = (x8_7 + 1) * 5f;
        v8 = _arc4random_uniform(0xe10) / 573f;
        float v1_2 = 0.5f;
        v9 = vfma_f32(_arc4random_uniform(0x3e8) / 0x447a0000 * v9 * v1_2, v9, v1_2);
        int32_t v0_4;
        int32_t v1_3;
        v0_4 = ___sincosf_stret(v8);
        v8 = v1_3 * v9;
        v9 = v0_4 * v9;
        uint32_t x0_20;
        int128_t v2_1;
        x0_20 = _arc4random_uniform(0x1f4);
        v2_1 = v9;
        sub_4114c8(obj, v8);
        _objc_msgSend(self, "setRainRemaining:", _objc_msgSend(self, "rainRemaining") - 1);
        _objc_release(obj);
    }
    
    /* tailcall */
    return _objc_release(x0_3);
}

void -[ACPanelController spawnTapped](struct ACPanelController* self, SEL sel)
{
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "loopTimer"));
    _objc_release(obj);
    
    if (obj)
    {
        id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "loopTimer"));
        _objc_msgSend(obj_1, "invalidate");
        _objc_release(obj_1);
        _objc_msgSend(self, "setLoopTimer:", 0);
        id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnBtn"));
        _objc_msgSend(obj_2, "setTitle:forState:", &cfstr_Spawn, 0);
        _objc_release(obj_2);
        /* tailcall */
        return sub_410c94(&cfstr_Loop_stopped);
    }
    
    _objc_msgSend(self, "doSpawnOnce");
    id obj_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "loopSwitch"));
    int32_t x0_12 = _objc_msgSend(obj_3, "isOn");
    _objc_release(obj_3);
    
    if (!x0_12)
        return;
    
    id obj_4 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnBtn"));
    _objc_msgSend(obj_4, "setTitle:forState:", &cfstr_Stop_Loop, 0);
    int64_t x6_1;
    int128_t v0_1;
    x6_1 = _objc_release(obj_4);
    v0_1 = 0.5;
    id x0_19 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSTimer, 
        "scheduledTimerWithTimeInterval:target:selector:userInfo:repeats:", self, "loopTick", 0, 1, 
        x6_1));
    _objc_msgSend(self, "setLoopTimer:", x0_19);
    /* tailcall */
    return _objc_release(x0_19);
}

void -[ACPanelController loopTick](struct ACPanelController* self, SEL sel)
{
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "loopSwitch"));
    int32_t x0_1 = _objc_msgSend(obj, "isOn");
    _objc_release(obj);
    
    if (x0_1 & 1)
        /* tailcall */
        return _objc_msgSend(self, "doSpawnOnce");
    
    id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "loopTimer"));
    _objc_msgSend(obj_1, "invalidate");
    _objc_release(obj_1);
    _objc_msgSend(self, "setLoopTimer:", 0);
    id x0_11 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnBtn"));
    _objc_msgSend(x0_11, "setTitle:forState:", &cfstr_Spawn, 0);
    /* tailcall */
    return _objc_release(x0_11);
}

void -[ACPanelController doSpawnOnce](struct ACPanelController* self, SEL sel)
{
    int64_t v10;
    int64_t var_78 = v10;
    int64_t v9;
    int64_t var_70 = v9;
    int64_t v8;
    int64_t var_68 = v8;
    int64_t x8 = *___stack_chk_guard;
    id obj_13 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "currentList"));
    id x0_3 = _objc_msgSend(self, "selectedIndex");
    id x0_5;
    id x0_7;
    
    if (!(x0_3 & 0x8000000000000000))
    {
        x0_5 = _objc_msgSend(self, "selectedIndex");
        x0_7 = _objc_msgSend(obj_13, "count");
    }
    
    if (!(x0_3 & 0x8000000000000000) && x0_5 < x0_7)
        goto label_4253d4;
    
    if (_objc_msgSend(obj_13, "count"))
    {
        _objc_msgSend(self, "setSelectedIndex:", 0);
    label_4253d4:
        id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_13, 
            "objectAtIndexedSubscript:", _objc_msgSend(self, "selectedIndex")));
        id x27_1 = _objc_msgSend(self, "spawnQuantity");
        id x0_18 = _objc_msgSend(self, "activeTab");
        id obj_2 = _objc_retain(obj_1);
        id var_f0_1 = x27_1;
        id obj_12;
        char* var_c8;
        int128_t var_a0;
        
        if (!x0_18)
        {
            uint32_t x22_3 = data_446ad2;
            v10 = *data_446ad4;
            v9 = *(data_446ad4 + 4);
            v8 = data_446adc;
            id obj_14 = obj_2;
            id var_128_1 = x27_1;
            id obj_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
                "stringWithFormat:", &cfstr_Spawn_'%@'_x%d));
            sub_410c94(obj_3);
            _objc_release(obj_3);
            obj_12 = obj_2;
            
            if (x27_1 >= 1)
            {
                int32_t i = 0;
                float v0_2 = 0f;
                
                if (x22_3)
                    v8 = v8;
                else
                    v8 = v0_2;
                
                if (x22_3)
                    v9 = v9;
                else
                    v9 = 2.5f;
                
                if (x22_3)
                    v10 = v10;
                else
                    v10 = v0_2;
                
                do
                {
                    uint32_t x8_4 = data_446ac0;
                    
                    if (x8_4 | data_446ac9)
                    {
                        int32_t x23;
                        uint32_t x28_1;
                        
                        if (!x8_4)
                        {
                            x28_1 = 0;
                            x23 = 0x80;
                        }
                        else if (!data_446ac8)
                        {
                            x28_1 = data_446ac4;
                            x23 = data_446760;
                        }
                        else
                        {
                            x28_1 = _arc4random_uniform(0x169);
                            
                            if (!data_446ac0)
                                x23 = 0x80;
                            else if (!data_446ac8)
                                x23 = data_446760;
                            else
                                x23 = _arc4random_uniform(0xc0) + 0x40;
                        }
                        
                        id obj_4;
                        int128_t v1_2;
                        int128_t v2_2;
                        obj_4 = _objc_retain(obj_12);
                        int64_t x0_29 = data_446ae8;
                        int32_t x19_3;
                        
                        if (!x0_29)
                            x19_3 = 0;
                        else
                        {
                            int64_t x0_30;
                            x0_30 = data_446ae0(x0_29, &cstr_, "ItemInstance");
                            
                            if (x0_30)
                            {
                            label_4255cc:
                                x19_3 = 0;
                                
                                if (x0_30 && data_446af0)
                                {
                                    int64_t x0_32;
                                    x0_32 = data_446af8();
                                    
                                    if (!x0_32)
                                        x19_3 = 0;
                                    else
                                    {
                                        int64_t x0_33;
                                        x0_33 = data_446b00();
                                        
                                        if (!x0_33)
                                            x19_3 = 0;
                                        else
                                        {
                                            var_c8 = nullptr;
                                            var_a0 = x0_33;
                                            void* x0_35;
                                            x0_35 = data_446b08(data_446af0, 0, &var_a0, &var_c8);
                                            x19_3 = 0;
                                            
                                            if (x0_35 && !var_c8)
                                                x19_3 = *(x0_35 + 0x18);
                                        }
                                    }
                                }
                            }
                            else
                            {
                                x0_30 = data_446ae0(data_446ae8, "AnimalCompany", "ItemInstance");
                                
                                if (x0_30)
                                    goto label_4255cc;
                                
                                int64_t x0_36 = data_446ae8;
                                
                                if (x0_36)
                                {
                                    x0_30 = data_446ae0(x0_36, &cstr_, "Item");
                                    
                                    if (!x0_30)
                                        x0_30 = data_446ae0(data_446ae8, "AnimalCompany", "Item");
                                    
                                    goto label_4255cc;
                                }
                                
                                x19_3 = 0;
                            }
                        }
                        
                        v1_2 = v9;
                        v2_2 = v8;
                        sub_4114c8(obj_4, v10);
                        int32_t x22_4 = 0;
                        
                        while (true)
                        {
                            _usleep(0xc350 + x22_4 * 0xc350);
                            int32_t x0_40 = data_44677c;
                            
                            if (x0_40 & 0x80000000)
                            {
                                uint64_t x27_2 = 0;
                                
                                do
                                {
                                    if (sub_42d42c(x27_2, x19_3, x28_1, x23))
                                    {
                                        data_44677c = x27_2;
                                        uint64_t var_130_1 = x27_2;
                                        id obj_5 = _objc_retainAutoreleasedReturnValue(
                                            _objc_msgSend(clsRef_NSString, "stringWithFormat:"));
                                        sub_410c94(obj_5);
                                        _objc_release(obj_5);
                                        break;
                                    }
                                    
                                    x27_2 = x27_2 + 1;
                                } while (x27_2 != 0x14);
                            }
                            else
                                sub_42d42c(x0_40, x19_3, x28_1, x23);
                            
                            if (data_446ac9)
                            {
                                int32_t x27_3 = data_446acc;
                                int32_t x0_46 = data_446780;
                                
                                if (x0_46 & 0x80000000)
                                {
                                    uint64_t x20_4 = 0;
                                    
                                    do
                                    {
                                        if (sub_42da88(x20_4, x19_3, x27_3))
                                        {
                                            data_446780 = x20_4;
                                            uint64_t var_130_2 = x20_4;
                                            id obj_6 = _objc_retainAutoreleasedReturnValue(
                                                _objc_msgSend(clsRef_NSString, 
                                                "stringWithFormat:"));
                                            sub_410c94(obj_6);
                                            _objc_release(obj_6);
                                            break;
                                        }
                                        
                                        x20_4 = x20_4 + 1;
                                    } while (x20_4 != 0x14);
                                }
                                else
                                    sub_42da88(x0_46, x19_3, x27_3);
                            }
                            
                            if (!(data_44677c & 0x80000000))
                                break;
                            
                            x22_4 += 1;
                            
                            if (x22_4 == 3)
                            {
                                sub_410c94(
                                    &cfstr_[WARN]_All_20_color_approaches_failed_after_delays);
                                break;
                            }
                        }
                        
                        _objc_release(obj_4);
                        obj_12 = obj_2;
                        x27_1 = var_f0_1;
                    }
                    else
                    {
                        int128_t v2_1;
                        v2_1 = v8;
                        sub_4114c8(obj_12, v10);
                    }
                    
                    i += 1;
                } while (i != x27_1);
            }
        }
        else
        {
            int64_t x0_21;
            int128_t v0_1;
            x0_21 = sub_42172c(data_446b98);
            int64_t var_d8;
            
            if (data_446ad2 != 1)
            {
                v0_1 = 0x4020000000000000;
                var_d8 = 0x4020000000000000;
                int32_t var_d0_2 = 0;
            }
            else
            {
                var_d8 = data_446ad4;
                int32_t var_d0_1 = data_446adc;
            }
            
            var_a0 = data_42f160;
            int32_t var_dc = 0;
            id obj_7 = _objc_retain(obj_2);
            id obj = obj_7;
            
            if (_objc_msgSend(obj_7, "hasSuffix:", &cfstr_Controller))
            {
                obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_7, "substringToIndex:", 
                    _objc_msgSend(obj_7, "length") - 0xa));
                _objc_release(obj_7);
            }
            
            id x0_62 = _objc_msgSend(data_446a90, "indexOfObject:", obj_7);
            char x8_19;
            
            x8_19 = x0_62 == 0x7fffffffffffffff ? 0 : x0_62;
            
            char var_dd = x8_19;
            id var_128_2 = x27_1;
            uint64_t var_120_1 = x8_19;
            id obj_15 = obj_7;
            id obj_8 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
                "stringWithFormat:", &cfstr_Monster_'%@'_x%d_(id:%d)));
            sub_410c94(obj_8);
            _objc_release(obj_8);
            
            if (x27_1 >= 1)
            {
                int32_t i_1 = 0;
                
                do
                {
                    if (data_446778 & 0x80000000)
                    {
                        for (int64_t j = 0; j != 0xe0; j += 0x10)
                        {
                            uint64_t x24_3 = *(&data_43c930 + j);
                            id obj_10;
                            int64_t x0_77;
                            int64_t x1_5;
                            char** x2_13;
                            int64_t x26_2;
                            
                            if (x24_3 <= 0xd)
                                switch (x24_3)
                                {
                                    case 0:
                                    {
                                        if (data_446ba8)
                                        {
                                            int64_t x26_1 = data_446ba0;
                                            _objc_msgSend(_objc_retainAutorelease(obj_7), 
                                                "UTF8String");
                                            var_c8 = x26_1();
                                            int64_t* var_c0_2 = &var_d8;
                                            int128_t* var_b8_2 = &var_a0;
                                            int64_t var_b0_2 = 0;
                                            *(j + &data_43c938);
                                            
                                            if (sub_42d16c(data_446ba8, 0, &var_c8))
                                            {
                                                data_446778 = x24_3;
                                                goto label_426060;
                                            }
                                        }
                                        break;
                                    }
                                    case 1:
                                    {
                                        bool z_1;
                                        
                                        if (data_446ba8)
                                            z_1 = !x0_21;
                                        else
                                            z_1 = true;
                                        
                                        if (!z_1)
                                        {
                                            x26_2 = data_446ba0;
                                            obj_10 = obj_7;
                                        label_425c04:
                                            _objc_msgSend(_objc_retainAutorelease(obj_10), 
                                                "UTF8String");
                                            var_c8 = x26_2();
                                            int64_t* var_c0_8 = &var_d8;
                                            int128_t* var_b8_8 = &var_a0;
                                            int64_t var_b0_8 = 0;
                                            x0_77 = data_446ba8;
                                            goto label_425d48;
                                        }
                                        break;
                                    }
                                    case 2:
                                    {
                                        if (data_446bb0)
                                        {
                                            int64_t x26_3 = data_446ba0;
                                            _objc_msgSend(_objc_retainAutorelease(obj_7), 
                                                "UTF8String");
                                            var_c8 = x26_3();
                                            x0_77 = data_446bb0;
                                        label_425cf0:
                                            *(j + &data_43c938);
                                            x2_13 = &var_c8;
                                            x1_5 = 0;
                                        label_425d54:
                                            
                                            if (sub_42d16c(x0_77, x1_5, x2_13) & 1)
                                            {
                                                data_446778 = x24_3;
                                                goto label_426060;
                                            }
                                        }
                                        break;
                                    }
                                    case 3:
                                    {
                                        bool z_2;
                                        
                                        if (data_446bb0)
                                            z_2 = !x0_21;
                                        else
                                            z_2 = true;
                                        
                                        if (!z_2)
                                        {
                                            int64_t x26_4 = data_446ba0;
                                            _objc_msgSend(_objc_retainAutorelease(obj_7), 
                                                "UTF8String");
                                            var_c8 = x26_4();
                                            x0_77 = data_446bb0;
                                        label_425d48:
                                            *(j + &data_43c938);
                                            x2_13 = &var_c8;
                                            x1_5 = x0_21;
                                            goto label_425d54;
                                        }
                                        break;
                                    }
                                    case 4:
                                    {
                                        x0_77 = data_446bd8;
                                        
                                        if (x0_77)
                                        {
                                            var_c8 = &var_dd;
                                            int64_t* var_c0_3 = &var_d8;
                                            int128_t* var_b8_3 = &var_a0;
                                            int32_t* var_b0_3 = &var_dc;
                                            int64_t var_a8_1 = 0;
                                            goto label_425cf0;
                                        }
                                        break;
                                    }
                                    case 5:
                                    {
                                        x0_77 = data_446bd8;
                                        bool z_3;
                                        
                                        z_3 = x0_77 ? !x0_21 : true;
                                        
                                        if (!z_3)
                                        {
                                            var_c8 = &var_dd;
                                            int64_t* var_c0_4 = &var_d8;
                                            int128_t* var_b8_4 = &var_a0;
                                            int32_t* var_b0_4 = &var_dc;
                                            int64_t var_a8_2 = 0;
                                            goto label_425d48;
                                        }
                                        break;
                                    }
                                    case 6:
                                    {
                                        if (data_446bb8)
                                        {
                                            int64_t x26_5 = data_446ba0;
                                            _objc_msgSend(_objc_retainAutorelease(obj_7), 
                                                "UTF8String");
                                            var_c8 = x26_5();
                                            int64_t* var_c0_5 = &var_d8;
                                            int128_t* var_b8_5 = &var_a0;
                                            int64_t var_b0_5 = 0;
                                            x0_77 = data_446bb8;
                                            goto label_425cf0;
                                        }
                                        break;
                                    }
                                    case 7:
                                    {
                                        bool z_4;
                                        
                                        if (data_446bb8)
                                            z_4 = !x0_21;
                                        else
                                            z_4 = true;
                                        
                                        if (!z_4)
                                        {
                                            int64_t x26_6 = data_446ba0;
                                            _objc_msgSend(_objc_retainAutorelease(obj_7), 
                                                "UTF8String");
                                            var_c8 = x26_6();
                                            int64_t* var_c0_6 = &var_d8;
                                            int128_t* var_b8_6 = &var_a0;
                                            int64_t var_b0_6 = 0;
                                            x0_77 = data_446bb8;
                                            goto label_425d48;
                                        }
                                        break;
                                    }
                                    case 8:
                                    {
                                        if (data_446ba8)
                                        {
                                            int64_t x26_7 = data_446ba0;
                                            _objc_msgSend(_objc_retainAutorelease(obj), 
                                                "UTF8String");
                                            var_c8 = x26_7();
                                            int64_t* var_c0_7 = &var_d8;
                                            int128_t* var_b8_7 = &var_a0;
                                            int64_t var_b0_7 = 0;
                                            x0_77 = data_446ba8;
                                            goto label_425cf0;
                                        }
                                        break;
                                    }
                                    case 9:
                                    {
                                        bool z_5;
                                        
                                        if (data_446ba8)
                                            z_5 = !x0_21;
                                        else
                                            z_5 = true;
                                        
                                        if (!z_5)
                                        {
                                            x26_2 = data_446ba0;
                                            obj_10 = obj;
                                            goto label_425c04;
                                        }
                                        break;
                                    }
                                    case 0xa:
                                    {
                                        if (data_446be0)
                                        {
                                            int64_t x26_8 = data_446ba0;
                                            _objc_msgSend(_objc_retainAutorelease(obj_7), 
                                                "UTF8String");
                                            var_c8 = x26_8();
                                            int64_t* var_c0_9 = &var_d8;
                                            int128_t* var_b8_9 = &var_a0;
                                            int64_t var_b0_9 = 0;
                                            x0_77 = data_446be0;
                                            goto label_425cf0;
                                        }
                                        break;
                                    }
                                    case 0xb:
                                    {
                                        bool z_6;
                                        
                                        if (data_446be0)
                                            z_6 = !x0_21;
                                        else
                                            z_6 = true;
                                        
                                        if (!z_6)
                                        {
                                            int64_t x26_9 = data_446ba0;
                                            _objc_msgSend(_objc_retainAutorelease(obj_7), 
                                                "UTF8String");
                                            var_c8 = x26_9();
                                            int64_t* var_c0_10 = &var_d8;
                                            int128_t* var_b8_10 = &var_a0;
                                            int64_t var_b0_10 = 0;
                                            x0_77 = data_446be0;
                                            goto label_425d48;
                                        }
                                        break;
                                    }
                                    case 0xc:
                                    {
                                        if (data_446be8)
                                        {
                                            int64_t x26_10 = data_446ba0;
                                            _objc_msgSend(_objc_retainAutorelease(obj_7), 
                                                "UTF8String");
                                            var_c8 = x26_10();
                                            int64_t* var_c0_11 = &var_d8;
                                            int128_t* var_b8_11 = &var_a0;
                                            int64_t var_b0_11 = 0;
                                            x0_77 = data_446be8;
                                            goto label_425cf0;
                                        }
                                        break;
                                    }
                                    case 0xd:
                                    {
                                        bool z_7;
                                        
                                        if (data_446be8)
                                            z_7 = !x0_21;
                                        else
                                            z_7 = true;
                                        
                                        if (!z_7)
                                        {
                                            int64_t x26_11 = data_446ba0;
                                            _objc_msgSend(_objc_retainAutorelease(obj_7), 
                                                "UTF8String");
                                            var_c8 = x26_11();
                                            int64_t* var_c0_12 = &var_d8;
                                            int128_t* var_b8_12 = &var_a0;
                                            int64_t var_b0_12 = 0;
                                            x0_77 = data_446be8;
                                            goto label_425d48;
                                        }
                                        break;
                                    }
                                }
                        }
                        
                        if (data_446778 & 0x80000000)
                        {
                            id obj_16 = obj_7;
                            id obj_11 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(
                                clsRef_NSString, "stringWithFormat:"));
                            sub_410c94(obj_11);
                            _objc_release(obj_11);
                            break;
                        }
                    }
                    else
                    {
                        int64_t x24_2 = data_446ba0;
                        id obj_9 = _objc_retainAutorelease(obj_7);
                        _objc_msgSend(obj_9, "UTF8String");
                        char* x0_67 = x24_2();
                        uint64_t x8_22 = data_446778;
                        
                        if (x8_22 <= 0xd)
                        {
                            int64_t x0_68;
                            int64_t x1_4;
                            int64_t* x2_11;
                            
                            switch (x8_22)
                            {
                                case 0:
                                {
                                    var_c8 = x0_67;
                                    int64_t* var_c0_1 = &var_d8;
                                    int128_t* var_b8_1 = &var_a0;
                                    int64_t var_b0_1 = 0;
                                    x0_68 = data_446ba8;
                                    x2_11 = &var_c8;
                                    x1_4 = 0;
                                    break;
                                }
                                case 1:
                                {
                                    var_c8 = x0_67;
                                    int64_t* var_c0_13 = &var_d8;
                                    int128_t* var_b8_13 = &var_a0;
                                    int64_t var_b0_13 = 0;
                                    x0_68 = data_446ba8;
                                    x2_11 = &var_c8;
                                    x1_4 = x0_21;
                                    break;
                                }
                                case 2:
                                {
                                    var_c8 = x0_67;
                                    x0_68 = data_446bb0;
                                    x2_11 = &var_c8;
                                    x1_4 = 0;
                                    break;
                                }
                                case 3:
                                {
                                    var_c8 = x0_67;
                                    x0_68 = data_446bb0;
                                    x2_11 = &var_c8;
                                    x1_4 = x0_21;
                                    break;
                                }
                                case 4:
                                {
                                    var_c8 = &var_dd;
                                    int64_t* var_c0_14 = &var_d8;
                                    int128_t* var_b8_14 = &var_a0;
                                    int32_t* var_b0_14 = &var_dc;
                                    int64_t var_a8_3 = 0;
                                    x0_68 = data_446bd8;
                                    x2_11 = &var_c8;
                                    x1_4 = 0;
                                    break;
                                }
                                case 5:
                                {
                                    var_c8 = &var_dd;
                                    int64_t* var_c0_15 = &var_d8;
                                    int128_t* var_b8_15 = &var_a0;
                                    int32_t* var_b0_15 = &var_dc;
                                    int64_t var_a8_4 = 0;
                                    x0_68 = data_446bd8;
                                    x2_11 = &var_c8;
                                    x1_4 = x0_21;
                                    break;
                                }
                                case 6:
                                {
                                    var_c8 = x0_67;
                                    int64_t* var_c0_16 = &var_d8;
                                    int128_t* var_b8_16 = &var_a0;
                                    int64_t var_b0_16 = 0;
                                    x0_68 = data_446bb8;
                                    x2_11 = &var_c8;
                                    x1_4 = 0;
                                    break;
                                }
                                case 7:
                                {
                                    var_c8 = x0_67;
                                    int64_t* var_c0_17 = &var_d8;
                                    int128_t* var_b8_17 = &var_a0;
                                    int64_t var_b0_17 = 0;
                                    x0_68 = data_446bb8;
                                    x2_11 = &var_c8;
                                    x1_4 = x0_21;
                                    break;
                                }
                                case 8:
                                {
                                    int64_t x19_6 = data_446ba0;
                                    _objc_msgSend(_objc_retainAutorelease(obj), "UTF8String");
                                    var_c8 = x19_6();
                                    int64_t* var_c0_18 = &var_d8;
                                    int128_t* var_b8_18 = &var_a0;
                                    int64_t var_b0_18 = 0;
                                    x0_68 = data_446ba8;
                                    x2_11 = &var_c8;
                                    x1_4 = 0;
                                    break;
                                }
                                case 9:
                                {
                                    int64_t x19_7 = data_446ba0;
                                    _objc_msgSend(_objc_retainAutorelease(obj), "UTF8String");
                                    var_c8 = x19_7();
                                    int64_t* var_c0_19 = &var_d8;
                                    int128_t* var_b8_19 = &var_a0;
                                    int64_t var_b0_19 = 0;
                                    x0_68 = data_446ba8;
                                    x2_11 = &var_c8;
                                    x1_4 = x0_21;
                                    break;
                                }
                                case 0xa:
                                {
                                    int64_t x24_4 = data_446ba0;
                                    _objc_msgSend(_objc_retainAutorelease(obj_9), "UTF8String");
                                    var_c8 = x24_4();
                                    int64_t* var_c0_20 = &var_d8;
                                    int128_t* var_b8_20 = &var_a0;
                                    int64_t var_b0_20 = 0;
                                    x0_68 = data_446be0;
                                    x2_11 = &var_c8;
                                    x1_4 = 0;
                                    break;
                                }
                                case 0xb:
                                {
                                    int64_t x24_5 = data_446ba0;
                                    _objc_msgSend(_objc_retainAutorelease(obj_9), "UTF8String");
                                    var_c8 = x24_5();
                                    int64_t* var_c0_21 = &var_d8;
                                    int128_t* var_b8_21 = &var_a0;
                                    int64_t var_b0_21 = 0;
                                    x0_68 = data_446be0;
                                    x2_11 = &var_c8;
                                    x1_4 = x0_21;
                                    break;
                                }
                                case 0xc:
                                {
                                    int64_t x24_6 = data_446ba0;
                                    _objc_msgSend(_objc_retainAutorelease(obj_9), "UTF8String");
                                    var_c8 = x24_6();
                                    int64_t* var_c0_22 = &var_d8;
                                    int128_t* var_b8_22 = &var_a0;
                                    int64_t var_b0_22 = 0;
                                    x0_68 = data_446be8;
                                    x2_11 = &var_c8;
                                    x1_4 = 0;
                                    break;
                                }
                                case 0xd:
                                {
                                    int64_t x24_7 = data_446ba0;
                                    _objc_msgSend(_objc_retainAutorelease(obj_9), "UTF8String");
                                    var_c8 = x24_7();
                                    int64_t* var_c0_23 = &var_d8;
                                    int128_t* var_b8_23 = &var_a0;
                                    int64_t var_b0_23 = 0;
                                    x0_68 = data_446be8;
                                    x2_11 = &var_c8;
                                    x1_4 = x0_21;
                                    break;
                                }
                            }
                            
                            sub_42d16c(x0_68, x1_4, x2_11);
                        }
                    }
                    
                label_426060:
                    i_1 += 1;
                } while (i_1 != var_f0_1);
            }
            
            _objc_release(obj);
            obj_12 = obj_2;
        }
        _objc_release(obj_12);
        _objc_release(obj_12);
    }
    
    _objc_release(obj_13);
    
    if (*___stack_chk_guard == x8)
        return;
    
    ___stack_chk_fail();
    /* no return */
}

id -[ACPanelController makeCloseButton:](struct ACPanelController* self, SEL sel, void* makeCloseButton)
{
    id x0_2;
    int64_t x2;
    int128_t v0;
    int128_t v1;
    int128_t v2;
    int128_t v3;
    x0_2 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton, "buttonWithType:", 0));
    int64_t entry_v0;
    v0 = entry_v0;
    int64_t entry_v1;
    v1 = entry_v1;
    double entry_v2;
    v2 = entry_v2;
    double entry_v3;
    v3 = entry_v3;
    int64_t x2_1;
    int64_t x3;
    int64_t x4;
    int64_t x5;
    int128_t v0_1;
    int128_t v2_1;
    int128_t v3_1;
    x2_1 = _objc_msgSend(x0_2, "setFrame:", x2);
    v0_1 = 0x3fe6666666666666;
    v3_1 = 1.0;
    v2_1 = 0x3fc3333333333333;
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:", x2_1, x3, x4, x5));
    _objc_msgSend(x0_2, "setBackgroundColor:", obj);
    _objc_release(obj);
    id obj_1;
    int64_t x2_3;
    int128_t v0_3;
    obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(x0_2, "layer"));
    v0_3 = entry_v2 * 0.5;
    _objc_msgSend(obj_1, "setCornerRadius:", x2_3);
    _objc_release(obj_1);
    int64_t x2_4;
    int64_t x3_1;
    int64_t x4_1;
    int64_t x5_1;
    int128_t v0_4;
    int128_t v1_1;
    int128_t v2_2;
    int128_t v3_2;
    x2_4 = _objc_msgSend(x0_2, "setTitle:forState:", &cfstr_?, 0);
    v0_4 = 0x3feb333333333333;
    v1_1 = 0x3feccccccccccccd;
    v2_2 = 1.0;
    v3_2 = 1.0;
    id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:", x2_4, x3_1, x4_1, x5_1));
    _objc_msgSend(x0_2, "setTitleColor:forState:", obj_2, 0);
    int64_t x2_6;
    int128_t v0_5;
    x2_6 = _objc_release(obj_2);
    v0_5 = 18.0;
    id obj_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
        "boldSystemFontOfSize:", x2_6));
    id obj_4 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(x0_2, "titleLabel"));
    _objc_msgSend(obj_4, "setFont:", obj_3);
    _objc_release(obj_4);
    _objc_release(obj_3);
    _objc_msgSend(x0_2, "addTarget:action:forControlEvents:", self, "dismissPanel", 0x40);
    /* tailcall */
    return _objc_autoreleaseReturnValue(x0_2);
}

id -[ACPanelController tabButtonWithTitle:frame:](struct ACPanelController* self, SEL sel, id tabButtonWithTitle, void* frame)
{
    struct objc_class_t* clsRef_UIButton_1 = clsRef_UIButton;
    id obj = _objc_retain(tabButtonWithTitle);
    id x0_3;
    int64_t x2;
    int128_t v0;
    int128_t v1;
    int128_t v2;
    int128_t v3;
    x0_3 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIButton_1, "buttonWithType:", 0));
    int64_t entry_v0;
    v0 = entry_v0;
    int64_t entry_v1;
    v1 = entry_v1;
    int64_t entry_v2;
    v2 = entry_v2;
    int64_t entry_v3;
    v3 = entry_v3;
    _objc_msgSend(x0_3, "setFrame:", x2);
    _objc_msgSend(x0_3, "setTitle:forState:", obj, 0);
    int64_t x2_2;
    int128_t v0_1;
    x2_2 = _objc_release(obj);
    v0_1 = 11.0;
    id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
        "boldSystemFontOfSize:", x2_2));
    id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(x0_3, "titleLabel"));
    _objc_msgSend(obj_2, "setFont:", obj_1);
    _objc_release(obj_2);
    _objc_release(obj_1);
    id obj_3;
    int64_t x2_4;
    int128_t v0_2;
    obj_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(x0_3, "layer"));
    v0_2 = 10.0;
    _objc_msgSend(obj_3, "setCornerRadius:", x2_4);
    _objc_release(obj_3);
    id obj_4 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(x0_3, "titleLabel"));
    _objc_msgSend(obj_4, "setAdjustsFontSizeToFitWidth:", 1);
    _objc_release(obj_4);
    id obj_5;
    int64_t x2_5;
    int128_t v0_3;
    obj_5 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(x0_3, "titleLabel"));
    v0_3 = 0x3fe6666666666666;
    _objc_msgSend(obj_5, "setMinimumScaleFactor:", x2_5);
    _objc_release(obj_5);
    /* tailcall */
    return _objc_autoreleaseReturnValue(x0_3);
}

void -[ACPanelController updateTabAppearance](struct ACPanelController* self, SEL sel)
{
    int64_t x8 = *___stack_chk_guard;
    id x0;
    int64_t x2;
    int64_t x3;
    int64_t x4;
    int64_t x5;
    int128_t v0;
    int128_t v1;
    int128_t v2;
    int128_t v3;
    x0 = _objc_msgSend(self, "activeTab");
    
    if (!x0)
    {
        v0 = 0x3fb999999999999a;
        v2 = 0x3fe199999999999a;
        v1 = 0.25;
    }
    else
    {
        v0 = 0x3faeb851eb851eb8;
        v1 = 0x3fa999999999999a;
        v2 = 0x3fc3333333333333;
    }
    
    v3 = 1.0;
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:", x2, x3, x4, x5));
    id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "itemsTabBtn"));
    _objc_msgSend(obj_1, "setBackgroundColor:", obj);
    _objc_release(obj_1);
    _objc_release(obj);
    id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "itemsTabBtn"));
    id x0_10;
    int128_t v0_1;
    int128_t v1_1;
    int128_t v2_1;
    int128_t v3_1;
    x0_10 = _objc_msgSend(self, "activeTab");
    
    if (!x0_10)
    {
        v0_1 = 0x3feb333333333333;
        v1_1 = 0x3feccccccccccccd;
        v2_1 = 1.0;
    }
    else
    {
        v0_1 = 0x3fdccccccccccccd;
        v1_1 = 0x3fe199999999999a;
        v2_1 = 0x3fe6666666666666;
    }
    
    v3_1 = 1.0;
    id obj_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_2, "setTitleColor:forState:", obj_3, 0);
    _objc_release(obj_3);
    _objc_release(obj_2);
    id x0_17;
    int128_t v0_2;
    int128_t v1_2;
    int128_t v2_2;
    int128_t v3_2;
    x0_17 = _objc_msgSend(self, "activeTab");
    
    if (x0_17 != 1)
    {
        v0_2 = 0x3faeb851eb851eb8;
        v1_2 = 0x3fa999999999999a;
        v2_2 = 0x3fc3333333333333;
    }
    else
    {
        v0_2 = 0x3fb999999999999a;
        v2_2 = 0x3fe199999999999a;
        v1_2 = 0.25;
    }
    
    v3_2 = 1.0;
    id obj_4 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    id obj_5 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "monstersTabBtn"));
    _objc_msgSend(obj_5, "setBackgroundColor:", obj_4);
    _objc_release(obj_5);
    _objc_release(obj_4);
    id obj_6 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "monstersTabBtn"));
    id x0_27;
    int128_t v0_3;
    int128_t v1_3;
    int128_t v2_3;
    int128_t v3_3;
    x0_27 = _objc_msgSend(self, "activeTab");
    
    if (x0_27 != 1)
    {
        v0_3 = 0x3fdccccccccccccd;
        v1_3 = 0x3fe199999999999a;
        v2_3 = 0x3fe6666666666666;
    }
    else
    {
        v0_3 = 0x3feb333333333333;
        v1_3 = 0x3feccccccccccccd;
        v2_3 = 1.0;
    }
    
    v3_3 = 1.0;
    id obj_7 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_6, "setTitleColor:forState:", obj_7, 0);
    _objc_release(obj_7);
    _objc_release(obj_6);
    id x0_34;
    int128_t v0_4;
    int128_t v1_4;
    int128_t v2_4;
    int128_t v3_4;
    x0_34 = _objc_msgSend(self, "activeTab");
    
    if (x0_34 != 2)
    {
        v0_4 = 0x3faeb851eb851eb8;
        v1_4 = 0x3fa999999999999a;
        v2_4 = 0x3fc3333333333333;
    }
    else
    {
        v0_4 = 0x3fb999999999999a;
        v2_4 = 0x3fe199999999999a;
        v1_4 = 0.25;
    }
    
    v3_4 = 1.0;
    id obj_8 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    id obj_9 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "experimentTabBtn"));
    _objc_msgSend(obj_9, "setBackgroundColor:", obj_8);
    _objc_release(obj_9);
    _objc_release(obj_8);
    id obj_10 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "experimentTabBtn"));
    id x0_44;
    int128_t v0_5;
    int128_t v1_5;
    int128_t v2_5;
    int128_t v3_5;
    x0_44 = _objc_msgSend(self, "activeTab");
    
    if (x0_44 != 2)
    {
        v0_5 = 0x3fdccccccccccccd;
        v1_5 = 0x3fe199999999999a;
        v2_5 = 0x3fe6666666666666;
    }
    else
    {
        v0_5 = 0x3feb333333333333;
        v1_5 = 0x3feccccccccccccd;
        v2_5 = 1.0;
    }
    
    v3_5 = 1.0;
    id obj_11 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_10, "setTitleColor:forState:", obj_11, 0);
    _objc_release(obj_11);
    _objc_release(obj_10);
    id x0_51;
    int128_t v0_6;
    int128_t v1_6;
    int128_t v2_6;
    int128_t v3_6;
    x0_51 = _objc_msgSend(self, "activeTab");
    
    if (x0_51 != 3)
    {
        v0_6 = 0x3faeb851eb851eb8;
        v1_6 = 0x3fa999999999999a;
        v2_6 = 0x3fc3333333333333;
    }
    else
    {
        v0_6 = 0x3fb999999999999a;
        v2_6 = 0x3fe199999999999a;
        v1_6 = 0.25;
    }
    
    v3_6 = 1.0;
    id obj_12 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    id obj_13 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "settingsTabBtn"));
    _objc_msgSend(obj_13, "setBackgroundColor:", obj_12);
    _objc_release(obj_13);
    _objc_release(obj_12);
    id obj_14 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "settingsTabBtn"));
    id x0_61;
    int128_t v0_7;
    int128_t v1_7;
    int128_t v2_7;
    int128_t v3_7;
    x0_61 = _objc_msgSend(self, "activeTab");
    
    if (x0_61 != 3)
    {
        v0_7 = 0x3fdccccccccccccd;
        v1_7 = 0x3fe199999999999a;
        v2_7 = 0x3fe6666666666666;
    }
    else
    {
        v0_7 = 0x3feb333333333333;
        v1_7 = 0x3feccccccccccccd;
        v2_7 = 1.0;
    }
    
    v3_7 = 1.0;
    id obj_15 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_14, "setTitleColor:forState:", obj_15, 0);
    _objc_release(obj_15);
    _objc_release(obj_14);
    id obj_16 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "panelView"));
    id obj_17 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_16, "viewWithTag:", 0x37a));
    _objc_release(obj_16);
    id x0_72;
    int128_t v0_8;
    int128_t v1_8;
    int128_t v2_8;
    int128_t v3_8;
    x0_72 = _objc_msgSend(self, "activeTab");
    
    if (x0_72 != 4)
    {
        v0_8 = 0x3faeb851eb851eb8;
        v1_8 = 0x3fa999999999999a;
        v2_8 = 0x3fc3333333333333;
        v3_8 = 1.0;
    }
    else
    {
        v0_8 = 0x3fe6666666666666;
        v3_8 = 1.0;
        v2_8 = 0x3fb999999999999a;
    }
    
    id obj_18 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_17, "setBackgroundColor:", obj_18);
    _objc_release(obj_18);
    id x0_78;
    int128_t v0_9;
    int128_t v1_9;
    int128_t v2_9;
    int128_t v3_9;
    x0_78 = _objc_msgSend(self, "activeTab");
    
    if (x0_78 != 4)
    {
        v0_9 = 0x3fdccccccccccccd;
        v1_9 = 0x3fe199999999999a;
        v2_9 = 0x3fe6666666666666;
    }
    else
    {
        v0_9 = 0x3feb333333333333;
        v1_9 = 0x3feccccccccccccd;
        v2_9 = 1.0;
    }
    
    v3_9 = 1.0;
    id obj_19 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    _objc_msgSend(obj_17, "setTitleColor:forState:", obj_19, 0);
    _objc_release(obj_19);
    uint64_t x22_11;
    
    if (!_objc_msgSend(self, "activeTab"))
        x22_11 = 0;
    else
        x22_11 = _objc_msgSend(self, "activeTab") != 1 ? 1 : 0;
    
    id obj_20 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnerScroll"));
    _objc_msgSend(obj_20, "setHidden:", x22_11);
    _objc_release(obj_20);
    uint64_t x22_12 = _objc_msgSend(self, "activeTab") != 2 ? 1 : 0;
    id obj_21 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "experimentScroll"));
    _objc_msgSend(obj_21, "setHidden:", x22_12);
    _objc_release(obj_21);
    uint64_t x22_13 = _objc_msgSend(self, "activeTab") != 3 ? 1 : 0;
    id obj_22 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "settingsContent"));
    _objc_msgSend(obj_22, "setHidden:", x22_13);
    _objc_release(obj_22);
    uint64_t x22_14 = _objc_msgSend(self, "activeTab") != 4 ? 1 : 0;
    id obj_23 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "adminScroll"));
    _objc_msgSend(obj_23, "setHidden:", x22_14);
    _objc_release(obj_23);
    id obj_24 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnerInner"));
    id obj_25 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_24, "viewWithTag:"));
    _objc_release(obj_24);
    _objc_msgSend(obj_25, "setHidden:", _objc_msgSend(self, "activeTab") ? 1 : 0);
    int128_t var_120;
    __builtin_memset(&var_120, 0, 0x20);
    int128_t var_140;
    __builtin_memset(&var_140, 0, 0x18);
    id obj_26 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "categoryButtons"));
    void var_f0;
    id i_2 = _objc_msgSend(obj_26, "countByEnumeratingWithState:objects:count:", &var_140, &var_f0, 
        0x10);
    
    if (i_2)
    {
        id i_1 = i_2;
        int64_t* var_130;
        int64_t x23_5 = *var_130;
        id i;
        
        do
        {
            int64_t x21_1 = 0;
            
            do
            {
                if (*var_130 != x23_5)
                    _objc_enumerationMutation(obj_26);
                
                _objc_msgSend(*(*(&var_140 + 8) + (x21_1 << 3)), "setHidden:", 
                    _objc_msgSend(self, "activeTab") ? 1 : 0);
                x21_1 += 1;
            } while (i_1 != x21_1);
            
            i = _objc_msgSend(obj_26, "countByEnumeratingWithState:objects:count:", &var_140, 
                &var_f0, 0x10);
            i_1 = i;
        } while (i);
    }
    
    _objc_release(obj_26);
    id obj_27 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnerInner"));
    id obj_28 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_27, "viewWithTag:"));
    _objc_release(obj_27);
    id obj_29 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_28, "viewWithTag:"));
    struct __NSConstantString* const x2_22;
    
    if (!_objc_msgSend(self, "activeTab"))
        x2_22 = &cfstr_Item_Spawner;
    else
        x2_22 = &cfstr_Monster_Spawner;
    
    _objc_msgSend(obj_29, "setText:", x2_22);
    id x0_130 = _objc_alloc(clsRef_NSAttributedString);
    id x0_132;
    int128_t v0_10;
    int128_t v1_10;
    int128_t v2_10;
    int128_t v3_10;
    x0_132 = _objc_msgSend(self, "activeTab");
    struct __NSConstantString* const x25_6;
    
    x25_6 = !x0_132 ? &cfstr_Search_items... : &cfstr_Search_monsters...;
    
    struct objc_class* var_100 = *_NSForegroundColorAttributeName;
    v0_10 = 0x3fdccccccccccccd;
    v1_10 = 0x3fe199999999999a;
    v2_10 = 0x3fe6666666666666;
    v3_10 = 1.0;
    id obj_30 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
        "colorWithRed:green:blue:alpha:"));
    id obj_41 = obj_30;
    id obj_31 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSDictionary, 
        "dictionaryWithObjects:forKeys:count:", &obj_41, &var_100, 1));
    id obj_32 = _objc_msgSend(x0_130, "initWithString:attributes:", x25_6, obj_31);
    id obj_33 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "searchField"));
    _objc_msgSend(obj_33, "setAttributedPlaceholder:", obj_32);
    _objc_release(obj_33);
    _objc_release(obj_32);
    _objc_release(obj_31);
    _objc_release(obj_30);
    uint64_t x21_4 = _objc_msgSend(self, "activeTab") ? 1 : 0;
    id obj_34 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "heartBtn"));
    _objc_msgSend(obj_34, "setHidden:", x21_4);
    _objc_release(obj_34);
    uint64_t x21_5 = _objc_msgSend(self, "activeTab") ? 1 : 0;
    id obj_35 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "rainBtn"));
    _objc_msgSend(obj_35, "setHidden:", x21_5);
    _objc_release(obj_35);
    int64_t x21_6 = _objc_msgSend(self, "activeTab") ? 1 : 0;
    id obj_36 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "jsonBtn"));
    _objc_msgSend(obj_36, "setHidden:", x21_6);
    _objc_release(obj_36);
    id obj_37 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnerInner"));
    id obj_38 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_37, "viewWithTag:"));
    _objc_release(obj_37);
    _objc_msgSend(obj_38, "setHidden:", _objc_msgSend(self, "activeTab") ? 1 : 0);
    id obj_39 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "spawnerInner"));
    id obj_40 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_39, "viewWithTag:"));
    _objc_release(obj_39);
    _objc_msgSend(obj_40, "setHidden:", _objc_msgSend(self, "activeTab") ? 1 : 0);
    _objc_release(obj_40);
    _objc_release(obj_38);
    _objc_release(obj_29);
    _objc_release(obj_28);
    _objc_release(obj_25);
    _objc_release(obj_17);
    
    if (*___stack_chk_guard == x8)
        return;
    
    ___stack_chk_fail();
    /* no return */
}

void -[ACPanelController switchToItems](struct ACPanelController* self, SEL sel)
{
    _objc_msgSend(self, "setActiveTab:", 0);
    _objc_msgSend(self, "setActiveCategory:", 0);
    _objc_msgSend(self, "setSelectedIndex:", -1);
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "searchField"));
    _objc_msgSend(obj, "setText:", &cfstr_);
    _objc_release(obj);
    _objc_msgSend(self, "updateTabAppearance");
    _objc_msgSend(self, "updateCategoryAppearance");
    /* tailcall */
    return _objc_msgSend(self, "applyFilter");
}

void -[ACPanelController switchToMonsters](struct ACPanelController* self, SEL sel)
{
    _objc_msgSend(self, "setActiveTab:", 1);
    _objc_msgSend(self, "setSelectedIndex:", -1);
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "searchField"));
    _objc_msgSend(obj, "setText:", &cfstr_);
    _objc_release(obj);
    _objc_msgSend(self, "updateTabAppearance");
    /* tailcall */
    return _objc_msgSend(self, "applyFilter");
}

void -[ACPanelController switchToExperiment](struct ACPanelController* self, SEL sel)
{
    _objc_msgSend(self, "setActiveTab:", 2);
    /* tailcall */
    return _objc_msgSend(self, "updateTabAppearance");
}

void -[ACPanelController switchToSettings](struct ACPanelController* self, SEL sel)
{
    _objc_msgSend(self, "setActiveTab:", 3);
    /* tailcall */
    return _objc_msgSend(self, "updateTabAppearance");
}

void -[ACPanelController switchToAdmin](struct ACPanelController* self, SEL sel)
{
    uint8_t** const x8_1;
    
    if (data_446ad0 != 1)
        x8_1 = &selRef_showAdminPasscodePrompt;
    else
    {
        _objc_msgSend(self, "setActiveTab:", 4);
        x8_1 = &selRef_updateTabAppearance;
    }
    
    /* tailcall */
    return _objc_msgSend(self, *x8_1);
}

void -[ACPanelController categoryTapped:](struct ACPanelController* self, SEL sel, id categoryTapped)
{
    _objc_msgSend(self, "setActiveCategory:", _objc_msgSend(categoryTapped, "tag") - 0x384);
    _objc_msgSend(self, "setSelectedIndex:", -1);
    _objc_msgSend(self, "updateCategoryAppearance");
    /* tailcall */
    return _objc_msgSend(self, "applyFilter");
}

void -[ACPanelController updateCategoryAppearance](struct ACPanelController* self, SEL sel)
{
    int64_t v15;
    int64_t var_a0 = v15;
    int64_t v14;
    int64_t var_98 = v14;
    int64_t v13;
    int64_t var_90 = v13;
    int64_t v12;
    int64_t var_88 = v12;
    int64_t v11;
    int64_t var_80 = v11;
    int64_t v10;
    int64_t var_78 = v10;
    int64_t v9;
    int64_t var_70 = v9;
    int64_t v8;
    int64_t var_68 = v8;
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "categoryButtons"));
    id x0_1 = _objc_msgSend(obj, "count");
    _objc_release(obj);
    
    if (x0_1 < 1)
        return;
    
    int64_t x21_1 = 0;
    id x0_33;
    
    do
    {
        id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "categoryButtons"));
        id obj_2 =
            _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_1, "objectAtIndexedSubscript:"));
        _objc_release(obj_1);
        int64_t x0_8;
        int64_t x2_2;
        int64_t x3_1;
        int64_t x4_1;
        int64_t x5_1;
        int128_t v0_1;
        int128_t v1_1;
        int128_t v2_1;
        int128_t v3_1;
        x0_8 = _objc_msgSend(self, "activeCategory");
        struct objc_class_t* clsRef_UIColor_1 = clsRef_UIColor;
        struct objc_class_t* clsRef_UIColor_2;
        int64_t x2_6;
        int64_t x3_4;
        int64_t x4_3;
        int64_t x5_3;
        int128_t v2_3;
        
        if (x21_1 != x0_8)
        {
            id obj_5 =
                _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor_1, "clearColor"));
            _objc_msgSend(obj_2, "setBackgroundColor:");
            int64_t x2_8;
            int64_t x3_5;
            int64_t x4_4;
            int64_t x5_4;
            int128_t v0_4;
            int128_t v1_4;
            int128_t v2_4;
            int128_t v3_4;
            x2_8 = _objc_release(obj_5);
            v3_4 = 1.0;
            v0_4 = 0x3fdccccccccccccd;
            v1_4 = 0x3fe199999999999a;
            v2_4 = 0x3fe6666666666666;
            id obj_6 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
                "colorWithRed:green:blue:alpha:", x2_8, x3_5, x4_4, x5_4));
            _objc_msgSend(obj_2, "setTitleColor:forState:");
            int128_t v0_5;
            int128_t v1_5;
            int128_t v3_5;
            x2_6 = _objc_release(obj_6);
            clsRef_UIColor_2 = clsRef_UIColor;
            v3_5 = 0.5;
            v0_5 = 0x3fc999999999999a;
            v1_5 = 0x3fe3333333333333;
        }
        else
        {
            v1_1 = 0.25;
            v3_1 = 1.0;
            v0_1 = 0x3fb999999999999a;
            v2_1 = 0x3fe199999999999a;
            id obj_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor_1, 
                "colorWithRed:green:blue:alpha:", x2_2, x3_1, x4_1, x5_1));
            _objc_msgSend(obj_2, "setBackgroundColor:");
            int64_t x2_4;
            int64_t x3_2;
            int64_t x4_2;
            int64_t x5_2;
            int128_t v0_2;
            int128_t v1_2;
            int128_t v2_2;
            int128_t v3_2;
            x2_4 = _objc_release(obj_3);
            v3_2 = 1.0;
            v0_2 = 0x3fb999999999999a;
            v1_2 = 0x3fe999999999999a;
            v2_2 = 0x3fee666666666666;
            id obj_4 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
                "colorWithRed:green:blue:alpha:", x2_4, x3_2, x4_2, x5_2));
            _objc_msgSend(obj_2, "setTitleColor:forState:");
            int128_t v0_3;
            int128_t v1_3;
            int128_t v3_3;
            x2_6 = _objc_release(obj_4);
            clsRef_UIColor_2 = clsRef_UIColor;
            v3_3 = 1.0;
            v0_3 = 0x3fd999999999999a;
            v1_3 = 0x3fc999999999999a;
        }
        
        v2_3 = 0x3fee666666666666;
        id obj_7 = _objc_retainAutorelease(_objc_retainAutoreleasedReturnValue(_objc_msgSend(
            clsRef_UIColor_2, "colorWithRed:green:blue:alpha:", x2_6, x3_4, x4_3, x5_3)));
        _objc_msgSend(obj_7, "CGColor");
        id obj_8 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_2, "layer"));
        _objc_msgSend(obj_8, "setBorderColor:");
        _objc_release(obj_8);
        _objc_release(obj_7);
        _objc_release(obj_2);
        x21_1 += 1;
        id obj_9 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "categoryButtons"));
        x0_33 = _objc_msgSend(obj_9, "count");
        _objc_release(obj_9);
    } while (x21_1 < x0_33);
}

void -[ACPanelController increaseQty](struct ACPanelController* self, SEL sel)
{
    if (_objc_msgSend(self, "spawnQuantity") > 0x3e6)
        return;
    
    _objc_msgSend(self, "setSpawnQuantity:", &_objc_msgSend(self, "spawnQuantity")->isa + 1);
    struct objc_class_t* clsRef_NSString_1 = clsRef_NSString;
    id var_40 = _objc_msgSend(self, "spawnQuantity");
    id x0_8 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString_1, 
        "stringWithFormat:", &cfstr_%ld));
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "quantityLabel"));
    _objc_msgSend(obj, "setText:", x0_8);
    _objc_release(obj);
    /* tailcall */
    return _objc_release(x0_8);
}

void -[ACPanelController decreaseQty](struct ACPanelController* self, SEL sel)
{
    if (_objc_msgSend(self, "spawnQuantity") < 2)
        return;
    
    _objc_msgSend(self, "setSpawnQuantity:", _objc_msgSend(self, "spawnQuantity") - 1);
    struct objc_class_t* clsRef_NSString_1 = clsRef_NSString;
    id var_40 = _objc_msgSend(self, "spawnQuantity");
    id x0_8 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString_1, 
        "stringWithFormat:", &cfstr_%ld));
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "quantityLabel"));
    _objc_msgSend(obj, "setText:", x0_8);
    _objc_release(obj);
    /* tailcall */
    return _objc_release(x0_8);
}

void -[ACPanelController applyFilter](struct ACPanelController* self, SEL sel)
{
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "searchField"));
    id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj, "text"));
    id x0_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_1, "lowercaseString"));
    _objc_release(obj_1);
    _objc_release(obj);
    id obj_6;
    
    if (!_objc_msgSend(self, "activeTab"))
    {
        id obj_2 = _objc_retain(data_446a88);
        
        if (_objc_msgSend(self, "activeCategory") != 1)
        {
            if (_objc_msgSend(self, "activeCategory") != 2)
            {
                obj_6 = obj_2;
                
                if (_objc_msgSend(self, "activeCategory") == 3)
                {
                    obj_6 = _objc_retain(data_446ab8);
                    _objc_release(obj_2);
                }
            }
            else
            {
                obj_6 = _objc_retain(data_446ab0);
                _objc_release(obj_2);
            }
        }
        else
        {
            obj_6 = _objc_retain(data_446aa8);
            _objc_release(obj_2);
        }
        
        int64_t obj_7;
        
        if (!_objc_msgSend(x0_3, "length"))
        {
            id x0_39 = _objc_msgSend(obj_6, "copy");
            obj_7 = data_446a98;
            data_446a98 = x0_39;
        }
        else
        {
            id var_40_2 = x0_3;
            obj_7 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSPredicate, 
                "predicateWithFormat:", &cfstr_SELF_contains[cd]_%@));
            id x0_36 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_6, 
                "filteredArrayUsingPredicate:", obj_7));
            id obj_5 = data_446a98;
            data_446a98 = x0_36;
            _objc_release(obj_5);
        }
        
        _objc_release(obj_7);
    }
    else
    {
        id x0_9 = _objc_msgSend(x0_3, "length");
        id x22_1 = data_446a90;
        
        if (!x0_9)
        {
            id x0_21 = _objc_msgSend(x22_1, "copy");
            obj_6 = data_446aa0;
            data_446aa0 = x0_21;
        }
        else
        {
            id var_40_1 = x0_3;
            obj_6 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSPredicate, 
                "predicateWithFormat:", &cfstr_SELF_contains[cd]_%@));
            id x0_15 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(x22_1, 
                "filteredArrayUsingPredicate:", obj_6));
            int64_t obj_4 = data_446aa0;
            data_446aa0 = x0_15;
            _objc_release(obj_4);
        }
    }
    
    _objc_release(obj_6);
    _objc_msgSend(self, "updateItemCount");
    id obj_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "tableView"));
    _objc_msgSend(obj_3, "reloadData");
    _objc_release(obj_3);
    /* tailcall */
    return _objc_release(x0_3);
}

void -[ACPanelController searchChanged](struct ACPanelController* self, SEL sel)
{
    /* tailcall */
    return _objc_msgSend(self, "applyFilter");
}

void -[ACPanelController updateItemCount](struct ACPanelController* self, SEL sel)
{
    id x0_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "currentList"));
    struct __NSConstantString* const obj;
    
    if (!_objc_msgSend(self, "activeTab"))
        obj = &cfstr_items;
    else
        obj = &cfstr_monsters;
    
    struct objc_class_t* clsRef_NSString_1 = clsRef_NSString;
    id obj_1 = _objc_retain(obj);
    id var_50 = _objc_msgSend(x0_1, "count");
    id obj_4 = obj_1;
    id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString_1, 
        "stringWithFormat:", &cfstr_%lu_%@));
    _objc_release(obj_1);
    id obj_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "itemCountLabel"));
    _objc_msgSend(obj_3, "setText:", obj_2);
    _objc_release(obj_3);
    _objc_release(obj_2);
    /* tailcall */
    return _objc_release(x0_1);
}

bool -[ACPanelController textFieldShouldReturn:](struct ACPanelController* self, SEL sel, id textFieldShouldReturn)
{
    id obj = _objc_retain(textFieldShouldReturn);
    _objc_msgSend(textFieldShouldReturn, "resignFirstResponder");
    id x0_3 = _objc_msgSend(textFieldShouldReturn, "tag");
    _objc_release(obj);
    
    if (x0_3 == 0x37c)
        _objc_msgSend(self, "aiCommandTapped");
    
    return 1;
}

id -[ACPanelController currentList](struct ACPanelController* self, SEL sel)
{
    int64_t* x8;
    
    if (!_objc_msgSend(self, "activeTab"))
        x8 = &data_446a98;
    else
        x8 = &data_446aa0;
    
    /* tailcall */
    return _objc_retainAutoreleaseReturnValue(*x8);
}

int64_t -[ACPanelController tableView:numberOfRowsInSection:](struct ACPanelController* self, SEL sel, id tableView, int64_t numberOfRowsInSection)
{
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "currentList"));
    id result = _objc_msgSend(obj, "count");
    _objc_release(obj);
    return result;
}

double -[ACPanelController tableView:heightForRowAtIndexPath:](struct ACPanelController* self, SEL sel, id tableView, id heightForRowAtIndexPath) __pure
{
    return 0x4043000000000000;
}

id -[ACPanelController tableView:cellForRowAtIndexPath:](struct ACPanelController* self, SEL sel, id tableView, id cellForRowAtIndexPath)
{
    double v9;
    double var_70 = v9;
    double v8;
    double var_68 = v8;
    id obj = _objc_retain(cellForRowAtIndexPath);
    id x0_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(tableView, 
        "dequeueReusableCellWithIdentifier:", &cfstr_C));
    id x20_1;
    
    if (!x0_3)
    {
        x20_1 = _objc_msgSend(_objc_alloc(clsRef_UITableViewCell), 
            "initWithStyle:reuseIdentifier:", 0, &cfstr_C);
        id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, "clearColor"));
        _objc_msgSend(x20_1, "setBackgroundColor:", obj_1);
        _objc_release(obj_1);
        _objc_msgSend(x20_1, "setSelectionStyle:", 0);
        id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(x20_1, "textLabel"));
        _objc_msgSend(obj_2, "setTextAlignment:", 1);
        _objc_release(obj_2);
    }
    else
        x20_1 = x0_3;
    
    id obj_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "currentList"));
    id obj_4 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_3, 
        "objectAtIndexedSubscript:", _objc_msgSend(obj, "row")));
    _objc_release(obj_3);
    id obj_5 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(x20_1, "textLabel"));
    _objc_msgSend(obj_5, "setText:", obj_4);
    _objc_release(obj_5);
    id x0_26 = _objc_msgSend(obj, "row");
    id x0_28;
    int64_t x2_3;
    int128_t v0;
    x0_28 = _objc_msgSend(self, "selectedIndex");
    id obj_10;
    
    if (x0_26 != x0_28)
    {
        id x0_44 = _objc_msgSend(self, "selectedIndex");
        id x0_46 = _objc_msgSend(obj, "row");
        int64_t x2_8;
        
        if (x0_44 & 0x8000000000000000)
        {
            id obj_11 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "currentList"));
            v9 = fabs(x0_46 + _objc_msgSend(obj_11, "count") * -0.5);
            x2_8 = _objc_release(obj_11);
        }
        else
        {
            id x0_48;
            x0_48 = _objc_msgSend(self, "selectedIndex");
            int64_t x8_1 = x0_46 - x0_48;
            int64_t x8_2;
            
            x8_2 = x0_46 - x0_48 < 0 ? -(x8_1) : x8_1;
            
            v9 = x8_2;
        }
        
        double temp0_2 = vmaxnm_f64(vfma_f64(1.0, v9, -0.20000000000000001), 0.29999999999999999);
        vmaxnm_f64(vfma_f64(16.0, v9, -1.5), 12.0);
        id obj_12 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
            "systemFontOfSize:", x2_8));
        id obj_13 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(x20_1, "textLabel"));
        _objc_msgSend(obj_13, "setFont:", obj_12);
        _objc_release(obj_13);
        int64_t x2_10;
        int64_t x3_2;
        int64_t x4_2;
        int64_t x5_2;
        int128_t v0_5;
        int128_t v1_5;
        int128_t v2_2;
        int128_t v3_2;
        x2_10 = _objc_release(obj_12);
        v0_5 = 0x3fdccccccccccccd;
        v1_5 = 0x3fe199999999999a;
        v2_2 = 0x3fe6666666666666;
        v3_2 = 1.0;
        id obj_14;
        int64_t x2_11;
        int128_t v0_6;
        obj_14 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
            "colorWithRed:green:blue:alpha:", x2_10, x3_2, x4_2, x5_2));
        v0_6 = temp0_2;
        int64_t obj_15 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_14, 
            "colorWithAlphaComponent:", x2_11));
        id obj_16 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(x20_1, "textLabel"));
        _objc_msgSend(obj_16, "setTextColor:", obj_15);
        _objc_release(obj_16);
        _objc_release(obj_15);
        _objc_release(obj_14);
        obj_10 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, "clearColor"));
    }
    else
    {
        v0 = 16.0;
        id obj_6 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
            "boldSystemFontOfSize:", x2_3));
        id obj_7 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(x20_1, "textLabel"));
        _objc_msgSend(obj_7, "setFont:", obj_6);
        _objc_release(obj_7);
        int64_t x2_5;
        int64_t x3;
        int64_t x4;
        int64_t x5;
        int128_t v0_1;
        int128_t v1_1;
        int128_t v2;
        int128_t v3;
        x2_5 = _objc_release(obj_6);
        v0_1 = 0x3feb333333333333;
        v1_1 = 0x3feccccccccccccd;
        v2 = 1.0;
        v3 = 1.0;
        id obj_8 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
            "colorWithRed:green:blue:alpha:", x2_5, x3, x4, x5));
        id obj_9 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(x20_1, "textLabel"));
        _objc_msgSend(obj_9, "setTextColor:", obj_8);
        _objc_release(obj_9);
        int64_t x2_7;
        int64_t x3_1;
        int64_t x4_1;
        int64_t x5_1;
        int128_t v0_2;
        int128_t v1_2;
        int128_t v2_1;
        int128_t v3_1;
        x2_7 = _objc_release(obj_8);
        v0_2 = 0x3fb999999999999a;
        v1_2 = 0x3fc3333333333333;
        v2_1 = 0x3fd6666666666666;
        v3_1 = 1.0;
        obj_10 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
            "colorWithRed:green:blue:alpha:", x2_7, x3_1, x4_1, x5_1));
    }
    
    id obj_17 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(x20_1, "contentView"));
    _objc_msgSend(obj_17, "setBackgroundColor:", obj_10);
    _objc_release(obj_17);
    _objc_release(obj_10);
    _objc_release(obj_4);
    _objc_release(obj);
    /* tailcall */
    return _objc_autoreleaseReturnValue(x20_1);
}

void -[ACPanelController tableView:didSelectRowAtIndexPath:](struct ACPanelController* self, SEL sel, id tableView, id didSelectRowAtIndexPath)
{
    id obj = _objc_retain(didSelectRowAtIndexPath);
    id x0_2 = _objc_retain(tableView);
    _objc_msgSend(self, "setSelectedIndex:", _objc_msgSend(didSelectRowAtIndexPath, "row"));
    _objc_msgSend(tableView, "reloadData");
    _objc_msgSend(tableView, "scrollToRowAtIndexPath:atScrollPosition:animated:", obj, 2, 1);
    _objc_release(obj);
    /* tailcall */
    return _objc_release(x0_2);
}

void -[ACPanelController dismissPanel](struct ACPanelController* self, SEL sel)
{
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "loopTimer"));
    _objc_release(obj);
    
    if (obj)
    {
        id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "loopTimer"));
        _objc_msgSend(obj_1, "invalidate");
        _objc_release(obj_1);
        _objc_msgSend(self, "setLoopTimer:", 0);
    }
    
    id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "rainTimer"));
    int64_t x4;
    int128_t v0;
    x4 = _objc_release(obj_2);
    
    if (obj_2)
    {
        id obj_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(self, "rainTimer"));
        _objc_msgSend(obj_3, "invalidate");
        _objc_release(obj_3);
        x4 = _objc_msgSend(self, "setRainTimer:", 0);
    }
    
    struct objc_class_t* clsRef_UIView_1 = clsRef_UIView;
    struct ACPanelController* self_1 = self;
    void* (* const var_58)[0x20] = __NSConcreteStackBlock;
    v0 = 0xc2000000;
    int64_t var_50 = 0xc2000000;
    int64_t (* var_48)(void* arg1) = sub_4284ec;
    void* const var_40 = &data_43c090;
    struct ACPanelController* self_2 = self;
    void* (* const var_80)[0x20] = __NSConcreteStackBlock;
    int64_t var_78 = 0xc2000000;
    int64_t (* var_70)(void* arg1) = sub_4285a4;
    void* const var_68 = &data_43c530;
    v0 = 0x3fc999999999999a;
    _objc_msgSend(clsRef_UIView_1, "animateWithDuration:animations:completion:", &var_58, &var_80, 
        x4);
}

int64_t sub_4284ec(void* arg1)
{
    _CGAffineTransformMakeScale(0x3feb333333333333, 0x3feb333333333333);
    id obj;
    int128_t v0_1;
    int128_t v1_1;
    obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(*(arg1 + 0x20), "panelView"));
    int128_t var_60;
    int128_t var_90 = var_60;
    int128_t var_50;
    int128_t var_80 = var_50;
    int128_t var_40;
    int128_t var_70 = var_40;
    _objc_msgSend(obj, "setTransform:", &var_90);
    _objc_release(obj);
    id obj_1;
    int64_t x2_1;
    int128_t v0_2;
    obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(*(arg1 + 0x20), "panelView"));
    v0_2 = 0.0;
    _objc_msgSend(obj_1, "setAlpha:", x2_1);
    return _objc_release(obj_1);
}

int64_t sub_4285a4(void* arg1)
{
    /* tailcall */
    return _objc_msgSend(*(arg1 + 0x20), "dismissViewControllerAnimated:completion:", 0, 0);
}

bool -[ACPanelController prefersStatusBarHidden](struct ACPanelController* self, SEL sel) __pure
{
    return 0;
}

uint64_t -[ACPanelController supportedInterfaceOrientations](struct ACPanelController* self, SEL sel) __pure
{
    return 0x1e;
}

id -[ACPanelController panelView](struct ACPanelController* self, SEL sel)
{
    return self->_panelView;
}

void -[ACPanelController setPanelView:](struct ACPanelController* self, SEL sel, id panelView)
{
    /* tailcall */
    return _objc_storeStrong(&self->_panelView, panelView);
}

id -[ACPanelController spawnerScroll](struct ACPanelController* self, SEL sel)
{
    return self->_spawnerScroll;
}

void -[ACPanelController setSpawnerScroll:](struct ACPanelController* self, SEL sel, id spawnerScroll)
{
    /* tailcall */
    return _objc_storeStrong(&self->_spawnerScroll, spawnerScroll);
}

id -[ACPanelController spawnerInner](struct ACPanelController* self, SEL sel)
{
    return *(self + data_446670[0]);
}

void -[ACPanelController setSpawnerInner:](struct ACPanelController* self, SEL sel, id spawnerInner)
{
    /* tailcall */
    return _objc_storeStrong(self + data_446670[0], spawnerInner);
}

id -[ACPanelController tableView](struct ACPanelController* self, SEL sel)
{
    return *(self + data_446670[1]);
}

void -[ACPanelController setTableView:](struct ACPanelController* self, SEL sel, id tableView)
{
    /* tailcall */
    return _objc_storeStrong(self + data_446670[1], tableView);
}

id -[ACPanelController searchField](struct ACPanelController* self, SEL sel)
{
    return *(self + data_446670[2]);
}

void -[ACPanelController setSearchField:](struct ACPanelController* self, SEL sel, id searchField)
{
    /* tailcall */
    return _objc_storeStrong(self + data_446670[2], searchField);
}

int64_t -[ACPanelController activeTab](struct ACPanelController* self, SEL sel)
{
    return *(self + data_446670[3]);
}

void -[ACPanelController setActiveTab:](struct ACPanelController* self, SEL sel, int64_t activeTab)
{
    *(self + data_446670[3]) = activeTab;
}

int64_t -[ACPanelController activeCategory](struct ACPanelController* self, SEL sel)
{
    return *(self + data_446670[4]);
}

void -[ACPanelController setActiveCategory:](struct ACPanelController* self, SEL sel, int64_t activeCategory)
{
    *(self + data_446670[4]) = activeCategory;
}

int64_t -[ACPanelController spawnQuantity](struct ACPanelController* self, SEL sel)
{
    return *(self + data_446670[5]);
}

void -[ACPanelController setSpawnQuantity:](struct ACPanelController* self, SEL sel, int64_t spawnQuantity)
{
    *(self + data_446670[5]) = spawnQuantity;
}

int64_t -[ACPanelController selectedIndex](struct ACPanelController* self, SEL sel)
{
    return *(self + data_446670[6]);
}

void -[ACPanelController setSelectedIndex:](struct ACPanelController* self, SEL sel, int64_t selectedIndex)
{
    *(self + data_446670[6]) = selectedIndex;
}

id -[ACPanelController itemsTabBtn](struct ACPanelController* self, SEL sel)
{
    return *(self + data_446670[7]);
}

void -[ACPanelController setItemsTabBtn:](struct ACPanelController* self, SEL sel, id itemsTabBtn)
{
    /* tailcall */
    return _objc_storeStrong(self + data_446670[7], itemsTabBtn);
}

id -[ACPanelController monstersTabBtn](struct ACPanelController* self, SEL sel)
{
    return *(self + data_446670[8]);
}

void -[ACPanelController setMonstersTabBtn:](struct ACPanelController* self, SEL sel, id monstersTabBtn)
{
    /* tailcall */
    return _objc_storeStrong(self + data_446670[8], monstersTabBtn);
}

id -[ACPanelController experimentTabBtn](struct ACPanelController* self, SEL sel)
{
    return *(self + data_446670[9]);
}

void -[ACPanelController setExperimentTabBtn:](struct ACPanelController* self, SEL sel, id experimentTabBtn)
{
    /* tailcall */
    return _objc_storeStrong(self + data_446670[9], experimentTabBtn);
}

id -[ACPanelController settingsTabBtn](struct ACPanelController* self, SEL sel)
{
    return *(self + data_446670[0xa]);
}

void -[ACPanelController setSettingsTabBtn:](struct ACPanelController* self, SEL sel, id settingsTabBtn)
{
    /* tailcall */
    return _objc_storeStrong(self + data_446670[0xa], settingsTabBtn);
}

id -[ACPanelController quantityLabel](struct ACPanelController* self, SEL sel)
{
    return *(self + data_446670[0xb]);
}

void -[ACPanelController setQuantityLabel:](struct ACPanelController* self, SEL sel, id quantityLabel)
{
    /* tailcall */
    return _objc_storeStrong(self + data_446670[0xb], quantityLabel);
}

id -[ACPanelController itemCountLabel](struct ACPanelController* self, SEL sel)
{
    return self->_itemCountLabel;
}

void -[ACPanelController setItemCountLabel:](struct ACPanelController* self, SEL sel, id itemCountLabel)
{
    /* tailcall */
    return _objc_storeStrong(&self->_itemCountLabel, itemCountLabel);
}

id -[ACPanelController locationLabel](struct ACPanelController* self, SEL sel)
{
    return self->_locationLabel;
}

void -[ACPanelController setLocationLabel:](struct ACPanelController* self, SEL sel, id locationLabel)
{
    /* tailcall */
    return _objc_storeStrong(&self->_locationLabel, locationLabel);
}

id -[ACPanelController categoryButtons](struct ACPanelController* self, SEL sel)
{
    return self->_categoryButtons;
}

void -[ACPanelController setCategoryButtons:](struct ACPanelController* self, SEL sel, id categoryButtons)
{
    /* tailcall */
    return _objc_storeStrong(&self->_categoryButtons, categoryButtons);
}

id -[ACPanelController settingsContent](struct ACPanelController* self, SEL sel)
{
    return self->_settingsContent;
}

void -[ACPanelController setSettingsContent:](struct ACPanelController* self, SEL sel, id settingsContent)
{
    /* tailcall */
    return _objc_storeStrong(&self->_settingsContent, settingsContent);
}

id -[ACPanelController experimentScroll](struct ACPanelController* self, SEL sel)
{
    return self->_experimentScroll;
}

void -[ACPanelController setExperimentScroll:](struct ACPanelController* self, SEL sel, id experimentScroll)
{
    /* tailcall */
    return _objc_storeStrong(&self->_experimentScroll, experimentScroll);
}

id -[ACPanelController experimentInner](struct ACPanelController* self, SEL sel)
{
    return self->_experimentInner;
}

void -[ACPanelController setExperimentInner:](struct ACPanelController* self, SEL sel, id experimentInner)
{
    /* tailcall */
    return _objc_storeStrong(&self->_experimentInner, experimentInner);
}

id -[ACPanelController logView](struct ACPanelController* self, SEL sel)
{
    return self->_logView;
}

void -[ACPanelController setLogView:](struct ACPanelController* self, SEL sel, id logView)
{
    /* tailcall */
    return _objc_storeStrong(&self->_logView, logView);
}

id -[ACPanelController loopSwitch](struct ACPanelController* self, SEL sel)
{
    return self->_loopSwitch;
}

void -[ACPanelController setLoopSwitch:](struct ACPanelController* self, SEL sel, id loopSwitch)
{
    /* tailcall */
    return _objc_storeStrong(&self->_loopSwitch, loopSwitch);
}

id -[ACPanelController heartLoopSwitch](struct ACPanelController* self, SEL sel)
{
    return self->_heartLoopSwitch;
}

void -[ACPanelController setHeartLoopSwitch:](struct ACPanelController* self, SEL sel, id heartLoopSwitch)
{
    /* tailcall */
    return _objc_storeStrong(&self->_heartLoopSwitch, heartLoopSwitch);
}

id -[ACPanelController loopTimer](struct ACPanelController* self, SEL sel)
{
    return self->_loopTimer;
}

void -[ACPanelController setLoopTimer:](struct ACPanelController* self, SEL sel, id loopTimer)
{
    /* tailcall */
    return _objc_storeStrong(&self->_loopTimer, loopTimer);
}

id -[ACPanelController rainTimer](struct ACPanelController* self, SEL sel)
{
    return self->_rainTimer;
}

void -[ACPanelController setRainTimer:](struct ACPanelController* self, SEL sel, id rainTimer)
{
    /* tailcall */
    return _objc_storeStrong(&self->_rainTimer, rainTimer);
}

int32_t -[ACPanelController rainRemaining](struct ACPanelController* self, SEL sel)
{
    return self->_rainRemaining;
}

void -[ACPanelController setRainRemaining:](struct ACPanelController* self, SEL sel, int32_t rainRemaining)
{
    self->_rainRemaining = rainRemaining;
}

id -[ACPanelController spawnBtn](struct ACPanelController* self, SEL sel)
{
    return self->_spawnBtn;
}

void -[ACPanelController setSpawnBtn:](struct ACPanelController* self, SEL sel, id spawnBtn)
{
    /* tailcall */
    return _objc_storeStrong(&self->_spawnBtn, spawnBtn);
}

id -[ACPanelController heartBtn](struct ACPanelController* self, SEL sel)
{
    return self->_heartBtn;
}

void -[ACPanelController setHeartBtn:](struct ACPanelController* self, SEL sel, id heartBtn)
{
    /* tailcall */
    return _objc_storeStrong(&self->_heartBtn, heartBtn);
}

id -[ACPanelController rainBtn](struct ACPanelController* self, SEL sel)
{
    return self->_rainBtn;
}

void -[ACPanelController setRainBtn:](struct ACPanelController* self, SEL sel, id rainBtn)
{
    /* tailcall */
    return _objc_storeStrong(&self->_rainBtn, rainBtn);
}

id -[ACPanelController jsonBtn](struct ACPanelController* self, SEL sel)
{
    return self->_jsonBtn;
}

void -[ACPanelController setJsonBtn:](struct ACPanelController* self, SEL sel, id jsonBtn)
{
    /* tailcall */
    return _objc_storeStrong(&self->_jsonBtn, jsonBtn);
}

id -[ACPanelController redSlider](struct ACPanelController* self, SEL sel)
{
    return self->_redSlider;
}

void -[ACPanelController setRedSlider:](struct ACPanelController* self, SEL sel, id redSlider)
{
    /* tailcall */
    return _objc_storeStrong(&self->_redSlider, redSlider);
}

id -[ACPanelController greenSlider](struct ACPanelController* self, SEL sel)
{
    return self->_greenSlider;
}

void -[ACPanelController setGreenSlider:](struct ACPanelController* self, SEL sel, id greenSlider)
{
    /* tailcall */
    return _objc_storeStrong(&self->_greenSlider, greenSlider);
}

id -[ACPanelController colorPreview](struct ACPanelController* self, SEL sel)
{
    return self->_colorPreview;
}

void -[ACPanelController setColorPreview:](struct ACPanelController* self, SEL sel, id colorPreview)
{
    /* tailcall */
    return _objc_storeStrong(&self->_colorPreview, colorPreview);
}

id -[ACPanelController randomColorSwitch](struct ACPanelController* self, SEL sel)
{
    return self->_randomColorSwitch;
}

void -[ACPanelController setRandomColorSwitch:](struct ACPanelController* self, SEL sel, id randomColorSwitch)
{
    /* tailcall */
    return _objc_storeStrong(&self->_randomColorSwitch, randomColorSwitch);
}

id -[ACPanelController adminScroll](struct ACPanelController* self, SEL sel)
{
    return self->_adminScroll;
}

void -[ACPanelController setAdminScroll:](struct ACPanelController* self, SEL sel, id adminScroll)
{
    /* tailcall */
    return _objc_storeStrong(&self->_adminScroll, adminScroll);
}

id -[ACPanelController adminInner](struct ACPanelController* self, SEL sel)
{
    return self->_adminInner;
}

void -[ACPanelController setAdminInner:](struct ACPanelController* self, SEL sel, id adminInner)
{
    /* tailcall */
    return _objc_storeStrong(&self->_adminInner, adminInner);
}

id -[ACPanelController connectedUsersContainer](struct ACPanelController* self, SEL sel)
{
    return self->_connectedUsersContainer;
}

void -[ACPanelController setConnectedUsersContainer:](struct ACPanelController* self, SEL sel, id connectedUsersContainer)
{
    /* tailcall */
    return _objc_storeStrong(&self->_connectedUsersContainer, connectedUsersContainer);
}

void -[ACPanelController .cxx_destruct](struct ACPanelController* self, SEL sel)
{
    _objc_storeStrong(&self->_connectedUsersContainer, nullptr);
    _objc_storeStrong(&self->_adminInner, nullptr);
    _objc_storeStrong(&self->_adminScroll, nullptr);
    _objc_storeStrong(&self->_randomColorSwitch, nullptr);
    _objc_storeStrong(&self->_colorPreview, nullptr);
    _objc_storeStrong(&self->_greenSlider, nullptr);
    _objc_storeStrong(&self->_redSlider, nullptr);
    _objc_storeStrong(&self->_jsonBtn, nullptr);
    _objc_storeStrong(&self->_rainBtn, nullptr);
    _objc_storeStrong(&self->_heartBtn, nullptr);
    _objc_storeStrong(&self->_spawnBtn, nullptr);
    _objc_storeStrong(&self->_rainTimer, nullptr);
    _objc_storeStrong(&self->_loopTimer, nullptr);
    _objc_storeStrong(&self->_heartLoopSwitch, nullptr);
    _objc_storeStrong(&self->_loopSwitch, nullptr);
    _objc_storeStrong(&self->_logView, nullptr);
    _objc_storeStrong(&self->_experimentInner, nullptr);
    _objc_storeStrong(&self->_experimentScroll, nullptr);
    _objc_storeStrong(&self->_settingsContent, nullptr);
    _objc_storeStrong(&self->_categoryButtons, nullptr);
    _objc_storeStrong(&self->_locationLabel, nullptr);
    _objc_storeStrong(&self->_itemCountLabel, nullptr);
    _objc_storeStrong(self + data_446670[0xb], nullptr);
    _objc_storeStrong(self + data_446670[0xa], nullptr);
    _objc_storeStrong(self + data_446670[9], nullptr);
    _objc_storeStrong(self + data_446670[8], nullptr);
    _objc_storeStrong(self + data_446670[7], nullptr);
    _objc_storeStrong(self + data_446670[2], nullptr);
    _objc_storeStrong(self + data_446670[1], nullptr);
    _objc_storeStrong(self + data_446670[0], nullptr);
    _objc_storeStrong(&self->_spawnerScroll, nullptr);
    /* tailcall */
    return _objc_storeStrong(&self->_panelView, nullptr);
}

void +[ACPanelController openMenu](struct ACPanelController* self, SEL sel)
{
    id x0_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(data_446b80, "window"));
    
    if (x0_2)
    {
        id obj_4 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(x0_2, "rootViewController"));
        id obj_3 = obj_4;
        id obj =
            _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_4, "presentedViewController"));
        _objc_release(obj);
        
        if (obj)
        {
            id obj_5;
            id obj_1;
            
            do
            {
                obj_5 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_3, 
                    "presentedViewController"));
                _objc_release(obj_3);
                obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_5, 
                    "presentedViewController"));
                _objc_release(obj_1);
                obj_3 = obj_5;
            } while (obj_1);
            obj_3 = obj_5;
        }
        
        int64_t obj_2 = _objc_alloc_init(clsRef_ACPanelController);
        _objc_msgSend(obj_2, "setModalPresentationStyle:", 5);
        _objc_msgSend(obj_2, "setModalTransitionStyle:", 2);
        _objc_msgSend(obj_3, "presentViewController:animated:completion:", obj_2, 1, 0);
        _objc_release(obj_2);
        _objc_release(obj_3);
    }
    
    /* tailcall */
    return _objc_release(x0_2);
}

void +[ACPanelController handleDrag:](struct ACPanelController* self, SEL sel, id handleDrag)
{
    double v10;
    double var_58 = v10;
    double v9;
    double var_50 = v9;
    double v8;
    double var_48 = v8;
    id x0_1 = _objc_retain(handleDrag);
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(x0_1, "view"));
    id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj, "superview"));
    
    if (obj_1)
    {
        if (_objc_msgSend(x0_1, "state") != 1)
        {
            if (_objc_msgSend(x0_1, "state") == 2)
            {
                double v0_2;
                double v1_2;
                v0_2 = _objc_msgSend(x0_1, "locationInView:", obj_1);
                v10 = v0_2 - data_446b88;
                double v0_3 = _objc_msgSend(obj_1, "bounds") - _objc_msgSend(obj, "frame");
                
                if (v10 < v0_3)
                    v0_3 = v10;
                
                double temp0_1 = vmaxnm_f64(v0_3, 0.0);
                v10 = v1_2 - data_446b90;
                double v0_4 = _objc_msgSend(obj_1, "bounds") - _objc_msgSend(obj, "frame") + -20.0;
                
                if (v10 < v0_4)
                    v0_4 = v10;
                
                double temp0_2 = vmaxnm_f64(v0_4, 0x4044000000000000);
                double v2_3 = _objc_msgSend(obj, "frame");
                int64_t x2_2;
                int128_t v0_5;
                int128_t v1_5;
                int128_t v2_4;
                x2_2 = _objc_msgSend(obj, "frame");
                v0_5 = temp0_1;
                v1_5 = temp0_2;
                v2_4 = v2_3;
                _objc_msgSend(obj, "setFrame:", x2_2);
            }
        }
        else
        {
            int64_t v0_1;
            int64_t v1_1;
            v0_1 = _objc_msgSend(x0_1, "locationInView:", obj);
            data_446b88 = v0_1;
            data_446b90 = v1_1;
        }
    }
    
    _objc_release(obj_1);
    _objc_release(obj);
    /* tailcall */
    return _objc_release(x0_1);
}

int64_t mod_init_func_0()
{
    _objc_autorelease(__dispatch_main_q);
    _dispatch_async(__dispatch_main_q, &data_43c560);
    /* tailcall */
    return _dispatch_after(_dispatch_time(0, 0x12a05f200), __dispatch_main_q, &data_43c5b0);
}

int64_t sub_4290dc()
{
    int64_t v15;
    int64_t var_a0 = v15;
    double v14;
    double var_98 = v14;
    double v13;
    double var_90 = v13;
    double v12;
    double var_88 = v12;
    double v11;
    double var_80 = v11;
    double v10;
    double var_78 = v10;
    double v9;
    double var_70 = v9;
    double v8;
    double var_68 = v8;
    int64_t x8 = *___stack_chk_guard;
    int128_t var_1f0;
    __builtin_memset(&var_1f0, 0, 0x18);
    int128_t var_1d0;
    __builtin_memset(&var_1d0, 0, 0x20);
    id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIApplication, 
        "sharedApplication"));
    id obj_31 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_1, "connectedScenes"));
    _objc_release(obj_1);
    void var_130;
    id i_4 = _objc_msgSend(obj_31, "countByEnumeratingWithState:objects:count:", &var_1f0, 
        &var_130, 0x10);
    int64_t result;
    
    if (!i_4)
        result = _objc_release(obj_31);
    else
    {
        id i_2 = i_4;
        id obj = nullptr;
        int64_t* var_1e0;
        int64_t x24_1 = *var_1e0;
        id i;
        
        do
        {
            int64_t x25_1 = 0;
            
            do
            {
                if (*var_1e0 != x24_1)
                    _objc_enumerationMutation(obj_31);
                
                void* x26_1 = *(*(&var_1f0 + 8) + (x25_1 << 3));
                _objc_msgSend(clsRef_UIWindowScene, "class");
                
                if (_objc_msgSend(x26_1, "isKindOfClass:"))
                {
                    int128_t var_210;
                    __builtin_memset(&var_210, 0, 0x20);
                    int128_t var_230;
                    __builtin_memset(&var_230, 0, 0x18);
                    id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(x26_1, "windows"));
                    int64_t j_2 =
                        _objc_msgSend(obj_2, "countByEnumeratingWithState:objects:count:");
                    
                    if (j_2)
                    {
                        int64_t j_1 = j_2;
                        int64_t* var_220;
                        int64_t x21_1 = *var_220;
                        int64_t j;
                        
                        do
                        {
                            int64_t x20_1 = 0;
                            
                            do
                            {
                                if (*var_220 != x21_1)
                                    _objc_enumerationMutation(obj_2);
                                
                                id obj_29 = *(*(&var_230 + 8) + (x20_1 << 3));
                                
                                if (_objc_msgSend(obj_29, "isKeyWindow"))
                                {
                                    id obj_32 = _objc_retain(obj_29);
                                    _objc_release(obj);
                                    obj = obj_32;
                                    goto label_4292ec;
                                }
                                
                                x20_1 += 1;
                            } while (j_1 != x20_1);
                            
                            j = _objc_msgSend(obj_2, "countByEnumeratingWithState:objects:count:");
                            j_1 = j;
                        } while (j);
                    }
                    
                label_4292ec:
                    _objc_release(obj_2);
                }
                
                x25_1 += 1;
            } while (x25_1 != i_2);
            
            i = _objc_msgSend(obj_31, "countByEnumeratingWithState:objects:count:");
            i_2 = i;
        } while (i);
        result = _objc_release(obj_31);
        
        if (obj)
        {
            id obj_3;
            int64_t x2_3;
            int64_t x3_1;
            int64_t x4_4;
            int64_t x5_1;
            int128_t v0_1;
            int128_t v1_1;
            int128_t v2_1;
            obj_3 = _objc_msgSend(_objc_alloc(clsRef_UIView), "initWithFrame:", 
                _objc_msgSend(obj, "bounds"));
            v0_1 = 0x3f9eb851eb851eb8;
            v1_1 = 0x3f947ae147ae147b;
            v2_1 = 0x3fb47ae147ae147b;
            id obj_4 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
                "colorWithRed:green:blue:alpha:", x2_3, x3_1, x4_4, x5_1));
            _objc_msgSend(obj_3, "setBackgroundColor:", obj_4);
            _objc_release(obj_4);
            _objc_msgSend(obj_3, "setTag:", 0x1869f);
            int32_t i_3 = 0x28;
            int32_t i_1;
            
            do
            {
                v10 = _arc4random_uniform(vcvtd_s32_f64(_objc_msgSend(obj_3, "bounds")));
                v11 = _arc4random_uniform(vcvtd_s32_f64(_objc_msgSend(obj_3, "bounds")));
                v12 = _arc4random_uniform(3) + 1.0;
                id x0_39;
                int64_t x2_5;
                int128_t v0_3;
                int128_t v1_2;
                int128_t v2_3;
                int128_t v3_2;
                x0_39 = _objc_alloc(clsRef_UIView);
                v0_3 = v10;
                v1_2 = v11;
                v2_3 = v12;
                v3_2 = v12;
                id obj_5 = _objc_msgSend(x0_39, "initWithFrame:", x2_5);
                struct objc_class_t* clsRef_UIColor_1 = clsRef_UIColor;
                uint32_t x0_40;
                int64_t x2_6;
                int64_t x3_2;
                x0_40 = _arc4random_uniform(0x46);
                id obj_6 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor_1, 
                    "colorWithWhite:alpha:", x2_6, x3_2));
                _objc_msgSend(obj_5, "setBackgroundColor:");
                _objc_release(obj_6);
                id obj_7;
                int64_t x2_8;
                int128_t v0_5;
                obj_7 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_5, "layer"));
                v0_5 = v12 * 0.5;
                _objc_msgSend(obj_7, "setCornerRadius:", x2_8);
                _objc_release(obj_7);
                _objc_msgSend(obj_3, "addSubview:", obj_5);
                _objc_release(obj_5);
                i_1 = i_3;
                i_3 -= 1;
            } while (i_1 != 1);
            id x0_51 = _objc_alloc(clsRef_UILabel);
            v11 = _objc_msgSend(obj_3, "bounds") * 0.34999999999999998;
            int64_t x2_10;
            int128_t v0_6;
            int128_t v1_4;
            int128_t v3_4;
            x2_10 = _objc_msgSend(obj_3, "bounds");
            v10 = 0x4049000000000000;
            v0_6 = 0.0;
            v1_4 = v11;
            v3_4 = v10;
            id obj_8 = _objc_msgSend(x0_51, "initWithFrame:", x2_10);
            int64_t x2_11;
            int64_t x3_3;
            int128_t v0_7;
            int128_t v1_5;
            x2_11 = _objc_msgSend(obj_8, "setText:", &cfstr_?_?rbit);
            v1_5 = *_UIFontWeightHeavy;
            v0_7 = 0x4042000000000000;
            id obj_9 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
                "systemFontOfSize:weight:", x2_11, x3_3));
            _objc_msgSend(obj_8, "setFont:", obj_9);
            int128_t v0_8;
            int128_t v1_6;
            int128_t v2_4;
            int128_t v3_5;
            v0_8 = _objc_release(obj_9);
            v0_8 = 0x3feb333333333333;
            v1_6 = 0x3feccccccccccccd;
            v2_4 = 1.0;
            v3_5 = 1.0;
            id obj_10 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
                "colorWithRed:green:blue:alpha:"));
            _objc_msgSend(obj_8, "setTextColor:", obj_10);
            _objc_release(obj_10);
            _objc_msgSend(obj_8, "setTextAlignment:", 1);
            _objc_msgSend(obj_3, "addSubview:", obj_8);
            id x0_66 = _objc_alloc(clsRef_UILabel);
            double temp0_3 = vfma_f64(v10, _objc_msgSend(obj_3, "bounds"), 0.34999999999999998);
            int128_t v0_9;
            int128_t v1_7;
            int128_t v3_7;
            v0_9 = _objc_msgSend(obj_3, "bounds");
            v0_9 = 0.0;
            v3_7 = 30.0;
            v1_7 = temp0_3;
            id obj_11 = _objc_msgSend(x0_66, "initWithFrame:");
            int64_t x2_15;
            int64_t x3_4;
            int128_t v0_10;
            int128_t v1_8;
            x2_15 = _objc_msgSend(obj_11, "setText:", &cfstr_Loading_menu...);
            v10 = *_UIFontWeightMedium;
            v0_10 = 16.0;
            v1_8 = v10;
            id obj_12 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
                "systemFontOfSize:weight:", x2_15, x3_4));
            _objc_msgSend(obj_11, "setFont:", obj_12);
            int128_t v0_11;
            int128_t v1_9;
            int128_t v3_8;
            v0_11 = _objc_release(obj_12);
            v0_11 = 0x3fdccccccccccccd;
            v3_8 = 1.0;
            v1_9 = 0x3fe199999999999a;
            id obj_13 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
                "colorWithRed:green:blue:alpha:"));
            _objc_msgSend(obj_11, "setTextColor:", obj_13);
            _objc_release(obj_13);
            _objc_msgSend(obj_11, "setTextAlignment:", 1);
            _objc_msgSend(obj_3, "addSubview:");
            id obj_14 = _objc_msgSend(_objc_alloc(clsRef_UIActivityIndicatorView), 
                "initWithActivityIndicatorStyle:", 0x65);
            v9 = 0.5;
            v13 = _objc_msgSend(obj_3, "bounds") * v9;
            int64_t x2_19;
            int128_t v0_12;
            int128_t v1_10;
            int64_t v3_9;
            x2_19 = _objc_msgSend(obj_3, "bounds");
            v1_10 = v3_9 * 0.55000000000000004;
            v0_12 = v13;
            int128_t v0_13;
            int128_t v1_11;
            int128_t v2_6;
            int128_t v3_10;
            v0_13 = _objc_msgSend(obj_14, "setCenter:", x2_19);
            v3_10 = 1.0;
            v0_13 = 0x3fc999999999999a;
            v1_11 = 0x3fe3333333333333;
            v2_6 = 0x3fee666666666666;
            int64_t obj_30 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
                "colorWithRed:green:blue:alpha:"));
            _objc_msgSend(obj_14, "setColor:", obj_30);
            _objc_release(obj_30);
            _objc_msgSend(obj_14, "startAnimating");
            _objc_msgSend(obj_3, "addSubview:");
            v12 = (_objc_msgSend(obj_3, "bounds") + -0x3f97000000000000) * v9;
            v13 = _objc_msgSend(obj_3, "bounds") * 0.65000000000000002;
            id x0_95;
            int128_t v0_15;
            int128_t v1_12;
            int128_t v2_8;
            int128_t v3_12;
            x0_95 = _objc_alloc(clsRef_UIView);
            v2_8 = 0x4069000000000000;
            v3_12 = 4.0;
            v0_15 = v12;
            v1_12 = v13;
            id obj_15;
            int64_t x2_22;
            int64_t x3_5;
            int128_t v0_16;
            int128_t v1_13;
            obj_15 = _objc_msgSend(x0_95, "initWithFrame:");
            v0_16 = 0x3fc3333333333333;
            v1_13 = 1.0;
            id obj_16 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
                "colorWithWhite:alpha:", x2_22, x3_5));
            _objc_msgSend(obj_15, "setBackgroundColor:");
            _objc_release(obj_16);
            id obj_17;
            int64_t x2_24;
            int128_t v0_17;
            obj_17 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_15, "layer"));
            v0_17 = 2.0;
            _objc_msgSend(obj_17, "setCornerRadius:", x2_24);
            _objc_release(obj_17);
            _objc_msgSend(obj_3, "addSubview:");
            id x0_105;
            int128_t v0_18;
            int128_t v1_14;
            int128_t v2_9;
            int128_t v3_13;
            x0_105 = _objc_alloc(clsRef_UIView);
            v2_9 = 0.0;
            v3_13 = 4.0;
            v0_18 = v12;
            v1_14 = v13;
            id obj_18;
            int128_t v0_19;
            int128_t v1_15;
            int128_t v2_10;
            int128_t v3_14;
            obj_18 = _objc_msgSend(x0_105, "initWithFrame:");
            v3_14 = 1.0;
            v0_19 = 0x3fc999999999999a;
            v1_15 = 0x3fe3333333333333;
            v2_10 = 0x3fee666666666666;
            id obj_19 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
                "colorWithRed:green:blue:alpha:"));
            _objc_msgSend(obj_18, "setBackgroundColor:");
            _objc_release(obj_19);
            id obj_20;
            int64_t x2_27;
            int128_t v0_20;
            obj_20 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_18, "layer"));
            v0_20 = 2.0;
            _objc_msgSend(obj_20, "setCornerRadius:", x2_27);
            _objc_release(obj_20);
            _objc_msgSend(obj_3, "addSubview:");
            id x0_115 = _objc_alloc(clsRef_UILabel);
            v9 = _objc_msgSend(obj_3, "bounds") * 0.75;
            int128_t v0_22;
            int128_t v1_16;
            int128_t v3_16;
            v0_22 = _objc_msgSend(obj_3, "bounds");
            v0_22 = 0.0;
            v3_16 = 20.0;
            v1_16 = v9;
            id obj_21 = _objc_msgSend(x0_115, "initWithFrame:");
            int128_t v0_23;
            int128_t v1_17;
            v0_23 = _objc_msgSend(obj_21, "setText:");
            v0_23 = 12.0;
            v1_17 = v10;
            id obj_22 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
                "systemFontOfSize:weight:"));
            _objc_msgSend(obj_21, "setFont:");
            int128_t v0_24;
            int128_t v1_18;
            int128_t v2_11;
            int128_t v3_17;
            v0_24 = _objc_release(obj_22);
            v3_17 = 1.0;
            v0_24 = 0x3fd3333333333333;
            v1_18 = 0x3fd999999999999a;
            v2_11 = 0x3fe3333333333333;
            id obj_23 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
                "colorWithRed:green:blue:alpha:"));
            _objc_msgSend(obj_21, "setTextColor:");
            _objc_release(obj_23);
            _objc_msgSend(obj_21, "setTextAlignment:");
            _objc_msgSend(obj_3, "addSubview:");
            id x0_130 = _objc_alloc(clsRef_UILabel);
            v8 = _objc_msgSend(obj_3, "bounds") + -0x3fb2000000000000;
            int128_t v0_26;
            int128_t v1_19;
            int128_t v3_19;
            v0_26 = _objc_msgSend(obj_3, "bounds");
            v0_26 = 0.0;
            v3_19 = 20.0;
            v1_19 = v8;
            id obj_24 = _objc_msgSend(x0_130, "initWithFrame:");
            int128_t v0_27;
            int128_t v1_20;
            v0_27 = _objc_msgSend(obj_24, "setText:");
            v0_27 = 11.0;
            v1_20 = v10;
            id obj_25 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIFont, 
                "systemFontOfSize:weight:"));
            _objc_msgSend(obj_24, "setFont:");
            int128_t v0_28;
            int128_t v1_21;
            int128_t v2_12;
            int128_t v3_20;
            v0_28 = _objc_release(obj_25);
            v0_28 = 0.25;
            v3_20 = 1.0;
            v1_21 = 0x3fd999999999999a;
            v2_12 = 0x3fe6666666666666;
            id obj_26 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIColor, 
                "colorWithRed:green:blue:alpha:"));
            _objc_msgSend(obj_24, "setTextColor:");
            _objc_release(obj_26);
            _objc_msgSend(obj_24, "setTextAlignment:");
            _objc_msgSend(obj_3, "addSubview:");
            _objc_msgSend(obj, "addSubview:");
            struct objc_class_t* clsRef_UIView_1 = clsRef_UIView;
            void* (* const var_278)[0x20] = __NSConcreteStackBlock;
            int64_t var_270_1 = 0xc2000000;
            int64_t (* var_268_1)(void* arg1) = sub_429df4;
            void* const var_260_1 = &data_43c580;
            double var_250_1 = v12;
            double var_248_1 = v13;
            int128_t var_240_1 = data_42f150;
            id obj_27;
            int64_t x5_2;
            int64_t x6_1;
            int128_t v0_30;
            int128_t v1_22;
            obj_27 = _objc_retain(obj_18);
            v0_30 = 5.0;
            v1_22 = 0.0;
            _objc_msgSend(clsRef_UIView_1, 
                "animateWithDuration:delay:options:animations:completion:", 0, &var_278, 0, x5_2, 
                x6_1);
            struct objc_class_t* clsRef_UIView_2 = clsRef_UIView;
            void* (* const var_2a0)[0x20] = __NSConcreteStackBlock;
            int64_t var_298_1 = 0xc2000000;
            int64_t (* var_290_1)(void* arg1) = sub_429e0c;
            void* const var_288_1 = &data_43c090;
            id obj_28;
            int64_t x5_3;
            int64_t x6_2;
            int128_t v0_31;
            int128_t v1_23;
            obj_28 = _objc_retain(obj_8);
            v0_31 = 0x3ff3333333333333;
            v1_23 = 0.0;
            _objc_msgSend(clsRef_UIView_2, 
                "animateWithDuration:delay:options:animations:completion:", 0x18, &var_2a0, 0, 
                x5_3, x6_2);
            _objc_release(obj_8);
            _objc_release(obj_18);
            _objc_release(obj_28);
            _objc_release(obj_27);
            _objc_release(obj_24);
            _objc_release(obj_21);
            _objc_release(obj_15);
            _objc_release(obj_14);
            _objc_release(obj_11);
            _objc_release(obj_3);
            result = _objc_release(obj);
        }
    }
    
    if (*___stack_chk_guard == x8)
        return result;
    
    ___stack_chk_fail();
    /* no return */
}

int64_t sub_429df4(void* arg1)
{
    int128_t v0;
    v0 = *(arg1 + 0x28);
    int128_t v1;
    v1 = *(arg1 + 0x30);
    int128_t v2;
    v2 = *(arg1 + 0x38);
    int128_t v3;
    v3 = *(arg1 + 0x40);
    int64_t entry_x2;
    /* tailcall */
    return _objc_msgSend(*(arg1 + 0x20), "setFrame:", entry_x2);
}

int64_t sub_429e0c(void* arg1)
{
    int128_t v0;
    v0 = 0.5;
    int64_t entry_x2;
    /* tailcall */
    return _objc_msgSend(*(arg1 + 0x20), "setAlpha:", entry_x2);
}

int64_t sub_429e20()
{
    double height;
    double height_1 = height;
    double width;
    double width_1 = width;
    int64_t v8;
    int64_t var_68 = v8;
    int64_t x8 = *___stack_chk_guard;
    int128_t var_dc0;
    __builtin_memset(&var_dc0, 0, 0x18);
    int128_t var_da0;
    __builtin_memset(&var_da0, 0, 0x20);
    id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIApplication, 
        "sharedApplication"));
    id obj_62 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_1, "connectedScenes"));
    _objc_release(obj_1);
    void var_c58;
    id i_6 = _objc_msgSend(obj_62, "countByEnumeratingWithState:objects:count:", &var_dc0, 
        &var_c58, 0x10);
    id obj;
    
    if (!i_6)
    {
        obj = nullptr;
        _objc_release(obj_62);
    }
    else
    {
        id i_3 = i_6;
        obj = nullptr;
        int64_t* var_db0;
        int64_t x19_1 = *var_db0;
        id i;
        
        do
        {
            int64_t x23_1 = 0;
            
            do
            {
                if (*var_db0 != x19_1)
                    _objc_enumerationMutation(obj_62);
                
                void* x26_1 = *(*(&var_dc0 + 8) + (x23_1 << 3));
                _objc_msgSend(clsRef_UIWindowScene, "class");
                
                if (_objc_msgSend(x26_1, "isKindOfClass:"))
                {
                    int128_t var_de0;
                    __builtin_memset(&var_de0, 0, 0x20);
                    int128_t var_e00;
                    __builtin_memset(&var_e00, 0, 0x18);
                    id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(x26_1, "windows"));
                    int64_t j_4 =
                        _objc_msgSend(obj_2, "countByEnumeratingWithState:objects:count:");
                    
                    if (j_4)
                    {
                        int64_t j_3 = j_4;
                        int64_t* var_df0;
                        int64_t x25 = *var_df0;
                        int64_t j;
                        
                        do
                        {
                            int64_t x20_1 = 0;
                            
                            do
                            {
                                if (*var_df0 != x25)
                                    _objc_enumerationMutation(obj_2);
                                
                                id obj_58 = *(*(&var_e00 + 8) + (x20_1 << 3));
                                
                                if (_objc_msgSend(obj_58, "isKeyWindow"))
                                {
                                    id obj_76 = _objc_retain(obj_58);
                                    _objc_release(obj);
                                    obj = obj_76;
                                    goto label_42a038;
                                }
                                
                                x20_1 += 1;
                            } while (j_3 != x20_1);
                            
                            j = _objc_msgSend(obj_2, "countByEnumeratingWithState:objects:count:");
                            j_3 = j;
                        } while (j);
                    }
                    
                label_42a038:
                    _objc_release(obj_2);
                }
                
                x23_1 += 1;
            } while (x23_1 != i_3);
            
            i = _objc_msgSend(obj_62, "countByEnumeratingWithState:objects:count:");
            i_3 = i;
        } while (i);
        _objc_release(obj_62);
        
        if (!obj)
            obj = nullptr;
        else
        {
            id obj_3 =
                _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj, "viewWithTag:", 0x1869f));
            
            if (obj_3)
            {
                struct objc_class_t* clsRef_UIView_1 = clsRef_UIView;
                void* (* const var_e28)[0x20] = __NSConcreteStackBlock;
                int64_t var_e20_1 = 0xc2000000;
                int64_t (* var_e18_1)(void* arg1) = sub_42c9a0;
                void* const var_e10_1 = &data_43c090;
                id obj_4 = _objc_retain(obj_3);
                void* (* const var_e50)[0x20] = __NSConcreteStackBlock;
                int64_t var_e48_1 = 0xc2000000;
                int64_t (* var_e40_1)(void* arg1) = sub_42c9b4;
                void* const var_e38_1 = &data_43c530;
                id obj_5;
                int64_t x4_4;
                int128_t v0_1;
                obj_5 = _objc_retain(obj_4);
                v0_1 = 0.5;
                _objc_msgSend(clsRef_UIView_1, "animateWithDuration:animations:completion:", 
                    &var_e28, &var_e50, x4_4);
                _objc_release(obj_5);
                _objc_release(obj_4);
            }
            
            _objc_release(obj_3);
        }
    }
    
    id x0_30 = _objc_msgSend(clsRef_NSMutableString, "new");
    id obj_45 = data_446a78;
    data_446a78 = x0_30;
    _objc_release(obj_45);
    sub_410c94(&cfstr_[?rbit_V7]_Init...);
    void* __handle = _dlopen("UnityFramework.framework/UnityFramework", 0x11);
    
    if (!__handle)
    {
        int32_t i_1 = __dyld_image_count();
        
        if (i_1)
        {
            uint64_t x22_2 = 0;
            
            do
            {
                char* x0_33 = __dyld_get_image_name(x22_2);
                
                if (x0_33 && _strstr(x0_33, "UnityFramework"))
                {
                    __handle = _dlopen(x0_33, 0x11);
                    
                    if (__handle)
                        goto label_42a190;
                }
                
                x22_2 = x22_2 + 1;
            } while (i_1 != x22_2);
        }
        
        __handle = _dlopen(nullptr, 1);
        data_446bf0 = __handle;
        
        if (__handle)
            goto label_42a1fc;
        
        sub_410c94(&cfstr_[ERR]_IL2CPP_init_failed);
    }
    else
    {
    label_42a190:
        data_446bf0 = __handle;
    label_42a1fc:
        char const* const x21_3 = "il2cpp_domain_get";
        void* x0_36 = _dlsym(__handle, "il2cpp_domain_get");
        data_446bf8 = x0_36;
        
        if (!x0_36)
        {
        label_42a944:
            _NSLog(&cfstr_[ACCompanion]_Missing:_%s, x21_3);
            sub_410c94(&cfstr_[ERR]_IL2CPP_init_failed);
        }
        else
        {
            x21_3 = "il2cpp_domain_get_assemblies";
            void* x0_38 = _dlsym(data_446bf0, "il2cpp_domain_get_assemblies");
            data_446c00 = x0_38;
            
            if (!x0_38)
                goto label_42a944;
            
            x21_3 = "il2cpp_assembly_get_image";
            void* x0_40 = _dlsym(data_446bf0, "il2cpp_assembly_get_image");
            data_446c08 = x0_40;
            
            if (!x0_40)
                goto label_42a944;
            
            x21_3 = "il2cpp_image_get_name";
            void* x0_42 = _dlsym(data_446bf0, "il2cpp_image_get_name");
            data_446c10 = x0_42;
            
            if (!x0_42)
                goto label_42a944;
            
            x21_3 = "il2cpp_class_from_name";
            void* x0_44 = _dlsym(data_446bf0, "il2cpp_class_from_name");
            data_446ae0 = x0_44;
            
            if (!x0_44)
                goto label_42a944;
            
            x21_3 = "il2cpp_class_get_method_from_name";
            void* x0_46 = _dlsym(data_446bf0, "il2cpp_class_get_method_from_name");
            data_446b10 = x0_46;
            
            if (!x0_46)
                goto label_42a944;
            
            x21_3 = "il2cpp_string_new";
            void* x0_48 = _dlsym(data_446bf0, "il2cpp_string_new");
            data_446ba0 = x0_48;
            
            if (!x0_48)
                goto label_42a944;
            
            x21_3 = "il2cpp_runtime_invoke";
            void* x0_50 = _dlsym(data_446bf0, "il2cpp_runtime_invoke");
            data_446b08 = x0_50;
            
            if (!x0_50)
                goto label_42a944;
            
            x21_3 = "il2cpp_resolve_icall";
            void* x0_52 = _dlsym(data_446bf0, "il2cpp_resolve_icall");
            data_446c18 = x0_52;
            
            if (!x0_52)
                goto label_42a944;
            
            x21_3 = "il2cpp_class_get_field_from_name";
            void* x0_54 = _dlsym(data_446bf0, "il2cpp_class_get_field_from_name");
            data_446b18 = x0_54;
            
            if (!x0_54)
                goto label_42a944;
            
            x21_3 = "il2cpp_field_get_value";
            void* x0_56 = _dlsym(data_446bf0, "il2cpp_field_get_value");
            data_446b20 = x0_56;
            
            if (!x0_56)
                goto label_42a944;
            
            x21_3 = "il2cpp_field_set_value";
            void* x0_58 = _dlsym(data_446bf0, "il2cpp_field_set_value");
            data_446b70 = x0_58;
            
            if (!x0_58)
                goto label_42a944;
            
            x21_3 = "il2cpp_class_get_type";
            void* x0_60 = _dlsym(data_446bf0, "il2cpp_class_get_type");
            data_446af8 = x0_60;
            
            if (!x0_60)
                goto label_42a944;
            
            x21_3 = "il2cpp_type_get_object";
            void* x0_62 = _dlsym(data_446bf0, "il2cpp_type_get_object");
            data_446b00 = x0_62;
            
            if (!x0_62)
                goto label_42a944;
            
            int64_t x0_63 = sub_42dec0("AnimalCompany.dll");
            data_446ae8 = x0_63;
            int64_t x0_64;
            
            if (!x0_63)
            {
                x0_64 = sub_42dec0("Assembly-CSharp.dll");
                data_446ae8 = x0_64;
            }
            
            struct __NSConstantString* const x0_323;
            
            if (!x0_63 && !x0_64)
            {
                x0_323 = &cfstr_[ERR]_Game_assembly_not_found;
            label_42c974:
                sub_410c94(x0_323);
                sub_410c94(&cfstr_[WARN]_Game_classes_failed_?_spawning_may_not_work);
            }
            else
            {
                int64_t x0_65 = sub_42dec0("UnityEngine.CoreModule.dll");
                data_446c20 = x0_65;
                
                if (!x0_65)
                {
                    x0_323 = &cfstr_[ERR]_Unity_engine_image_not_found;
                    goto label_42c974;
                }
                
                int64_t x0_67 = data_446ae0(data_446ae8, &cstr_, "PrefabGenerator");
                data_446b98 = x0_67;
                
                if (x0_67)
                {
                label_42a464:
                    data_446ba8 = data_446b10(x0_67, "SpawnItem", 4);
                    data_446bb0 = data_446b10(data_446b98, "SpawnItem", 1);
                    data_446bb8 = data_446b10(data_446b98, "SpawnItem", 0xffffffff);
                    data_446c28 = data_446b10(data_446b98, "GetItemPrefab", 1);
                    data_446bd8 = data_446b10(data_446b98, "SpawnMob", 5);
                    data_446c30 = data_446b10(data_446b98, "GetMobPrefab", 1);
                    data_446be0 = data_446b10(data_446b98, "GeneratePrefab", 4);
                    data_446be8 = data_446b10(data_446b98, "RPC_GeneratePrefab", 4);
                    int64_t var_eb8_1 = data_446bd8;
                    int64_t var_eb0_1 = data_446be0;
                    int64_t var_ec8_1 = data_446bb0;
                    int64_t var_ec0_1 = data_446bb8;
                    int64_t var_ed0_1 = data_446ba8;
                    id obj_6 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
                        "stringWithFormat:", &cfstr_SI4:%p_SI1:%p_Any:%p_SM5:%p_GP4:%p));
                    sub_410c94(obj_6);
                    _objc_release(obj_6);
                }
                else
                {
                    x0_67 = data_446ae0(data_446ae8, "AnimalCompany", "PrefabGenerator");
                    data_446b98 = x0_67;
                    
                    if (x0_67)
                        goto label_42a464;
                    
                    sub_410c94(&cfstr_[ERR]_PrefabGenerator_NOT_FOUND);
                }
                
                int64_t x0_88 = data_446ae0(data_446c20, "UnityEngine", "Object");
                data_446c38 = x0_88;
                
                if (x0_88)
                {
                    data_446bd0 = data_446b10(x0_88, "FindObjectOfType", 1);
                    data_446c40 = data_446b10(data_446c38, "FindObjectOfType", 0);
                }
                
                data_446c48 = data_446ae0(data_446c20, "UnityEngine", "GameObject");
                data_446b58 = data_446ae0(data_446c20, "UnityEngine", "Transform");
                int64_t x0_96 = data_446c48;
                
                if (x0_96)
                    data_446b40 = data_446b10(x0_96, "get_transform", 0);
                
                data_446b48 = data_446c18("
                    UnityEngine.Transform::get_position_Injected(UnityEngine.Vector3&)");
                int64_t x0_99 = data_446c18("
                    UnityEngine.Transform::set_position_Injected(UnityEngine.Vector3&)");
                data_446b50 = x0_99;
                
                if (x0_99)
                    sub_410c94(&cfstr_set_position_Injected_found!);
                
                int64_t x0_101 = data_446ae0(data_446ae8, &cstr_, "PlayerHealth");
                data_446b68 = x0_101;
                
                if (x0_101)
                    sub_410c94(&cfstr_Health_class_found_for_god_mode!);
                else
                {
                    int64_t x0_103 = data_446ae0(data_446ae8, &cstr_, "Health");
                    data_446b68 = x0_103;
                    
                    if (x0_103)
                        sub_410c94(&cfstr_Health_class_found_for_god_mode!);
                    else
                    {
                        int64_t x0_105 = data_446ae0(data_446ae8, "AnimalCompany", "PlayerHealth");
                        data_446b68 = x0_105;
                        
                        if (x0_105)
                            sub_410c94(&cfstr_Health_class_found_for_god_mode!);
                    }
                }
                
                int64_t x0_107 = data_446ae0(data_446ae8, &cstr_, "NetPlayer");
                data_446bc0 = x0_107;
                
                if (x0_107)
                {
                    data_446b38 = data_446b10(x0_107, "get_localPlayer", 0);
                    int64_t x0_110 = data_446b10(data_446bc0, "get_name", 0);
                    data_446bc8 = x0_110;
                    
                    if (!x0_110)
                    {
                        int64_t x0_112 = data_446b10(data_446bc0, "get_playerName", 0);
                        data_446bc8 = x0_112;
                        
                        if (!x0_112)
                        {
                            int64_t x0_114 = data_446b10(data_446bc0, "get_NickName", 0);
                            data_446bc8 = x0_114;
                            
                            if (!x0_114)
                                data_446bc8 = data_446b10(data_446bc0, "get_DisplayName", 0);
                        }
                    }
                    
                    data_446c50 = data_446b10(data_446bc0, "get_players", 0);
                }
                
                int64_t x0_119 = data_446c38;
                
                if (x0_119)
                    data_446af0 = data_446b10(x0_119, "FindObjectsOfType", 1);
                
                int64_t x0_122 = data_446ae0(data_446ae8, &cstr_, "ItemInstance");
                data_446c58 = x0_122;
                
                if (x0_122)
                {
                label_42a8c8:
                    data_446c60 = data_446b18(x0_122, "colorHue");
                    int64_t x0_127 = data_446b18(data_446c58, "colorSaturation");
                    data_446c68 = x0_127;
                    int64_t var_ec8_2 = data_446c60;
                    int64_t var_ec0_2 = x0_127;
                    int64_t var_ed0_2 = data_446c58;
                    id obj_7 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
                        "stringWithFormat:", &cfstr_ItemColor:_cls:%p_hue:%p_sat:%p));
                    sub_410c94(obj_7);
                    _objc_release(obj_7);
                }
                else
                {
                    x0_122 = data_446ae0(data_446ae8, &cstr_, "Item");
                    data_446c58 = x0_122;
                    
                    if (x0_122)
                        goto label_42a8c8;
                    
                    x0_122 = data_446ae0(data_446ae8, "AnimalCompany", "ItemInstance");
                    data_446c58 = x0_122;
                    
                    if (x0_122)
                        goto label_42a8c8;
                }
                
                if (!data_446b98)
                    sub_410c94(&cfstr_[WARN]_Game_classes_failed_?_spawning_may_not_work);
            }
        }
    }
    
    struct __NSConstantString* const var_bd8 = &cfstr_item_ac_cola;
    struct __NSConstantString* const var_bd0 = &cfstr_item_alphablade;
    struct __NSConstantString* const var_bc8 = &cfstr_item_anti_gravity_grenade;
    struct __NSConstantString* const var_bc0 = &cfstr_item_apple;
    struct __NSConstantString* const var_bb8 = &cfstr_item_arena_pistol;
    struct __NSConstantString* const var_bb0 = &cfstr_item_arena_shotgun;
    struct __NSConstantString* const var_ba8 = &cfstr_item_arrow;
    struct __NSConstantString* const var_ba0 = &cfstr_item_arrow_bomb;
    struct __NSConstantString* const var_b98 = &cfstr_item_arrow_heart;
    struct __NSConstantString* const var_b90 = &cfstr_item_arrow_lightbulb;
    struct __NSConstantString* const var_b88 = &cfstr_item_arrow_teleport;
    struct __NSConstantString* const var_b80 = &cfstr_item_axe;
    struct __NSConstantString* const var_b78 = &cfstr_item_backpack;
    struct __NSConstantString* const var_b70 = &cfstr_item_backpack_big;
    struct __NSConstantString* const var_b68 = &cfstr_item_backpack_black;
    struct __NSConstantString* const var_b60 = &cfstr_item_backpack_cube;
    struct __NSConstantString* const var_b58 = &cfstr_item_backpack_gold;
    struct __NSConstantString* const var_b50 = &cfstr_item_backpack_green;
    struct __NSConstantString* const var_b48 = &cfstr_item_backpack_large_base;
    struct __NSConstantString* const var_b40 = &cfstr_item_backpack_large_basketball;
    struct __NSConstantString* const var_b38 = &cfstr_item_backpack_large_clover;
    struct __NSConstantString* const var_b30 = &cfstr_item_backpack_mega;
    struct __NSConstantString* const var_b28 = &cfstr_item_backpack_neon;
    struct __NSConstantString* const var_b20 = &cfstr_item_backpack_pink;
    struct __NSConstantString* const var_b18 = &cfstr_item_backpack_realistic;
    struct __NSConstantString* const var_b10 = &cfstr_item_backpack_skull;
    struct __NSConstantString* const var_b08 = &cfstr_item_backpack_small_base;
    struct __NSConstantString* const var_b00 = &cfstr_item_backpack_white;
    struct __NSConstantString* const var_af8 = &cfstr_item_backpack_with_flashlight;
    struct __NSConstantString* const var_af0 = &cfstr_item_balloon;
    struct __NSConstantString* const var_ae8 = &cfstr_item_balloon_heart;
    struct __NSConstantString* const var_ae0 = &cfstr_item_banana;
    struct __NSConstantString* const var_ad8 = &cfstr_item_banana_chips;
    struct __NSConstantString* const var_ad0 = &cfstr_item_baseball_bat;
    struct __NSConstantString* const var_ac8 = &cfstr_item_basic_fishing_rod;
    struct __NSConstantString* const var_ac0 = &cfstr_item_beans;
    struct __NSConstantString* const var_ab8 = &cfstr_item_big_cup;
    struct __NSConstantString* const var_ab0 = &cfstr_item_bighead_larva;
    struct __NSConstantString* const var_aa8 = &cfstr_item_bloodlust_vial;
    struct __NSConstantString* const var_aa0 = &cfstr_item_boombox;
    struct __NSConstantString* const var_a98 = &cfstr_item_boombox_neon;
    struct __NSConstantString* const var_a90 = &cfstr_item_boomerang;
    struct __NSConstantString* const var_a88 = &cfstr_item_box_fan;
    struct __NSConstantString* const var_a80 = &cfstr_item_brain_chunk;
    struct __NSConstantString* const var_a78 = &cfstr_item_brick;
    struct __NSConstantString* const var_a70 = &cfstr_item_broccoli_grenade;
    struct __NSConstantString* const var_a68 = &cfstr_item_broccoli_shrink_grenade;
    struct __NSConstantString* const var_a60 = &cfstr_item_broom;
    struct __NSConstantString* const var_a58 = &cfstr_item_broom_halloween;
    struct __NSConstantString* const var_a50 = &cfstr_item_burrito;
    struct __NSConstantString* const var_a48 = &cfstr_item_calculator;
    struct __NSConstantString* const var_a40 = &cfstr_item_cardboard_box;
    struct __NSConstantString* const var_a38 = &cfstr_item_ceo_plaque;
    struct __NSConstantString* const var_a30 = &cfstr_item_clapper;
    struct __NSConstantString* const var_a28 = &cfstr_item_cluster_grenade;
    struct __NSConstantString* const var_a20 = &cfstr_item_coconut_shell;
    struct __NSConstantString* const var_a18 = &cfstr_item_cola;
    struct __NSConstantString* const var_a10 = &cfstr_item_cola_large;
    struct __NSConstantString* const var_a08 = &cfstr_item_company_ration;
    struct __NSConstantString* const var_a00 = &cfstr_item_company_ration_heal;
    struct __NSConstantString* const var_9f8 = &cfstr_item_cracker;
    struct __NSConstantString* const var_9f0 = &cfstr_item_crate;
    struct __NSConstantString* const var_9e8 = &cfstr_item_crossbow;
    struct __NSConstantString* const var_9e0 = &cfstr_item_crossbow_heart;
    struct __NSConstantString* const var_9d8 = &cfstr_item_crowbar;
    struct __NSConstantString* const var_9d0 = &cfstr_item_cutie_dead;
    struct __NSConstantString* const var_9c8 = &cfstr_item_d20;
    struct __NSConstantString* const var_9c0 = &cfstr_item_demon_sword;
    struct __NSConstantString* const var_9b8 = &cfstr_item_disc;
    struct __NSConstantString* const var_9b0 = &cfstr_item_disposable_camera;
    struct __NSConstantString* const var_9a8 = &cfstr_item_drill;
    struct __NSConstantString* const var_9a0 = &cfstr_item_drill_neon;
    struct __NSConstantString* const var_998 = &cfstr_item_dynamite;
    struct __NSConstantString* const var_990 = &cfstr_item_dynamite_cube;
    struct __NSConstantString* const var_988 = &cfstr_item_egg;
    struct __NSConstantString* const var_980 = &cfstr_item_electrical_tape;
    struct __NSConstantString* const var_978 = &cfstr_item_eraser;
    struct __NSConstantString* const var_970 = &cfstr_item_film_reel;
    struct __NSConstantString* const var_968 = &cfstr_item_finger_board;
    struct __NSConstantString* const var_960 = &cfstr_item_fish_dumb_fish;
    struct __NSConstantString* const var_958 = &cfstr_item_flamethrower;
    struct __NSConstantString* const var_950 = &cfstr_item_flamethrower_skull;
    struct __NSConstantString* const var_948 = &cfstr_item_flamethrower_skull_ruby;
    struct __NSConstantString* const var_940 = &cfstr_item_flaregun;
    struct __NSConstantString* const var_938 = &cfstr_item_flashbang;
    struct __NSConstantString* const var_930 = &cfstr_item_flashlight;
    struct __NSConstantString* const var_928 = &cfstr_item_flashlight_mega;
    struct __NSConstantString* const var_920 = &cfstr_item_flashlight_red;
    struct __NSConstantString* const var_918 = &cfstr_item_flipflop_realistic;
    struct __NSConstantString* const var_910 = &cfstr_item_floppy3;
    struct __NSConstantString* const var_908 = &cfstr_item_floppy5;
    struct __NSConstantString* const var_900 = &cfstr_item_football;
    struct __NSConstantString* const var_8f8 = &cfstr_item_friend_launcher;
    struct __NSConstantString* const var_8f0 = &cfstr_item_frying_pan;
    struct __NSConstantString* const var_8e8 = &cfstr_item_gameboy;
    struct __NSConstantString* const var_8e0 = &cfstr_item_glowstick;
    struct __NSConstantString* const var_8d8 = &cfstr_item_goldbar;
    struct __NSConstantString* const var_8d0 = &cfstr_item_goldcoin;
    struct __NSConstantString* const var_8c8 = &cfstr_item_goop;
    struct __NSConstantString* const var_8c0 = &cfstr_item_goopfish;
    struct __NSConstantString* const var_8b8 = &cfstr_item_great_sword;
    struct __NSConstantString* const var_8b0 = &cfstr_item_grenade;
    struct __NSConstantString* const var_8a8 = &cfstr_item_grenade_gold;
    struct __NSConstantString* const var_8a0 = &cfstr_item_grenade_launcher;
    struct __NSConstantString* const var_898 = &cfstr_item_guided_boomerang;
    struct __NSConstantString* const var_890 = &cfstr_item_harddrive;
    struct __NSConstantString* const var_888 = &cfstr_item_hatchet;
    struct __NSConstantString* const var_880 = &cfstr_item_hawaiian_drum;
    struct __NSConstantString* const var_878 = &cfstr_item_heart_chunk;
    struct __NSConstantString* const var_870 = &cfstr_item_heart_gun;
    struct __NSConstantString* const var_868 = &cfstr_item_heartchocolatebox;
    struct __NSConstantString* const var_860 = &cfstr_item_hh_key;
    struct __NSConstantString* const var_858 = &cfstr_item_hookshot;
    struct __NSConstantString* const var_850 = &cfstr_item_hookshot_sword;
    struct __NSConstantString* const var_848 = &cfstr_item_hot_cocoa;
    struct __NSConstantString* const var_840 = &cfstr_item_hoverpad;
    struct __NSConstantString* const var_838 = &cfstr_item_impulse_grenade;
    struct __NSConstantString* const var_830 = &cfstr_item_jetpack;
    struct __NSConstantString* const var_828 = &cfstr_item_joystick;
    struct __NSConstantString* const var_820 = &cfstr_item_joystick_inv_y;
    struct __NSConstantString* const var_818 = &cfstr_item_keycard;
    struct __NSConstantString* const var_810 = &cfstr_item_lance;
    struct __NSConstantString* const var_808 = &cfstr_item_landmine;
    struct __NSConstantString* const var_800 = &cfstr_item_large_banana;
    struct __NSConstantString* const var_7f8 = &cfstr_item_megaphone;
    struct __NSConstantString* const var_7f0 = &cfstr_item_metal_ball;
    struct __NSConstantString* const var_7e8 = &cfstr_item_metal_ball_xmas;
    struct __NSConstantString* const var_7e0 = &cfstr_item_metal_plate;
    struct __NSConstantString* const var_7d8 = &cfstr_item_metal_plate_xmas;
    struct __NSConstantString* const var_7d0 = &cfstr_item_metal_rod;
    struct __NSConstantString* const var_7c8 = &cfstr_item_metal_rod_xmas;
    struct __NSConstantString* const var_7c0 = &cfstr_item_metal_triangle;
    struct __NSConstantString* const var_7b8 = &cfstr_item_momboss_box;
    struct __NSConstantString* const var_7b0 = &cfstr_item_moneygun;
    struct __NSConstantString* const var_7a8 = &cfstr_item_motor;
    struct __NSConstantString* const var_7a0 = &cfstr_item_mountain_key;
    struct __NSConstantString* const var_798 = &cfstr_item_mug;
    struct __NSConstantString* const var_790 = &cfstr_item_needle;
    struct __NSConstantString* const var_788 = &cfstr_item_nut;
    struct __NSConstantString* const var_780 = &cfstr_item_nut_drop;
    struct __NSConstantString* const var_778 = &cfstr_item_ogre_hands;
    struct __NSConstantString* const var_770 = &cfstr_item_ore_copper_l;
    struct __NSConstantString* const var_768 = &cfstr_item_ore_copper_m;
    struct __NSConstantString* const var_760 = &cfstr_item_ore_copper_s;
    struct __NSConstantString* const var_758 = &cfstr_item_ore_gold_l;
    struct __NSConstantString* const var_750 = &cfstr_item_ore_gold_m;
    struct __NSConstantString* const var_748 = &cfstr_item_ore_gold_s;
    struct __NSConstantString* const var_740 = &cfstr_item_ore_hell;
    struct __NSConstantString* const var_738 = &cfstr_item_ore_silver_l;
    struct __NSConstantString* const var_730 = &cfstr_item_ore_silver_m;
    struct __NSConstantString* const var_728 = &cfstr_item_ore_silver_s;
    struct __NSConstantString* const var_720 = &cfstr_item_painting_canvas;
    struct __NSConstantString* const var_718 = &cfstr_item_paperpack;
    struct __NSConstantString* const var_710 = &cfstr_item_pelican_case;
    struct __NSConstantString* const var_708 = &cfstr_item_pickaxe;
    struct __NSConstantString* const var_700 = &cfstr_item_pickaxe_cny;
    struct __NSConstantString* const var_6f8 = &cfstr_item_pickaxe_cube;
    struct __NSConstantString* const var_6f0 = &cfstr_item_pickaxe_realistic;
    struct __NSConstantString* const var_6e8 = &cfstr_item_pinata_bat;
    struct __NSConstantString* const var_6e0 = &cfstr_item_pineapple;
    struct __NSConstantString* const var_6d8 = &cfstr_item_pipe;
    struct __NSConstantString* const var_6d0 = &cfstr_item_pistol_dragon;
    struct __NSConstantString* const var_6c8 = &cfstr_item_piston;
    struct __NSConstantString* const var_6c0 = &cfstr_item_plank;
    struct __NSConstantString* const var_6b8 = &cfstr_item_plunger;
    struct __NSConstantString* const var_6b0 = &cfstr_item_pogostick;
    struct __NSConstantString* const var_6a8 = &cfstr_item_police_baton;
    struct __NSConstantString* const var_6a0 = &cfstr_item_popcorn;
    struct __NSConstantString* const var_698 = &cfstr_item_portable_teleporter;
    struct __NSConstantString* const var_690 = &cfstr_item_prop_scanner;
    struct __NSConstantString* const var_688 = &cfstr_item_pumpkin_bomb;
    struct __NSConstantString* const var_680 = &cfstr_item_pumpkin_pie;
    struct __NSConstantString* const var_678 = &cfstr_item_pumpkinjack;
    struct __NSConstantString* const var_670 = &cfstr_item_pumpkinjack_small;
    struct __NSConstantString* const var_668 = &cfstr_item_quest_gy_skull;
    struct __NSConstantString* const var_660 = &cfstr_item_quest_gy_skull_special;
    struct __NSConstantString* const var_658 = &cfstr_item_quest_hlal_brain;
    struct __NSConstantString* const var_650 = &cfstr_item_quest_hlal_eyeball;
    struct __NSConstantString* const var_648 = &cfstr_item_quest_hlal_flesh;
    struct __NSConstantString* const var_640 = &cfstr_item_quest_hlal_heart;
    struct __NSConstantString* const var_638 = &cfstr_item_quest_key_graveyard;
    struct __NSConstantString* const var_630 = &cfstr_item_quest_vhs;
    struct __NSConstantString* const var_628 = &cfstr_item_quest_vhs_backlots;
    struct __NSConstantString* const var_620 = &cfstr_item_quest_vhs_basement;
    struct __NSConstantString* const var_618 = &cfstr_item_quest_vhs_cave;
    struct __NSConstantString* const var_610 = &cfstr_item_quest_vhs_circus_day;
    struct __NSConstantString* const var_608 = &cfstr_item_quest_vhs_circus_ext;
    struct __NSConstantString* const var_600 = &cfstr_item_quest_vhs_circus_fac;
    struct __NSConstantString* const var_5f8 = &cfstr_item_quest_vhs_dam_facility;
    struct __NSConstantString* const var_5f0 = &cfstr_item_quest_vhs_dam_servers;
    struct __NSConstantString* const var_5e8 = &cfstr_item_quest_vhs_dark_forest;
    struct __NSConstantString* const var_5e0 = &cfstr_item_quest_vhs_forest;
    struct __NSConstantString* const var_5d8 = &cfstr_item_quest_vhs_foundation;
    struct __NSConstantString* const var_5d0 = &cfstr_item_quest_vhs_graveyard;
    struct __NSConstantString* const var_5c8 = &cfstr_item_quest_vhs_haunted_house;
    struct __NSConstantString* const var_5c0 = &cfstr_item_quest_vhs_hell;
    struct __NSConstantString* const var_5b8 = &cfstr_item_quest_vhs_lab;
    struct __NSConstantString* const var_5b0 = &cfstr_item_quest_vhs_lake;
    struct __NSConstantString* const var_5a8 = &cfstr_item_quest_vhs_lobby;
    struct __NSConstantString* const var_5a0 = &cfstr_item_quest_vhs_mines;
    struct __NSConstantString* const var_598 = &cfstr_item_quest_vhs_mountain;
    struct __NSConstantString* const var_590 = &cfstr_item_quest_vhs_mountainbot;
    struct __NSConstantString* const var_588 = &cfstr_item_quest_vhs_mountainshack;
    struct __NSConstantString* const var_580 = &cfstr_item_quest_vhs_mountainvault;
    struct __NSConstantString* const var_578 = &cfstr_item_quest_vhs_office;
    struct __NSConstantString* const var_570 = &cfstr_item_quest_vhs_office_basement;
    struct __NSConstantString* const var_568 = &cfstr_item_quest_vhs_powerplant_microwave;
    struct __NSConstantString* const var_560 = &cfstr_item_quest_vhs_powerplant_reactorcore;
    struct __NSConstantString* const var_558 = &cfstr_item_quest_vhs_powerplant_security;
    struct __NSConstantString* const var_550 = &cfstr_item_quest_vhs_powerplant_supportfacility;
    struct __NSConstantString* const var_548 = &cfstr_item_quest_vhs_sewers;
    struct __NSConstantString* const var_540 = &cfstr_item_quiver;
    struct __NSConstantString* const var_538 = &cfstr_item_quiver_heart;
    struct __NSConstantString* const var_530 = &cfstr_item_radiation_gun;
    struct __NSConstantString* const var_528 = &cfstr_item_radioactive_broccoli;
    struct __NSConstantString* const var_520 = &cfstr_item_randombox_base;
    struct __NSConstantString* const var_518 = &cfstr_item_randombox_mobloot_big;
    struct __NSConstantString* const var_510 = &cfstr_item_randombox_mobloot_medium;
    struct __NSConstantString* const var_508 = &cfstr_item_randombox_mobloot_small;
    struct __NSConstantString* const var_500 = &cfstr_item_randombox_mobloot_weapons;
    struct __NSConstantString* const var_4f8 = &cfstr_item_randombox_mobloot_zombie;
    struct __NSConstantString* const var_4f0 = &cfstr_item_rare_card;
    struct __NSConstantString* const var_4e8 = &cfstr_item_remote_controller;
    struct __NSConstantString* const var_4e0 = &cfstr_item_revolver;
    struct __NSConstantString* const var_4d8 = &cfstr_item_revolver_ammo;
    struct __NSConstantString* const var_4d0 = &cfstr_item_revolver_gold;
    struct __NSConstantString* const var_4c8 = &cfstr_item_ring_buoy;
    struct __NSConstantString* const var_4c0 = &cfstr_item_robo_monke;
    struct __NSConstantString* const var_4b8 = &cfstr_item_robot_arm_left;
    struct __NSConstantString* const var_4b0 = &cfstr_item_robot_arm_right;
    struct __NSConstantString* const var_4a8 = &cfstr_item_robot_head;
    struct __NSConstantString* const var_4a0 = &cfstr_item_rope;
    struct __NSConstantString* const var_498 = &cfstr_item_rpg;
    struct __NSConstantString* const var_490 = &cfstr_item_rpg_ammo;
    struct __NSConstantString* const var_488 = &cfstr_item_rpg_ammo_egg;
    struct __NSConstantString* const var_480 = &cfstr_item_rpg_ammo_spear;
    struct __NSConstantString* const var_478 = &cfstr_item_rpg_cny;
    struct __NSConstantString* const var_470 = &cfstr_item_rpg_easter;
    struct __NSConstantString* const var_468 = &cfstr_item_rpg_smshr;
    struct __NSConstantString* const var_460 = &cfstr_item_rpg_spear;
    struct __NSConstantString* const var_458 = &cfstr_item_rubberducky;
    struct __NSConstantString* const var_450 = &cfstr_item_ruby;
    struct __NSConstantString* const var_448 = &cfstr_item_saddle;
    struct __NSConstantString* const var_440 = &cfstr_item_scanner;
    struct __NSConstantString* const var_438 = &cfstr_item_scissors;
    struct __NSConstantString* const var_430 = &cfstr_item_server_pad;
    struct __NSConstantString* const var_428 = &cfstr_item_shield;
    struct __NSConstantString* const var_420 = &cfstr_item_shield_bones;
    struct __NSConstantString* const var_418 = &cfstr_item_shield_police;
    struct __NSConstantString* const var_410 = &cfstr_item_shield_viking_1;
    struct __NSConstantString* const var_408 = &cfstr_item_shield_viking_2;
    struct __NSConstantString* const var_400 = &cfstr_item_shield_viking_3;
    struct __NSConstantString* const var_3f8 = &cfstr_item_shield_viking_4;
    struct __NSConstantString* const var_3f0 = &cfstr_item_shotgun;
    struct __NSConstantString* const var_3e8 = &cfstr_item_shotgun_ammo;
    struct __NSConstantString* const var_3e0 = &cfstr_item_shotgun_viper;
    struct __NSConstantString* const var_3d8 = &cfstr_item_shovel;
    struct __NSConstantString* const var_3d0 = &cfstr_item_shredder;
    struct __NSConstantString* const var_3c8 = &cfstr_item_shrinking_broccoli;
    struct __NSConstantString* const var_3c0 = &cfstr_item_skipole;
    struct __NSConstantString* const var_3b8 = &cfstr_item_skishoe;
    struct __NSConstantString* const var_3b0 = &cfstr_item_skishoe_2;
    struct __NSConstantString* const var_3a8 = &cfstr_item_skishoe_3;
    struct __NSConstantString* const var_3a0 = &cfstr_item_skishoe_4;
    struct __NSConstantString* const var_398 = &cfstr_item_sludge;
    struct __NSConstantString* const var_390 = &cfstr_item_snail_friend;
    struct __NSConstantString* const var_388 = &cfstr_item_snowball;
    struct __NSConstantString* const var_380 = &cfstr_item_snowboard;
    struct __NSConstantString* const var_378 = &cfstr_item_snowboard_2;
    struct __NSConstantString* const var_370 = &cfstr_item_snowboard_3;
    struct __NSConstantString* const var_368 = &cfstr_item_snowboard_4;
    struct __NSConstantString* const var_360 = &cfstr_item_snowboard_auto;
    struct __NSConstantString* const var_358 = &cfstr_item_stapler;
    struct __NSConstantString* const var_350 = &cfstr_item_stash_grenade;
    struct __NSConstantString* const var_348 = &cfstr_item_steel_beam;
    struct __NSConstantString* const var_340 = &cfstr_item_steel_beam_xmas;
    struct __NSConstantString* const var_338 = &cfstr_item_stellarsword_blue;
    struct __NSConstantString* const var_330 = &cfstr_item_stellarsword_gold;
    struct __NSConstantString* const var_328 = &cfstr_item_stick_armbones;
    struct __NSConstantString* const var_320 = &cfstr_item_stick_bone;
    struct __NSConstantString* const var_318 = &cfstr_item_sticker_dispenser;
    struct __NSConstantString* const var_310 = &cfstr_item_sticky_dynamite;
    struct __NSConstantString* const var_308 = &cfstr_item_stinky_cheese;
    struct __NSConstantString* const var_300 = &cfstr_item_tablet;
    struct __NSConstantString* const var_2f8 = &cfstr_item_tapedispenser;
    struct __NSConstantString* const var_2f0 = &cfstr_item_tele_grenade;
    struct __NSConstantString* const var_2e8 = &cfstr_item_teleport_gun;
    struct __NSConstantString* const var_2e0 = &cfstr_item_theremin;
    struct __NSConstantString* const var_2d8 = &cfstr_item_timebomb;
    struct __NSConstantString* const var_2d0 = &cfstr_item_toilet_paper;
    struct __NSConstantString* const var_2c8 = &cfstr_item_toilet_paper_mega;
    struct __NSConstantString* const var_2c0 = &cfstr_item_toilet_paper_roll_empty;
    struct __NSConstantString* const var_2b8 = &cfstr_item_token_circus;
    struct __NSConstantString* const var_2b0 = &cfstr_item_trampoline;
    struct __NSConstantString* const var_2a8 = &cfstr_item_treestick;
    struct __NSConstantString* const var_2a0 = &cfstr_item_tripwire_explosive;
    struct __NSConstantString* const var_298 = &cfstr_item_trophy;
    struct __NSConstantString* const var_290 = &cfstr_item_truss;
    struct __NSConstantString* const var_288 = &cfstr_item_truss_xmas;
    struct __NSConstantString* const var_280 = &cfstr_item_turkey_leg;
    struct __NSConstantString* const var_278 = &cfstr_item_turkey_whole;
    struct __NSConstantString* const var_270 = &cfstr_item_ukulele;
    struct __NSConstantString* const var_268 = &cfstr_item_ukulele_gold;
    struct __NSConstantString* const var_260 = &cfstr_item_umbrella;
    struct __NSConstantString* const var_258 = &cfstr_item_umbrella_clover;
    struct __NSConstantString* const var_250 = &cfstr_item_umbrella_squirrel;
    struct __NSConstantString* const var_248 = &cfstr_item_upsidedown_loot;
    struct __NSConstantString* const var_240 = &cfstr_item_uranium_chunk_l;
    struct __NSConstantString* const var_238 = &cfstr_item_uranium_chunk_m;
    struct __NSConstantString* const var_230 = &cfstr_item_uranium_chunk_s;
    struct __NSConstantString* const var_228 = &cfstr_item_viking_hammer;
    struct __NSConstantString* const var_220 = &cfstr_item_viking_hammer_twilight;
    struct __NSConstantString* const var_218 = &cfstr_item_wheelhandle;
    struct __NSConstantString* const var_210 = &cfstr_item_wheelhandle_big;
    struct __NSConstantString* const var_208 = &cfstr_item_whoopie;
    struct __NSConstantString* const var_200 = &cfstr_item_wood_log;
    struct __NSConstantString* const var_1f8 = &cfstr_item_wood_pallet;
    struct __NSConstantString* const var_1f0 = &cfstr_item_zipline_gun;
    struct __NSConstantString* const var_1e8 = &cfstr_item_zombie_meat;
    struct __NSConstantString* const var_1e0 = &cfstr_item_kissy;
    struct __NSConstantString* const var_1d8 = &cfstr_item_crappie;
    struct __NSConstantString* const var_1d0 = &cfstr_item_carp;
    struct __NSConstantString* const var_1c8 = &cfstr_item_diamond_jade_koi;
    struct __NSConstantString* const var_1c0 = &cfstr_item_boot;
    struct __NSConstantString* const var_1b8 = &cfstr_item_license_plate;
    struct __NSConstantString* const var_1b0 = &cfstr_item_bottled_message;
    struct __NSConstantString* const var_1a8 = &cfstr_item_rotten_fish;
    id x0_134 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &var_bd8, 0x147));
    id obj_46 = data_446a88;
    data_446a88 = x0_134;
    _objc_release(obj_46);
    struct __NSConstantString* const var_110 = &cfstr_item_basic_fishing_rod;
    id x0_138 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &var_110, 1));
    id obj_47 = data_446aa8;
    data_446aa8 = x0_138;
    _objc_release(obj_47);
    struct __NSConstantString* const var_d0 = &cfstr_item_fish_dumb_fish;
    struct __NSConstantString* const var_c8 = &cfstr_item_goopfish;
    struct __NSConstantString* const var_c0 = &cfstr_item_kissy;
    struct __NSConstantString* const var_b8 = &cfstr_item_crappie;
    struct __NSConstantString* const var_b0 = &cfstr_item_carp;
    struct __NSConstantString* const var_a8 = &cfstr_item_diamond_jade_koi;
    struct __NSConstantString* const var_a0 = &cfstr_item_rotten_fish;
    id x0_142 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &var_d0, 7));
    id obj_48 = data_446ab0;
    data_446ab0 = x0_142;
    _objc_release(obj_48);
    struct __NSConstantString* const obj_63 = &cfstr_item_apple;
    struct __NSConstantString* const var_188 = &cfstr_item_banana;
    struct __NSConstantString* const var_180 = &cfstr_item_beans;
    struct __NSConstantString* const var_178 = &cfstr_item_burrito;
    struct __NSConstantString* const var_170 = &cfstr_item_coconut_shell;
    struct __NSConstantString* const var_168 = &cfstr_item_cracker;
    struct __NSConstantString* const var_160 = &cfstr_item_egg;
    struct __NSConstantString* const var_158 = &cfstr_item_pineapple;
    struct __NSConstantString* const var_150 = &cfstr_item_popcorn;
    struct __NSConstantString* const var_148 = &cfstr_item_stinky_cheese;
    id x0_146 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &obj_63, 0xa));
    id obj_49 = data_446ab8;
    data_446ab8 = x0_146;
    _objc_release(obj_49);
    id x0_149 = _objc_msgSend(data_446a88, "copy");
    id obj_50 = data_446a98;
    data_446a98 = x0_149;
    _objc_release(obj_50);
    var_bd8 = &cfstr_AnglerController;
    struct __NSConstantString* const var_bd0_1 = &cfstr_AnglerMadController;
    struct __NSConstantString* const var_bc8_1 = &cfstr_ArmstrongController;
    struct __NSConstantString* const var_bc0_1 = &cfstr_ArmstrongMadController;
    struct __NSConstantString* const var_bb8_1 = &cfstr_BansheeController;
    struct __NSConstantString* const var_bb0_1 = &cfstr_BlobController;
    struct __NSConstantString* const var_ba8_1 = &cfstr_BombController;
    struct __NSConstantString* const var_ba0_1 = &cfstr_BomberController;
    struct __NSConstantString* const var_b98_1 = &cfstr_BomberFlashbangController;
    struct __NSConstantString* const var_b90_1 = &cfstr_BomberMadController;
    struct __NSConstantString* const var_b88_1 = &cfstr_ChickenController;
    struct __NSConstantString* const var_b80_1 = &cfstr_CutieController;
    struct __NSConstantString* const var_b78_1 = &cfstr_CystController;
    struct __NSConstantString* const var_b70_1 = &cfstr_EvilEyeController;
    struct __NSConstantString* const var_b68_1 = &cfstr_EvilEyePinataController;
    struct __NSConstantString* const var_b60_1 = &cfstr_EvilEyePinataLargeController;
    struct __NSConstantString* const var_b58_1 = &cfstr_FakeGorillaController;
    struct __NSConstantString* const var_b50_1 = &cfstr_FlyingSwarmController;
    struct __NSConstantString* const var_b48_1 = &cfstr_GiantController;
    struct __NSConstantString* const var_b40_1 = &cfstr_LankyController;
    struct __NSConstantString* const var_b38_1 = &cfstr_NextBotController;
    struct __NSConstantString* const var_b30_1 = &cfstr_NextBotStaticController;
    struct __NSConstantString* const var_b28_1 = &cfstr_PhantomController;
    struct __NSConstantString* const var_b20_1 = &cfstr_RedGreenController;
    struct __NSConstantString* const var_b18_1 = &cfstr_RedGreenMadController;
    struct __NSConstantString* const var_b10_1 = &cfstr_SegwayController;
    struct __NSConstantString* const var_b08_1 = &cfstr_SpiderCaveController;
    struct __NSConstantString* const var_b00_1 = &cfstr_SpiderController;
    id x0_153 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &var_bd8, 0x1c));
    id obj_51 = data_446a90;
    data_446a90 = x0_153;
    _objc_release(obj_51);
    id x0_156 = _objc_msgSend(data_446a90, "copy");
    id obj_52 = data_446aa0;
    data_446aa0 = x0_156;
    _objc_release(obj_52);
    var_bd8 = &cfstr_Custom_Input;
    struct __NSConstantString* const var_bd0_2 = &cfstr_Sell;
    struct __NSConstantString* const var_bc8_2 = &cfstr_Stage_5;
    struct __NSConstantString* const var_bc0_2 = &cfstr_Toilet;
    struct __NSConstantString* const var_bb8_2 = &cfstr_Hot;
    struct __NSConstantString* const var_bb0_2 = &cfstr_Spawn;
    struct __NSConstantString* const var_ba8_2 = &cfstr_Center_of_Spawn;
    struct __NSConstantString* const var_ba0_2 = &cfstr_Origin_of_Spawn;
    struct __NSConstantString* const var_b98_2 = &cfstr_Stash;
    struct __NSConstantString* const var_b90_2 = &cfstr_Inside_Stash;
    struct __NSConstantString* const var_b88_2 = &cfstr_Lake;
    struct __NSConstantString* const var_b80_2 = &cfstr_Mountains;
    struct __NSConstantString* const var_b78_2 = &cfstr_Dupe_Machine;
    id x0_160 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &var_bd8, 0xd));
    id obj_53 = data_4469d0;
    data_4469d0 = x0_160;
    _objc_release(obj_53);
    struct objc_class_t* clsRef_NSValue_1 = clsRef_NSValue;
    var_d0 = nullptr;
    var_c8 = 0;
    id obj_8 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSValue_1, 
        "valueWithBytes:objCType:", &var_d0, "{?=fff}"));
    obj_63 = obj_8;
    struct objc_class_t* clsRef_NSValue_2 = clsRef_NSValue;
    var_110 = 0x40200000c1940000;
    int32_t var_108 = 0xc1b00000;
    id obj_9 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSValue_2, 
        "valueWithBytes:objCType:", &var_110, "{?=fff}"));
    id obj_64 = obj_9;
    struct objc_class_t* clsRef_NSValue_3 = clsRef_NSValue;
    id var_1a0 = 0x4248000042be0000;
    int32_t var_198 = 0x42dc0000;
    id obj_10 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSValue_3, 
        "valueWithBytes:objCType:", &var_1a0, "{?=fff}"));
    id obj_65 = obj_10;
    struct objc_class_t* clsRef_NSValue_4 = clsRef_NSValue;
    int64_t var_ce8 = 0x40200000c0a00000;
    int32_t var_ce0 = 0x41400000;
    id obj_11 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSValue_4, 
        "valueWithBytes:objCType:", &var_ce8, "{?=fff}"));
    id obj_66 = obj_11;
    struct objc_class_t* clsRef_NSValue_5 = clsRef_NSValue;
    int64_t var_cf8 = 0x4020000041f00000;
    int32_t var_cf0 = 0xc1700000;
    id obj_12 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSValue_5, 
        "valueWithBytes:objCType:", &var_cf8, "{?=fff}"));
    id obj_67 = obj_12;
    struct objc_class_t* clsRef_NSValue_6 = clsRef_NSValue;
    int64_t var_d08 = 0x4020000000000000;
    int32_t var_d00 = 0;
    id obj_13 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSValue_6, 
        "valueWithBytes:objCType:", &var_d08, "{?=fff}"));
    id obj_68 = obj_13;
    struct objc_class_t* clsRef_NSValue_7 = clsRef_NSValue;
    int64_t var_d18 = 0x4020000000000000;
    int32_t var_d10 = 0;
    id obj_14 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSValue_7, 
        "valueWithBytes:objCType:", &var_d18, "{?=fff}"));
    id obj_69 = obj_14;
    struct objc_class_t* clsRef_NSValue_8 = clsRef_NSValue;
    int64_t var_d28 = 0;
    int32_t var_d20 = 0;
    id obj_15 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSValue_8, 
        "valueWithBytes:objCType:", &var_d28, "{?=fff}"));
    id obj_70 = obj_15;
    struct objc_class_t* clsRef_NSValue_9 = clsRef_NSValue;
    int64_t var_d38 = 0x40200000c2200000;
    int32_t var_d30 = 0x41f00000;
    id obj_16 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSValue_9, 
        "valueWithBytes:objCType:", &var_d38, "{?=fff}"));
    id obj_71 = obj_16;
    struct objc_class_t* clsRef_NSValue_10 = clsRef_NSValue;
    int64_t var_d48 = 0x40a00000c2200000;
    int32_t var_d40 = 0x41f00000;
    id obj_17 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSValue_10, 
        "valueWithBytes:objCType:", &var_d48, "{?=fff}"));
    id obj_72 = obj_17;
    struct objc_class_t* clsRef_NSValue_11 = clsRef_NSValue;
    int64_t var_d58 = 0x4020000042700000;
    int32_t var_d50 = 0xc2480000;
    id obj_18 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSValue_11, 
        "valueWithBytes:objCType:", &var_d58, "{?=fff}"));
    id obj_73 = obj_18;
    struct objc_class_t* clsRef_NSValue_12 = clsRef_NSValue;
    int64_t var_d68 = 0x42340000c28c0000;
    int32_t var_d60 = 0x42a00000;
    id obj_19 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSValue_12, 
        "valueWithBytes:objCType:", &var_d68, "{?=fff}"));
    id obj_74 = obj_19;
    struct objc_class_t* clsRef_NSValue_13 = clsRef_NSValue;
    int64_t var_d78 = 0x4020000041200000;
    int32_t var_d70 = 0xc1f00000;
    id obj_20 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSValue_13, 
        "valueWithBytes:objCType:", &var_d78, "{?=fff}"));
    id obj_75 = obj_20;
    id x0_177 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSArray, 
        "arrayWithObjects:count:", &obj_63, 0xd));
    id obj_54 = data_4469d8;
    data_4469d8 = x0_177;
    _objc_release(obj_54);
    _objc_release(obj_20);
    _objc_release(obj_19);
    _objc_release(obj_18);
    _objc_release(obj_17);
    _objc_release(obj_16);
    _objc_release(obj_15);
    _objc_release(obj_14);
    _objc_release(obj_13);
    _objc_release(obj_12);
    _objc_release(obj_11);
    _objc_release(obj_10);
    _objc_release(obj_9);
    _objc_release(obj_8);
    id obj_21 = _objc_retainAutoreleasedReturnValue(_NSSearchPathForDirectoriesInDomains(
        NSDocumentDirectory, 1, true));
    id obj_61 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_21, "firstObject"));
    _objc_release(obj_21);
    id x0_198 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_61, 
        "stringByAppendingPathComponent:", &cfstr_orbit_saved_items.txt));
    id obj_55 = data_446a48;
    data_446a48 = x0_198;
    _objc_release(obj_55);
    id obj_22 =
        _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSFileManager, "defaultManager"));
    int32_t x0_202 = _objc_msgSend(obj_22, "fileExistsAtPath:", data_446a48);
    _objc_release(obj_22);
    
    if (x0_202)
    {
        id obj_23 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
            "stringWithContentsOfFile:encoding:error:", data_446a48, 4, 0));
        
        if (_objc_msgSend(obj_23, "length"))
        {
            id obj_24 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_23, 
                "componentsSeparatedByString:", &cfstr_\n));
            id x0_209 = _objc_msgSend(obj_24, "mutableCopy");
            id obj_56 = data_446a40;
            data_446a40 = x0_209;
            _objc_release(obj_56);
            _objc_release(obj_24);
            _objc_msgSend(data_446a40, "removeObject:", &cfstr_);
            struct objc_class_t* clsRef_NSString_1 = clsRef_NSString;
            id var_ed0_4 = _objc_msgSend(data_446a40, "count");
            id obj_25 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString_1, 
                "stringWithFormat:", &cfstr_Loaded_%lu_saved_world_items_from_file));
            sub_410c94(obj_25);
            _objc_release(obj_25);
        }
        
        _objc_release(obj_23);
    }
    
    if (!data_446b80)
    {
        __builtin_memset(&var_d0, 0, 0x40);
        id obj_26 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIApplication, 
            "sharedApplication"));
        id obj_60 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_26, "connectedScenes"));
        _objc_release(obj_26);
        int64_t i_7 = _objc_msgSend(obj_60, "countByEnumeratingWithState:objects:count:");
        
        if (i_7)
        {
            int64_t i_4 = i_7;
            void* isa = var_c0->isa;
            int64_t i_2;
            
            do
            {
                int64_t x25_2 = 0;
                int64_t i_5 = i_4;
                
                do
                {
                    if (var_c0->isa != isa)
                        _objc_enumerationMutation(obj_60);
                    
                    void* x22_4 = *(var_c8 + (x25_2 << 3));
                    _objc_msgSend(clsRef_UIWindowScene, "class");
                    
                    if (_objc_msgSend(x22_4, "isKindOfClass:"))
                    {
                        int128_t var_f0;
                        __builtin_memset(&var_f0, 0, 0x20);
                        __builtin_memset(&var_110, 0, 0x18);
                        id obj_27 =
                            _objc_retainAutoreleasedReturnValue(_objc_msgSend(x22_4, "windows"));
                        int64_t j_5 =
                            _objc_msgSend(obj_27, "countByEnumeratingWithState:objects:count:");
                        
                        if (j_5)
                        {
                            int64_t j_2 = j_5;
                            int64_t* var_100;
                            int64_t x21_7 = *var_100;
                            int64_t j_1;
                            
                            do
                            {
                                int64_t x27_2 = 0;
                                
                                do
                                {
                                    if (*var_100 != x21_7)
                                        _objc_enumerationMutation(obj_27);
                                    
                                    id obj_59 = *(var_108 + (x27_2 << 3));
                                    
                                    if (_objc_msgSend(obj_59, "isKeyWindow") & 1)
                                    {
                                        id obj_77 = _objc_retain(obj_59);
                                        _objc_release(obj_27);
                                        i_4 = i_5;
                                        
                                        if (!obj_77)
                                            goto label_42c384;
                                        
                                        _objc_release(obj_60);
                                        id x0_243 = _objc_retainAutoreleasedReturnValue(
                                            _objc_msgSend(clsRef_UIButton, "buttonWithType:", 0));
                                        id obj_57 = data_446b80;
                                        data_446b80 = x0_243;
                                        int64_t x2_26;
                                        int128_t v0_2;
                                        int128_t v1_1;
                                        int128_t v2_1;
                                        int128_t v3_1;
                                        x2_26 = _objc_release(obj_57);
                                        v1_1 = 0x405e000000000000;
                                        double v9 = 0x404b000000000000;
                                        v0_2 = 16.0;
                                        v2_1 = v9;
                                        v3_1 = v9;
                                        _objc_msgSend(data_446b80, "setFrame:", x2_26);
                                        id obj_28;
                                        int64_t x2_27;
                                        int128_t v0_3;
                                        obj_28 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(
                                            data_446b80, "layer"));
                                        v0_3 = 27.0;
                                        _objc_msgSend(obj_28, "setCornerRadius:", x2_27);
                                        int64_t x2_28;
                                        int64_t x3_2;
                                        int64_t x4_9;
                                        int64_t x5_1;
                                        int128_t v0_4;
                                        int128_t v1_2;
                                        int128_t v2_2;
                                        int128_t v3_2;
                                        x2_28 = _objc_release(obj_28);
                                        v1_2 = 0.5;
                                        v2_2 = 1.0;
                                        v3_2 = 1.0;
                                        v0_4 = 0x3fd3333333333333;
                                        id obj_29 = _objc_retainAutorelease(
                                            _objc_retainAutoreleasedReturnValue(_objc_msgSend(
                                            clsRef_UIColor, "colorWithRed:green:blue:alpha:", 
                                            x2_28, x3_2, x4_9, x5_1)));
                                        id x0_252 = _objc_msgSend(obj_29, "CGColor");
                                        id obj_30 = _objc_retainAutoreleasedReturnValue(
                                            _objc_msgSend(data_446b80, "layer"));
                                        _objc_msgSend(obj_30, "setShadowColor:", x0_252);
                                        _objc_release(obj_30);
                                        _objc_release(obj_29);
                                        width = _CGSizeZero->width;
                                        height = _CGSizeZero->height;
                                        id obj_31;
                                        int64_t x2_30;
                                        int128_t v0_5;
                                        int128_t v1_3;
                                        obj_31 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(
                                            data_446b80, "layer"));
                                        v0_5 = width;
                                        v1_3 = height;
                                        _objc_msgSend(obj_31, "setShadowOffset:", x2_30);
                                        _objc_release(obj_31);
                                        id obj_32;
                                        int64_t x2_31;
                                        int128_t v0_6;
                                        obj_32 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(
                                            data_446b80, "layer"));
                                        v0_6 = 0x3f666666;
                                        _objc_msgSend(obj_32, "setShadowOpacity:", x2_31);
                                        _objc_release(obj_32);
                                        id obj_33;
                                        int64_t x2_32;
                                        int128_t v0_7;
                                        obj_33 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(
                                            data_446b80, "layer"));
                                        v0_7 = 12.0;
                                        _objc_msgSend(obj_33, "setShadowRadius:", x2_32);
                                        int64_t x2_33;
                                        int64_t x3_3;
                                        int64_t x4_10;
                                        int64_t x5_2;
                                        int128_t v0_8;
                                        int128_t v2_3;
                                        int128_t v3_3;
                                        x2_33 = _objc_release(obj_33);
                                        v0_8 = 0x3fc999999999999a;
                                        v2_3 = 1.0;
                                        v3_3 = 0x3fe3333333333333;
                                        id obj_34 = _objc_retainAutorelease(
                                            _objc_retainAutoreleasedReturnValue(_objc_msgSend(
                                            clsRef_UIColor, "colorWithRed:green:blue:alpha:", 
                                            x2_33, x3_3, x4_10, x5_2)));
                                        id x0_269 = _objc_msgSend(obj_34, "CGColor");
                                        id obj_35 = _objc_retainAutoreleasedReturnValue(
                                            _objc_msgSend(data_446b80, "layer"));
                                        _objc_msgSend(obj_35, "setBorderColor:", x0_269);
                                        _objc_release(obj_35);
                                        _objc_release(obj_34);
                                        id obj_36;
                                        int64_t x2_35;
                                        int128_t v0_9;
                                        obj_36 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(
                                            data_446b80, "layer"));
                                        v0_9 = 2.0;
                                        _objc_msgSend(obj_36, "setBorderWidth:", x2_35);
                                        _objc_release(obj_36);
                                        _objc_msgSend(data_446b80, "setClipsToBounds:", 0);
                                        id obj_37;
                                        int128_t v0_10;
                                        int128_t v1_4;
                                        int128_t v2_4;
                                        int128_t v3_4;
                                        obj_37 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(
                                            clsRef_CAGradientLayer, "layer"));
                                        v0_10 = 0.0;
                                        v1_4 = 0.0;
                                        v2_4 = v9;
                                        v3_4 = v9;
                                        int64_t x2_36;
                                        int128_t v0_11;
                                        x2_36 = _objc_msgSend(obj_37, "setFrame:");
                                        v0_11 = 27.0;
                                        int64_t x2_37;
                                        int64_t x3_4;
                                        int64_t x4_11;
                                        int64_t x5_3;
                                        int128_t v0_12;
                                        int128_t v1_5;
                                        int128_t v2_5;
                                        int128_t v3_5;
                                        x2_37 = _objc_msgSend(obj_37, "setCornerRadius:", x2_36);
                                        v0_12 = 0x3fb999999999999a;
                                        v2_5 = 0x3fdccccccccccccd;
                                        v3_5 = 1.0;
                                        v1_5 = 0x3fc3333333333333;
                                        id obj_38 = _objc_retainAutorelease(
                                            _objc_retainAutoreleasedReturnValue(_objc_msgSend(
                                            clsRef_UIColor, "colorWithRed:green:blue:alpha:", 
                                            x2_37, x3_4, x4_11, x5_3)));
                                        id x0_284;
                                        int64_t x2_38;
                                        int64_t x3_5;
                                        int64_t x4_12;
                                        int64_t x5_4;
                                        int128_t v0_13;
                                        int128_t v1_6;
                                        int128_t v2_6;
                                        int128_t v3_6;
                                        x0_284 = _objc_msgSend(obj_38, "CGColor");
                                        var_1a0 = x0_284;
                                        v2_6 = 0x3fe6666666666666;
                                        v3_6 = 1.0;
                                        v0_13 = 0x3fd3333333333333;
                                        v1_6 = 0x3fc3333333333333;
                                        id obj_39 = _objc_retainAutorelease(
                                            _objc_retainAutoreleasedReturnValue(_objc_msgSend(
                                            clsRef_UIColor, "colorWithRed:green:blue:alpha:", 
                                            x2_38, x3_5, x4_12, x5_4)));
                                        var_198 = _objc_msgSend(obj_39, "CGColor");
                                        id obj_40 = _objc_retainAutoreleasedReturnValue(
                                            _objc_msgSend(clsRef_NSArray, 
                                            "arrayWithObjects:count:"));
                                        _objc_msgSend(obj_37, "setColors:", obj_40);
                                        _objc_release(obj_40);
                                        _objc_release(obj_39);
                                        _objc_release(obj_38);
                                        id obj_41 = _objc_retainAutoreleasedReturnValue(
                                            _objc_msgSend(data_446b80, "layer"));
                                        _objc_msgSend(obj_41, "insertSublayer:atIndex:", obj_37, 0);
                                        _objc_release(obj_41);
                                        int64_t x2_41;
                                        int128_t v0_14;
                                        x2_41 = _objc_msgSend(data_446b80, "setTitle:forState:", 
                                            &cfstr_??, 0);
                                        v0_14 = 24.0;
                                        id obj_42 = _objc_retainAutoreleasedReturnValue(
                                            _objc_msgSend(clsRef_UIFont, "systemFontOfSize:", 
                                            x2_41));
                                        id obj_43 = _objc_retainAutoreleasedReturnValue(
                                            _objc_msgSend(data_446b80, "titleLabel"));
                                        _objc_msgSend(obj_43, "setFont:", obj_42);
                                        _objc_release(obj_43);
                                        _objc_release(obj_42);
                                        _objc_msgSend(data_446b80, 
                                            "addTarget:action:forControlEvents:", 
                                            _objc_msgSend(clsRef_ACPanelController, "class"), 
                                            "openMenu", 0x40);
                                        id obj_44 = _objc_msgSend(
                                            _objc_alloc(clsRef_UIPanGestureRecognizer), 
                                            "initWithTarget:action:", 
                                            _objc_msgSend(clsRef_ACPanelController, "class"), 
                                            "handleDrag:");
                                        _objc_msgSend(data_446b80, "addGestureRecognizer:", obj_44);
                                        _objc_msgSend(obj_77, "addSubview:", data_446b80);
                                        _objc_release(obj_44);
                                        _objc_release(obj_37);
                                        obj_60 = obj_77;
                                        goto label_42c8d4;
                                    }
                                    
                                    x27_2 += 1;
                                } while (j_2 != x27_2);
                                
                                j_1 = _objc_msgSend(obj_27, 
                                    "countByEnumeratingWithState:objects:count:");
                                j_2 = j_1;
                            } while (j_1);
                        }
                        
                        _objc_release(obj_27);
                        i_4 = i_5;
                    }
                    
                label_42c384:
                    x25_2 += 1;
                } while (x25_2 != i_4);
                
                i_2 = _objc_msgSend(obj_60, "countByEnumeratingWithState:objects:count:");
                i_4 = i_2;
            } while (i_2);
        }
        
    label_42c8d4:
        _objc_release(obj_60);
    }
    
    sub_410c94(&cfstr_[?rbit_V7]_Ready!);
    id x0_319 = _objc_retainAutoreleasedReturnValue(_dispatch_get_global_queue(0, 0));
    _dispatch_async(x0_319, &data_43c5d0);
    _objc_release(x0_319);
    _objc_release(obj_61);
    int64_t result = _objc_release(obj);
    
    if (*___stack_chk_guard == x8)
        return result;
    
    ___stack_chk_fail();
    /* no return */
}

int64_t sub_42c9a0(void* arg1)
{
    int128_t v0;
    v0 = 0.0;
    int64_t entry_x2;
    /* tailcall */
    return _objc_msgSend(*(arg1 + 0x20), "setAlpha:", entry_x2);
}

int64_t sub_42c9b4(void* arg1)
{
    /* tailcall */
    return _objc_msgSend(*(arg1 + 0x20), "removeFromSuperview");
}

int64_t sub_42c9c4()
{
    id x0_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSURL, "URLWithString:", 
        &cfstr_https://raw.githubusercontent.com/hluysterd-del/ACCompanion/master/version.txt));
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
        "stringWithContentsOfURL:encoding:error:", x0_2, 4, 0));
    
    if (obj)
    {
        id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSCharacterSet, 
            "whitespaceAndNewlineCharacterSet"));
        id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj, 
            "stringByTrimmingCharactersInSet:", obj_1));
        _objc_release(obj);
        _objc_release(obj_1);
        id obj_4 = data_446758;
        data_446758 = obj_2;
        id obj_3 = _objc_retain(obj_2);
        _objc_release(obj_4);
        _objc_retainAutorelease(__dispatch_main_q);
        _dispatch_async(__dispatch_main_q, &data_43c5f0);
        _objc_release(obj_3);
    }
    
    /* tailcall */
    return _objc_release(x0_2);
}

int64_t sub_42cad8(struct _Unwind_Exception* arg1, int32_t arg2, int64_t arg3, int64_t arg4, int64_t arg5, int64_t arg6, int64_t arg7, int64_t arg8)
{
    if (arg2 != 1)
    {
        __Unwind_Resume(arg1);
        /* tailcall */
        return sub_42cafc();
    }
    
    _objc_begin_catch(arg1);
    /* tailcall */
    return _objc_end_catch();
}

int64_t sub_42cafc()
{
    int64_t x8 = *___stack_chk_guard;
    
    if (!(_objc_msgSend(&cfstr_V7, "isEqualToString:", data_446758) & 1))
    {
        struct objc_class_t* clsRef_UIAlertController_1 = clsRef_UIAlertController;
        struct __NSConstantString* const var_230_1 = &cfstr_V7;
        void* var_228_1 = data_446758;
        id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
            "stringWithFormat:", 
            &cfstr_Oops!_It_doesn't_look_like_you're_on_the_right_version.\n\nYou_have:_%@\nLatest:_%@\n\nPlease_join_the_Discord_to_get_the_newest_version!));
        id obj_13 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIAlertController_1, 
            "alertControllerWithTitle:message:preferredStyle:", &cfstr_Update_Available!, obj_1, 
            1));
        _objc_release(obj_1);
        id obj_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIAlertAction, 
            "actionWithTitle:style:handler:", &cfstr_Join_Discord, 0, &data_43c630));
        _objc_msgSend(obj_13, "addAction:", obj_2);
        _objc_release(obj_2);
        id obj_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIAlertAction, 
            "actionWithTitle:style:handler:", &cfstr_Later, 1, 0));
        _objc_msgSend(obj_13, "addAction:", obj_3);
        _objc_release(obj_3);
        int128_t var_190;
        __builtin_memset(&var_190, 0, 0x20);
        int128_t var_1b0;
        __builtin_memset(&var_1b0, 0, 0x18);
        id obj_4 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIApplication, 
            "sharedApplication"));
        id obj_9 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_4, "connectedScenes"));
        _objc_release(obj_4);
        void var_f0;
        id obj_14 = _objc_msgSend(obj_9, "countByEnumeratingWithState:objects:count:", &var_1b0, 
            &var_f0, 0x10);
        id obj_11 = obj_14;
        
        if (!obj_14)
            _objc_release(obj_9);
        else
        {
            id obj = nullptr;
            int64_t* var_1a0;
            int64_t x22_1 = *var_1a0;
            id i;
            
            do
            {
                int64_t x26_1 = 0;
                
                do
                {
                    if (*var_1a0 != x22_1)
                        _objc_enumerationMutation(obj_9);
                    
                    void* x19_4 = *(*(&var_1b0 + 8) + (x26_1 << 3));
                    _objc_msgSend(clsRef_UIWindowScene, "class");
                    
                    if (_objc_msgSend(x19_4, "isKindOfClass:"))
                    {
                        int128_t var_1f0;
                        __builtin_memset(&var_1f0, 0, 0x40);
                        id obj_5 =
                            _objc_retainAutoreleasedReturnValue(_objc_msgSend(x19_4, "windows"));
                        int64_t j_2 =
                            _objc_msgSend(obj_5, "countByEnumeratingWithState:objects:count:");
                        
                        if (j_2)
                        {
                            int64_t j_1 = j_2;
                            int64_t x22_2 = *0;
                            int64_t j;
                            
                            do
                            {
                                int64_t x21_1 = 0;
                                
                                do
                                {
                                    if (*0 != x22_2)
                                        _objc_enumerationMutation(obj_5);
                                    
                                    id obj_10 = *(x21_1 << 3);
                                    
                                    if (_objc_msgSend(obj_10, "isKeyWindow"))
                                    {
                                        id obj_15 = _objc_retain(obj_10);
                                        _objc_release(obj);
                                        obj = obj_15;
                                        goto label_42ce9c;
                                    }
                                    
                                    x21_1 += 1;
                                } while (j_1 != x21_1);
                                
                                j = _objc_msgSend(obj_5, 
                                    "countByEnumeratingWithState:objects:count:");
                                j_1 = j;
                            } while (j);
                        }
                        
                    label_42ce9c:
                        _objc_release(obj_5);
                    }
                    
                    x26_1 += 1;
                } while (x26_1 != obj_11);
                
                i = _objc_msgSend(obj_9, "countByEnumeratingWithState:objects:count:");
                obj_11 = i;
            } while (i);
            _objc_release(obj_9);
            obj_11 = obj;
            
            if (obj_11)
            {
                id obj_6 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_11, 
                    "rootViewController"));
                _objc_release(obj_6);
                
                if (obj_6)
                {
                    id obj_16 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_11, 
                        "rootViewController"));
                    obj_9 = obj_16;
                    id obj_7 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_16, 
                        "presentedViewController"));
                    _objc_release(obj_7);
                    
                    if (obj_7)
                    {
                        id obj_12 = obj_9;
                        id obj_17;
                        id obj_8;
                        
                        do
                        {
                            obj_17 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_12, 
                                "presentedViewController"));
                            _objc_release(obj_12);
                            obj_8 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_17, 
                                "presentedViewController"));
                            _objc_release(obj_8);
                            obj_12 = obj_17;
                        } while (obj_8);
                        obj_9 = obj_17;
                    }
                    
                    _objc_msgSend(obj_9, "presentViewController:animated:completion:", obj_13, 1, 
                        0);
                    _objc_release(obj_9);
                }
            }
        }
        
        _objc_release(obj_11);
        int64_t result = _objc_release(obj_13);
        
        if (*___stack_chk_guard == x8)
            return result;
    }
    else
    {
        struct __NSConstantString* const var_230 = &cfstr_V7;
        id x0_3 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
            "stringWithFormat:", &cfstr_Version_%@_is_up_to_date!));
        sub_410c94(x0_3);
        
        if (*___stack_chk_guard == x8)
            /* tailcall */
            return _objc_release(x0_3);
    }
    
    ___stack_chk_fail();
    /* no return */
}

int64_t sub_42d008()
{
    id x0_2 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSURL, "URLWithString:", 
        &cfstr_https://discord.gg/ezWxtYS5nD));
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_UIApplication, 
        "sharedApplication"));
    _objc_msgSend(obj, "openURL:options:completionHandler:", x0_2, *___NSDictionary0__, 0);
    _objc_release(obj);
    /* tailcall */
    return _objc_release(x0_2);
}

int64_t sub_42d094()
{
    id x0 = _objc_loadWeakRetained(&data_446a80);
    
    if (x0)
    {
        _objc_msgSend(x0, "setText:", data_446a78);
        id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(x0, "text"));
        id x0_4 = _objc_msgSend(obj, "length");
        _objc_release(obj);
        
        if (x0_4)
        {
            id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(x0, "text"));
            _objc_msgSend(x0, "scrollRangeToVisible:", _objc_msgSend(obj_1, "length") - 1);
            _objc_release(obj_1);
        }
    }
    
    /* tailcall */
    return _objc_release(x0);
}

uint64_t sub_42d16c(int64_t arg1, int64_t arg2, int64_t arg3)
{
    if (!arg1)
        return 0;
    
    int64_t var_28 = 0;
    data_446b08(arg1, arg2, arg3, &var_28);
    int64_t x8_2 = var_28;
    int64_t x2;
    
    x2 = !x8_2 ? &cfstr_[OK]_%s : &cfstr_[FAIL]_%s;
    
    int64_t x3;
    int64_t var_30_1 = x3;
    id obj = _objc_retainAutoreleasedReturnValue(_objc_msgSend(clsRef_NSString, 
        "stringWithFormat:", x2));
    sub_410c94(obj);
    _objc_release(obj);
    return !x8_2 ? 1 : 0;
}

int64_t sub_42d204(id arg1, id arg2)
{
    int64_t x8 = *___stack_chk_guard;
    id obj_3 = _objc_retain(arg1);
    id obj = _objc_retain(arg2);
    id obj_1 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_3, "objectForKeyedSubscript:", 
        &cfstr_itemID));
    
    if (obj_1 && _objc_msgSend(obj_1, "length"))
        _objc_msgSend(obj, "addObject:", obj_1);
    
    id obj_4 = _objc_retainAutoreleasedReturnValue(_objc_msgSend(obj_3, "objectForKeyedSubscript:", 
        &cfstr_children));
    
    if (_objc_msgSend(obj_4, "isKindOfClass:", _objc_msgSend(clsRef_NSArray, "class")))
    {
        int128_t var_110;
        __builtin_memset(&var_110, 0, 0x20);
        int128_t var_130;
        __builtin_memset(&var_130, 0, 0x18);
        id obj_2 = _objc_retain(obj_4);
        void var_f0;
        id i_2 = _objc_msgSend(obj_2, "countByEnumeratingWithState:objects:count:", &var_130, 
            &var_f0, 0x10);
        
        if (i_2)
        {
            id i_1 = i_2;
            int64_t* var_120;
            int64_t x19 = *var_120;
            id i;
            
            do
            {
                int64_t x22 = 0;
                
                do
                {
                    if (*var_120 != x19)
                        _objc_enumerationMutation(obj_2);
                    
                    id x28_1 = *(*(&var_130 + 8) + (x22 << 3));
                    
                    if (_objc_msgSend(x28_1, "isKindOfClass:", 
                            _objc_msgSend(clsRef_NSDictionary, "class")))
                        sub_42d204(x28_1, obj);
                    
                    x22 += 1;
                } while (i_1 != x22);
                
                i = _objc_msgSend(obj_2, "countByEnumeratingWithState:objects:count:", &var_130, 
                    &var_f0, 0x10);
                i_1 = i;
            } while (i);
        }
        
        _objc_release(obj_2);
    }
    
    _objc_release(obj_4);
    _objc_release(obj_1);
    _objc_release(obj);
    int64_t result = _objc_release(obj_3);
    
    if (*___stack_chk_guard == x8)
        return result;
    
    ___stack_chk_fail();
    /* no return */
}

uint64_t sub_42d42c(int32_t arg1, int32_t arg2, int32_t arg3, int32_t arg4)
{
    int64_t x8 = *___stack_chk_guard;
    int32_t var_c0 = arg4;
    int32_t var_bc = arg3;
    int64_t x0 = data_446ae8;
    int32_t x21;
    
    if (!x0)
        x21 = 0;
    else
    {
        int64_t x20_1 = (&data_43c670)[arg1];
        int64_t x0_1 = data_446ae0(x0, &cstr_, x20_1);
        int64_t x19_1 = x0_1;
        int64_t x0_3;
        
        if (!x0_1)
        {
            x0_3 = data_446ae0(data_446ae8, "AnimalCompany", x20_1);
            x19_1 = x0_3;
        }
        
        if (!x0_1 && !x0_3)
            x21 = 0;
        else
        {
            void* x0_5 = sub_42de18(x19_1);
            
            if (!x0_5)
                x21 = 0;
            else
            {
                int32_t x8_3 = *(x0_5 + 0x18);
                
                if (x8_3 < 1)
                    x21 = 0;
                else
                {
                    int32_t* var_a8;
                    
                    if (arg1 <= 0xd)
                    {
                        int64_t x9_1 = arg1;
                        int64_t x23_1 = (&data_43c7c8)[x9_1];
                        
                        if (arg1 < 0xe || x23_1)
                        {
                            x21 = 0;
                            int32_t i_5;
                            
                            i_5 = x8_3 < 3 ? 0 : x8_3 - 3;
                            
                            bool v_1;
                            bool z_1;
                            bool n_1;
                            
                            if (x8_3 > arg2)
                            {
                                v_1 = arg2 + 0;
                                z_1 = !arg2;
                                n_1 = arg2 < 0;
                            }
                            else
                            {
                                n_1 = false;
                                z_1 = true;
                                v_1 = false;
                            }
                            
                            uint64_t i;
                            
                            i = !z_1 && n_1 == v_1 ? arg2 : i_5;
                            
                            if (i < x8_3)
                            {
                                x21 = 0;
                                int64_t x8_4 = (&data_43c710)[x9_1];
                                
                                do
                                {
                                    int64_t x25_1 = *(x0_5 + 0x20 + (i << 3));
                                    
                                    if (x25_1)
                                    {
                                        if (arg1 <= 0xd)
                                        {
                                            int64_t x26_1;
                                            
                                            if (arg1 - 0xb > 2)
                                            {
                                                int64_t x0_9 = data_446b18(x19_1, x8_4);
                                                x26_1 = x0_9;
                                                
                                                if (x0_9)
                                                    data_446b70(x25_1, x26_1, &var_bc);
                                            }
                                            else
                                            {
                                                var_a8 = var_c0 | (0xffffff & var_bc) << 8;
                                                int64_t x0_7 = data_446b18(x19_1, x8_4);
                                                x26_1 = x0_7;
                                                
                                                if (x0_7)
                                                    data_446b70(x25_1, x26_1, &var_a8);
                                            }
                                            
                                            x21 |= x26_1 ? 1 : 0;
                                        }
                                        
                                        if (x23_1)
                                        {
                                            int64_t x0_12 = data_446b18(x19_1, x23_1);
                                            
                                            if (x0_12)
                                                data_446b70(x25_1, x0_12, &var_c0);
                                            
                                            x21 |= x0_12 ? 1 : 0;
                                        }
                                    }
                                    
                                    i += 1;
                                } while (i < *(x0_5 + 0x18));
                            }
                        }
                        else
                            x21 = 0;
                    }
                    else
                    {
                        int32_t* var_a0;
                        
                        if (arg1 == 0xe)
                        {
                            int64_t x0_14 = data_446b98;
                            
                            if (!x0_14)
                                x21 = 0;
                            else
                            {
                                int64_t x0_15 = data_446b10(x0_14, "SpawnItem", 6);
                                int64_t x19_2 = x0_15;
                                
                                if (x0_15)
                                {
                                label_42d6c0:
                                    int64_t x0_23 = sub_42172c(data_446b98);
                                    
                                    if (!x0_23)
                                        x21 = 0;
                                    else
                                    {
                                        var_a8 = &var_bc;
                                        var_a0 = &var_c0;
                                        x21 = sub_42d16c(x19_2, x0_23, &var_a8);
                                    }
                                }
                                else
                                {
                                    int64_t x0_17 = data_446b10(data_446b98, "SpawnItem", 5);
                                    x19_2 = x0_17;
                                    
                                    if (x0_17)
                                        goto label_42d6c0;
                                    
                                    int64_t x0_19 =
                                        data_446b10(data_446b98, "SpawnItemColored", 0xffffffff);
                                    x19_2 = x0_19;
                                    
                                    if (x0_19)
                                        goto label_42d6c0;
                                    
                                    int64_t x0_21 =
                                        data_446b10(data_446b98, "SpawnItemWithColor", 0xffffffff);
                                    x19_2 = x0_21;
                                    
                                    if (x0_21)
                                        goto label_42d6c0;
                                    
                                    x21 = 0;
                                }
                            }
                        }
                        else
                        {
                            int32_t* var_b8;
                            int32_t* var_70;
                            
                            if (arg1 <= 0x11)
                            {
                                x21 = 0;
                                int32_t i_3;
                                
                                i_3 = x8_3 < 3 ? 0 : x8_3 - 3;
                                
                                bool v_2;
                                bool z_2;
                                bool n_2;
                                
                                if (x8_3 > arg2)
                                {
                                    v_2 = arg2 + 0;
                                    z_2 = !arg2;
                                    n_2 = arg2 < 0;
                                }
                                else
                                {
                                    n_2 = false;
                                    z_2 = true;
                                    v_2 = false;
                                }
                                
                                uint64_t i_1;
                                
                                i_1 = !z_2 && n_2 == v_2 ? arg2 : i_3;
                                
                                if (i_1 < x8_3)
                                {
                                    int64_t x22_1 = (&data_43c7b0)[arg1 - 0xf];
                                    
                                    do
                                    {
                                        int64_t x21_1 = *(x0_5 + 0x20 + (i_1 << 3));
                                        
                                        if (x21_1)
                                        {
                                            var_a8 = &var_bc;
                                            var_a0 = &var_c0;
                                            int64_t x0_27 = data_446b10(x19_1, x22_1, 2);
                                            
                                            if (x0_27)
                                            {
                                                var_b8 = nullptr;
                                                data_446b08(x0_27, x21_1, &var_a8, &var_b8);
                                            }
                                            
                                            if (x0_27 && !var_b8)
                                            {
                                                x21 = 1;
                                                break;
                                            }
                                            
                                            var_70 = &var_bc;
                                            int64_t x0_29 = data_446b10(x19_1, x22_1, 1);
                                            
                                            if (x0_29)
                                            {
                                                var_b8 = nullptr;
                                                data_446b08(x0_29, x21_1, &var_70, &var_b8);
                                                
                                                if (!var_b8)
                                                {
                                                    x21 = 1;
                                                    break;
                                                }
                                            }
                                            
                                            x8_3 = *(x0_5 + 0x18);
                                        }
                                        
                                        x21 = 0;
                                        i_1 += 1;
                                    } while (i_1 < x8_3);
                                }
                            }
                            else if (arg1 == 0x13)
                            {
                                int64_t x0_38 = data_446b98;
                                
                                if (!x0_38)
                                    x21 = 0;
                                else
                                {
                                    char const* const x19_3 = "RPC_SetItemColor";
                                    var_a8 = "RPC_SetItemColor";
                                    var_a0 = "RPC_SpawnItemColored";
                                    char const* const var_98_1 = "RPC_ChangeColor";
                                    char const* const var_90_1 = "SetItemColorRPC";
                                    char const* const var_88_1 = "PhotonSetColor";
                                    int64_t x0_39 = sub_42172c(x0_38);
                                    int64_t x24_4 = 0;
                                    x21 = 1;
                                    
                                    while (true)
                                    {
                                        int64_t x0_41 = data_446b10(data_446b98, x19_3, 0xffffffff);
                                        
                                        if (x0_41)
                                        {
                                            var_b8 = &var_bc;
                                            int32_t* var_b0_1 = &var_c0;
                                            
                                            if (sub_42d16c(x0_41, x0_39, &var_b8) & 1)
                                                break;
                                        }
                                        
                                        x21 = x24_4 < 4 ? 1 : 0;
                                        
                                        if (x24_4 == 4)
                                            break;
                                        
                                        x19_3 = (&var_a0)[x24_4];
                                        x24_4 += 1;
                                    }
                                }
                            }
                            else if (arg1 != 0x12)
                                x21 = 0;
                            else
                            {
                                x21 = 0;
                                int32_t i_4;
                                
                                i_4 = x8_3 < 3 ? 0 : x8_3 - 3;
                                
                                bool v_3;
                                bool z_3;
                                bool n_3;
                                
                                if (x8_3 > arg2)
                                {
                                    v_3 = arg2 + 0;
                                    z_3 = !arg2;
                                    n_3 = arg2 < 0;
                                }
                                else
                                {
                                    n_3 = false;
                                    z_3 = true;
                                    v_3 = false;
                                }
                                
                                uint64_t i_2;
                                
                                i_2 = !z_3 && n_3 == v_3 ? arg2 : i_4;
                                
                                if (i_2 < x8_3)
                                {
                                    x21 = 0;
                                    
                                    do
                                    {
                                        int64_t x26_3 = *(x0_5 + 0x20 + (i_2 << 3));
                                        
                                        if (x26_3)
                                        {
                                            var_b8 = &var_bc;
                                            int64_t x0_31 = data_446b10(x19_1, "set_colorHue", 1);
                                            int32_t x22_2;
                                            
                                            if (!x0_31)
                                                x22_2 = 0;
                                            else
                                            {
                                                var_a8 = nullptr;
                                                data_446b08(x0_31, x26_3, &var_b8, &var_a8);
                                                x22_2 = !var_a8 ? 1 : 0;
                                            }
                                            
                                            var_70 = &var_c0;
                                            int64_t x0_33 =
                                                data_446b10(x19_1, "set_colorSaturation", 1);
                                            int32_t x24_3;
                                            
                                            if (!x0_33)
                                                x24_3 = 0;
                                            else
                                            {
                                                var_a8 = nullptr;
                                                data_446b08(x0_33, x26_3, &var_70, &var_a8);
                                                x24_3 = !var_a8 ? 1 : 0;
                                            }
                                            
                                            int32_t* var_78 = &var_bc;
                                            int64_t x0_35 = data_446b10(x19_1, "set_hue", 1);
                                            int32_t x25_2;
                                            
                                            if (!x0_35)
                                                x25_2 = 0;
                                            else
                                            {
                                                var_a8 = nullptr;
                                                data_446b08(x0_35, x26_3, &var_78, &var_a8);
                                                x25_2 = !var_a8 ? 1 : 0;
                                            }
                                            
                                            int32_t* var_80 = &var_c0;
                                            int64_t x0_37 = data_446b10(x19_1, "set_saturation", 1);
                                            int32_t x8_38;
                                            
                                            if (!x0_37)
                                                x8_38 = 0;
                                            else
                                            {
                                                var_a8 = nullptr;
                                                data_446b08(x0_37, x26_3, &var_80, &var_a8);
                                                x8_38 = !var_a8 ? 1 : 0;
                                            }
                                            
                                            x21 |= x8_38 | x25_2 | x24_3 | x22_2;
                                            x8_3 = *(x0_5 + 0x18);
                                        }
                                        
                                        i_2 += 1;
                                    } while (i_2 < x8_3);
                                }
                            }
                        }
                    }
                }
            }
        }
    }
    
    if (*___stack_chk_guard == x8)
        return x21 & 1;
    
    ___stack_chk_fail();
    /* no return */
}

uint64_t sub_42da88(int32_t arg1, int32_t arg2, int32_t arg3)
{
    int64_t x8 = *___stack_chk_guard;
    int32_t var_a4 = arg3;
    int64_t x0 = data_446ae8;
    int32_t x25_1;
    
    if (!x0)
        x25_1 = 0;
    else
    {
        int64_t x0_1 = data_446ae0(x0, &cstr_, "ItemInstance");
        int64_t x19_1 = x0_1;
        
        if (x0_1)
        {
        label_42db1c:
            void* x0_5 = sub_42de18(x19_1);
            
            if (!x0_5)
                x25_1 = 0;
            else
            {
                int32_t x8_3 = *(x0_5 + 0x18);
                
                if (x8_3 < 1)
                    x25_1 = 0;
                else
                {
                    int32_t i_1;
                    
                    i_1 = x8_3 < 3 ? 0 : x8_3 - 3;
                    
                    bool v_1;
                    bool z_1;
                    bool n_1;
                    
                    if (x8_3 > arg2)
                    {
                        v_1 = arg2 + 0;
                        z_1 = !arg2;
                        n_1 = arg2 < 0;
                    }
                    else
                    {
                        n_1 = false;
                        z_1 = true;
                        v_1 = false;
                    }
                    
                    uint64_t i;
                    
                    i = !z_1 && n_1 == v_1 ? arg2 : i_1;
                    
                    if (arg1 > 0xd)
                    {
                        char const* const var_a0;
                        int32_t* var_70;
                        
                        if (arg1 > 0x10)
                        {
                            uint64_t x22_4 = arg1 - 0x11;
                            
                            if (x22_4 > 1)
                            {
                                var_a0 = "localScale";
                                char const* const var_98_1 = "modelScale";
                                char const* const var_90_1 = "prefabScale";
                                char const* const var_88_1 = "spawnScale";
                                char const* const var_80_1 = "baseScale";
                                char const* const var_78_1 = "customScale";
                                
                                if (i < x8_3)
                                {
                                    do
                                    {
                                        int64_t x21_4 = *(x0_5 + 0x20 + (i << 3));
                                        
                                        if (x21_4)
                                        {
                                            for (int64_t j = 0; j != 0x30; j += 8)
                                            {
                                                int64_t x0_18 = data_446b18(x19_1, *(&var_a0 + j));
                                                
                                                if (x0_18)
                                                {
                                                    data_446b70(x21_4, x0_18, &var_a4);
                                                    goto label_42de0c;
                                                }
                                            }
                                            
                                            x8_3 = *(x0_5 + 0x18);
                                        }
                                        
                                        i += 1;
                                    } while (i < x8_3);
                                }
                                
                                x25_1 = 0;
                            }
                            else if (i >= x8_3)
                                x25_1 = 0;
                            else
                            {
                                do
                                {
                                    int64_t x21_3 = *(x0_5 + 0x20 + (i << 3));
                                    
                                    if (x21_3)
                                    {
                                        var_70 = &var_a4;
                                        int64_t x0_16 =
                                            data_446b10(x19_1, (&data_43c920)[x22_4], 1);
                                        
                                        if (x0_16)
                                        {
                                            var_a0 = nullptr;
                                            data_446b08(x0_16, x21_3, &var_70, &var_a0);
                                            
                                            if (!var_a0)
                                                goto label_42de0c;
                                        }
                                        
                                        x8_3 = *(x0_5 + 0x18);
                                    }
                                    
                                    x25_1 = 0;
                                    i += 1;
                                } while (i < x8_3);
                            }
                        }
                        else if (i >= x8_3)
                            x25_1 = 0;
                        else
                        {
                            do
                            {
                                int64_t x21_2 = *(x0_5 + 0x20 + (i << 3));
                                
                                if (x21_2)
                                {
                                    var_70 = &var_a4;
                                    int64_t x0_10 =
                                        data_446b10(x19_1, (&data_43c908)[arg1 - 0xe], 1);
                                    
                                    if (x0_10)
                                    {
                                        var_a0 = nullptr;
                                        data_446b08(x0_10, x21_2, &var_70, &var_a0);
                                        
                                        if (!var_a0)
                                        {
                                        label_42de0c:
                                            x25_1 = 1;
                                            break;
                                        }
                                    }
                                    
                                    x8_3 = *(x0_5 + 0x18);
                                }
                                
                                x25_1 = 0;
                                i += 1;
                            } while (i < x8_3);
                        }
                    }
                    else if (i >= x8_3)
                        x25_1 = 0;
                    else
                    {
                        x25_1 = 0;
                        int64_t x21_1 = (&data_43c868)[arg1];
                        
                        do
                        {
                            int64_t x22_2 = *(x0_5 + 0x20 + (i << 3));
                            
                            if (x22_2)
                            {
                                int64_t x0_7 = data_446b18(x19_1, x21_1);
                                
                                if (x0_7)
                                    data_446b70(x22_2, x0_7, &var_a4);
                                
                                x25_1 |= x0_7 ? 1 : 0;
                                x8_3 = *(x0_5 + 0x18);
                            }
                            
                            i += 1;
                        } while (i < x8_3);
                    }
                }
            }
        }
        else
        {
            int64_t x0_3 = data_446ae0(data_446ae8, "AnimalCompany", "ItemInstance");
            x19_1 = x0_3;
            
            if (x0_3)
                goto label_42db1c;
            
            int64_t x0_11 = data_446ae8;
            
            if (!x0_11)
                x25_1 = 0;
            else
            {
                int64_t x0_12 = data_446ae0(x0_11, &cstr_, "Item");
                x19_1 = x0_12;
                
                if (x0_12)
                    goto label_42db1c;
                
                int64_t x0_14 = data_446ae0(data_446ae8, "AnimalCompany", "Item");
                x19_1 = x0_14;
                
                if (x0_14)
                    goto label_42db1c;
                
                x25_1 = 0;
            }
        }
    }
    
    if (*___stack_chk_guard == x8)
        return x25_1 & 1;
    
    ___stack_chk_fail();
    /* no return */
}

int64_t sub_42de18(int64_t arg1)
{
    int64_t result = 0;
    int64_t x9 = *___stack_chk_guard;
    
    if (arg1 && data_446af0)
    {
        result = data_446af8(arg1);
        
        if (result)
        {
            result = data_446b00();
            
            if (result)
            {
                int64_t var_38 = 0;
                int64_t result_1 = result;
                result = data_446b08(data_446af0, 0, &result_1, &var_38);
            }
        }
    }
    
    if (*___stack_chk_guard == x9)
        return result;
    
    ___stack_chk_fail();
    /* no return */
}

int64_t sub_42dec0(char* arg1)
{
    int64_t x0 = data_446bf8();
    
    if (!x0)
        return 0;
    
    int64_t var_48 = 0;
    int64_t x0_1 = data_446c00(x0, &var_48);
    bool z_1;
    
    z_1 = x0_1 ? !var_48 : true;
    
    if (z_1)
        return 0;
    
    int64_t x22_1 = 0;
    
    while (true)
    {
        int64_t result = data_446c08(*(x0_1 + (x22_1 << 3)));
        
        if (result)
        {
            char* __s1 = data_446c10();
            
            if (__s1 && !_strcmp(__s1, arg1))
                return result;
        }
        
        x22_1 += 1;
        
        if (x22_1 >= var_48)
            return 0;
    }
}

struct CGAffineTransform _CGAffineTransformMakeScale(CGFloat sx, CGFloat sy)
{
    /* tailcall */
    return _CGAffineTransformMakeScale(sx, sy);
}

void _NSLog(NSString* arg1, ...)
{
    /* tailcall */
    return _NSLog(arg1);
}

struct objc_object* _NSSearchPathForDirectoriesInDomains(enum NSSearchPathDirectory directory, NSSearchPathDomainMask domainMask, BOOL expandTilde)
{
    /* tailcall */
    return _NSSearchPathForDirectoriesInDomains(directory, domainMask, expandTilde);
}

void __Block_object_assign(void* arg1, void const* arg2, int32_t const arg3)
{
    /* tailcall */
    return __Block_object_assign(arg1, arg2, arg3);
}

void __Block_object_dispose(void const* arg1, int32_t const arg2)
{
    /* tailcall */
    return __Block_object_dispose(arg1, arg2);
}

void __Unwind_Resume(struct _Unwind_Exception* exception_object)
{
    /* tailcall */
    return __Unwind_Resume(exception_object);
}

struct __float2 ___sincosf_stret(float arg1)
{
    /* tailcall */
    return ___sincosf_stret(arg1);
}

void ___stack_chk_fail() __noreturn
{
    /* tailcall */
    return ___stack_chk_fail();
}

int64_t __dyld_get_image_name()
{
    /* tailcall */
    return __dyld_get_image_name();
}

int64_t __dyld_image_count()
{
    /* tailcall */
    return __dyld_image_count();
}

uint32_t _arc4random_uniform(uint32_t __upper_bound)
{
    /* tailcall */
    return _arc4random_uniform(__upper_bound);
}

float _cosf(float arg1)
{
    /* tailcall */
    return _cosf(arg1);
}

void _dispatch_after(dispatch_time_t when, dispatch_queue_t queue, dispatch_block_t block)
{
    /* tailcall */
    return _dispatch_after(when, queue, block);
}

void _dispatch_async(dispatch_queue_t queue, dispatch_block_t block)
{
    /* tailcall */
    return _dispatch_async(queue, block);
}

dispatch_queue_global_t _dispatch_get_global_queue(intptr_t identifier, uintptr_t flags)
{
    /* tailcall */
    return _dispatch_get_global_queue(identifier, flags);
}

dispatch_time_t _dispatch_time(dispatch_time_t when, int64_t delta)
{
    /* tailcall */
    return _dispatch_time(when, delta);
}

void* _dlopen(char const* __path, int32_t __mode)
{
    /* tailcall */
    return _dlopen(__path, __mode);
}

void* _dlsym(void* __handle, char const* __symbol)
{
    /* tailcall */
    return _dlsym(__handle, __symbol);
}

id _objc_alloc(Class cls)
{
    /* tailcall */
    return _objc_alloc(cls);
}

id _objc_alloc_init(Class cls)
{
    /* tailcall */
    return _objc_alloc_init(cls);
}

id _objc_autorelease(id obj)
{
    /* tailcall */
    return _objc_autorelease(obj);
}

id _objc_autoreleaseReturnValue(id obj)
{
    /* tailcall */
    return _objc_autoreleaseReturnValue(obj);
}

id _objc_begin_catch(void* exc_buf)
{
    /* tailcall */
    return _objc_begin_catch(exc_buf);
}

void _objc_copyWeak(id* to, id* from)
{
    /* tailcall */
    return _objc_copyWeak(to, from);
}

void _objc_destroyWeak(id* location)
{
    /* tailcall */
    return _objc_destroyWeak(location);
}

void _objc_end_catch()
{
    /* tailcall */
    return _objc_end_catch();
}

void _objc_enumerationMutation(id obj)
{
    /* tailcall */
    return _objc_enumerationMutation(obj);
}

id _objc_initWeak(id* location, id val)
{
    /* tailcall */
    return _objc_initWeak(location, val);
}

id _objc_loadWeakRetained(id* location)
{
    /* tailcall */
    return _objc_loadWeakRetained(location);
}

void _objc_msgSend(void* self, char* cmd)
{
    /* tailcall */
    return _objc_msgSend(self, cmd);
}

id _objc_msgSendSuper2(struct objc_super* super, SEL op)
{
    /* tailcall */
    return _objc_msgSendSuper2(super, op);
}

void _objc_release(id obj)
{
    /* tailcall */
    return _objc_release(obj);
}

id _objc_retain(id obj)
{
    /* tailcall */
    return _objc_retain(obj);
}

id _objc_retainAutorelease(id obj)
{
    /* tailcall */
    return _objc_retainAutorelease(obj);
}

id _objc_retainAutoreleaseReturnValue(id obj)
{
    /* tailcall */
    return _objc_retainAutoreleaseReturnValue(obj);
}

id _objc_retainAutoreleasedReturnValue(id obj)
{
    /* tailcall */
    return _objc_retainAutoreleasedReturnValue(obj);
}

id _objc_retainBlock(id arg1)
{
    /* tailcall */
    return _objc_retainBlock(arg1);
}

void _objc_storeStrong(id* location, id obj)
{
    /* tailcall */
    return _objc_storeStrong(location, obj);
}

id _objc_storeWeak(id* location, id obj)
{
    /* tailcall */
    return _objc_storeWeak(location, obj);
}

float _sinf(float arg1)
{
    /* tailcall */
    return _sinf(arg1);
}

int32_t _strcmp(char const* __s1, char const* __s2)
{
    /* tailcall */
    return _strcmp(__s1, __s2);
}

char* _strstr(char* __s1, char const* __s2)
{
    /* tailcall */
    return _strstr(__s1, __s2);
}

int32_t _usleep(useconds_t arg1)
{
    /* tailcall */
    return _usleep(arg1);
}

int64_t sub_42e184()
{
    void* var_8 = &data_446750;
    /* tailcall */
    return dyld_stub_binder();
}

int64_t sub_42e19c()
{
    /* tailcall */
    return sub_42e184();
}

int64_t sub_42e1a8()
{
    /* tailcall */
    return sub_42e184();
}

int64_t sub_42e1b4()
{
    /* tailcall */
    return sub_42e184();
}

int64_t sub_42e1c0()
{
    /* tailcall */
    return sub_42e184();
}

int64_t sub_42e1cc()
{
    /* tailcall */
    return sub_42e184();
}

int64_t sub_42e1d8()
{
    /* tailcall */
    return sub_42e184();
}

int64_t sub_42e1e4()
{
    /* tailcall */
    return sub_42e184();
}

int64_t sub_42e1f0()
{
    /* tailcall */
    return sub_42e184();
}

int64_t sub_42e1fc()
{
    /* tailcall */
    return sub_42e184();
}

int64_t sub_42e208()
{
    /* tailcall */
    return sub_42e184();
}

int64_t sub_42e214()
{
    /* tailcall */
    return sub_42e184();
}

int64_t sub_42e220()
{
    /* tailcall */
    return sub_42e184();
}

int64_t sub_42e22c()
{
    /* tailcall */
    return sub_42e184();
}

int64_t sub_42e238()
{
    /* tailcall */
    return sub_42e184();
}

int64_t sub_42e244()
{
    /* tailcall */
    return sub_42e184();
}

int64_t sub_42e250()
{
    /* tailcall */
    return sub_42e184();
}

int64_t sub_42e25c()
{
    /* tailcall */
    return sub_42e184();
}

int64_t sub_42e268()
{
    /* tailcall */
    return sub_42e184();
}

int64_t sub_42e274()
{
    /* tailcall */
    return sub_42e184();
}

int64_t sub_42e280()
{
    /* tailcall */
    return sub_42e184();
}

int64_t sub_42e28c()
{
    /* tailcall */
    return sub_42e184();
}

int64_t sub_42e298()
{
    /* tailcall */
    return sub_42e184();
}

int64_t sub_42e2a4()
{
    /* tailcall */
    return sub_42e184();
}

int64_t sub_42e2b0()
{
    /* tailcall */
    return sub_42e184();
}

int64_t sub_42e2bc()
{
    /* tailcall */
    return sub_42e184();
}

int64_t sub_42e2c8()
{
    /* tailcall */
    return sub_42e184();
}

int64_t sub_42e2d4()
{
    /* tailcall */
    return sub_42e184();
}

int64_t sub_42e2e0()
{
    /* tailcall */
    return sub_42e184();
}

int64_t sub_42e2ec()
{
    /* tailcall */
    return sub_42e184();
}

int64_t sub_42e2f8()
{
    /* tailcall */
    return sub_42e184();
}

int64_t sub_42e304()
{
    /* tailcall */
    return sub_42e184();
}

int64_t sub_42e310()
{
    /* tailcall */
    return sub_42e184();
}

int64_t sub_42e31c()
{
    /* tailcall */
    return sub_42e184();
}

int64_t sub_42e328()
{
    /* tailcall */
    return sub_42e184();
}

int64_t sub_42e334()
{
    /* tailcall */
    return sub_42e184();
}

int64_t sub_42e340()
{
    /* tailcall */
    return sub_42e184();
}

int64_t sub_42e34c()
{
    /* tailcall */
    return sub_42e184();
}

int64_t sub_42e358()
{
    /* tailcall */
    return sub_42e184();
}

int64_t sub_42e364()
{
    /* tailcall */
    return sub_42e184();
}

int64_t sub_42e370()
{
    /* tailcall */
    return sub_42e184();
}

int64_t sub_42e37c()
{
    /* tailcall */
    return sub_42e184();
}

int64_t sub_42e388()
{
    /* tailcall */
    return sub_42e184();
}

int64_t sub_42e394()
{
    /* tailcall */
    return sub_42e184();
}

