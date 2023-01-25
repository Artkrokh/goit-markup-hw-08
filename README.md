.hero__container {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    width: 100vw;
    background-color: $primaryTextColor;
    background-image: $heroBackgroundGradient,
        url('../images/hero-bg-mob-1x.jpg');
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
    padding-top: 118px;
    padding-bottom: 118px;
    @include mobile {
    padding: 118px 60px;
    }
    @media (min-device-pixel-ratio: 2),
        (min-resolution: 192dpi),
        (min-resolution: 2dppx) {
        background-image: $heroBackgroundGradient,
            url('../images/hero-bg-mob-2x.jpg');}
    @include tablet {
        background-image: $heroBackgroundGradient,
            url('../images/hero-bg-tab-1x.jpg');
        padding: 118px 204px;
        @media (min-device-pixel-ratio: 2),
        (min-resolution: 192dpi),
        (min-resolution: 2dppx) {
            background-image: $heroBackgroundGradient,
                url('../images/hero-bg-tab-2x.jpg');
        }
    }
    @include desktop {
        padding-top: 200px;
        padding-bottom: 200px;
        background-image: $heroBackgroundGradient,
            url('../images/hero-bg-1x.jpg');
        @media (min-device-pixel-ratio: 2),
        (min-resolution: 192dpi),
        (min-resolution: 2dppx) {
            background-image: $heroBackgroundGradient,
                url('../images/hero-bg-2x.jpg');
        }
    }
}



.container {
    padding-left: 15px;
    padding-right: 15px;
    margin: 0 auto;
    @media screen and (min-width: $mobile) {
        max-width: $mobile;
    }
    @media screen and (min-width: $tablet) {
        max-width: $tablet;
    }
    @media screen and (min-width: $desktop) {
        max-width: $desktop;
    }
}

.hero {
    &__title {
        width: 100%;
        margin: 0 auto 20px auto;
        @include mobile {
            width: 360px;
        }
        @include font (900, 26px, 1.61, 0.06em);
        @include desktop {
            margin: 0 auto 30px auto;
            width: 696px;
            @include font (900, 44px, 1.35, 0.06em);
        }
        text-align: center;
        text-transform: uppercase;
        color: $whiteColor;
    }
        &__button {
        margin-left: auto;
        margin-right: auto;
        @media screen and (min-width: $desktop) {
        width: 216px;}
    }
}