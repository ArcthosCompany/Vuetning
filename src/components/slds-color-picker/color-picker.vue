<template>
    <div class="slds-color-picker">
        <div class="slds-form-element slds-color-picker__summary">
            <label class="slds-form-element__label slds-color-picker__summary-label" for="color-picker-summary-input">
                Choose Color
            </label>
            <div class="slds-form-element__control">
                <button class="slds-button slds-color-picker__summary-button slds-button_icon slds-button_icon-more" title="Choose Color">
                    <span class="slds-swatch" style="background:hsl(220, 46%, 55%)">
                        <span class="slds-assistive-text">hsl(220, 46%, 55%)</span>
                    </span>
                    <svg class="slds-button__icon slds-button__icon_small slds-m-left_xx-small" aria-hidden="true">
                        <use xlink:href="/assets/icons/utility-sprite/svg/symbols.svg#down"/>
                    </svg>
                    <span class="slds-assistive-text">Choose a color. Current color: #5679C0</span>
                </button>
                <div class="slds-color-picker__summary-input">
                    <input id="color-picker-summary-input" type="text" class="slds-input" value="#5679C0">
                </div>
            </div>
        </div>
        <section aria-describedby="dialog-body-id-3" aria-label="Choose a color" class="slds-popover slds-color-picker__selector slds-hide" role="dialog">
            <div id="dialog-body-id-3" class="slds-popover__body">
                <div class="slds-tabs_default">
                    <ul class="slds-tabs_default__nav" role="tablist">
                        <li class="slds-tabs_default__item slds-is-active" title="Default" role="presentation">
                            <a
                                id="color-picker-default__item"
                                class="slds-tabs_default__link"
                                href="javascript:void(0);"
                                role="tab"
                                tabindex="0"
                                aria-selected="true"
                                aria-controls="color-picker-default">
                                Default
                            </a>
                        </li>
                        <li class="slds-tabs_default__item" title="Custom" role="presentation">
                            <a
                                id="color-picker-custom__item"
                                class="slds-tabs_default__link"
                                href="javascript:void(0);"
                                role="tab"
                                tabindex="-1"
                                aria-selected="false"
                                aria-controls="color-picker-custom">
                                Custom
                            </a>
                        </li>
                    </ul>
                    <div id="color-picker-default" class="slds-tabs_default__content slds-show" role="tabpanel" aria-labelledby="color-picker-default__item">
                        <ul class="slds-color-picker__swatches" role="listbox">
                            <li class="slds-color-picker__swatch" role="presentation">
                                <a class="slds-color-picker__swatch-trigger" href="#" role="option" tabindex="0">
                                    <span class="slds-swatch" style="background:#e3abec">
                                        <span class="slds-assistive-text">#e3abec</span>
                                    </span>
                                </a>
                            </li>
                            <li class="slds-color-picker__swatch" role="presentation">
                                <a class="slds-color-picker__swatch-trigger" href="#" role="option" tabindex="-1">
                                    <span class="slds-swatch" style="background:#c2dbf7">
                                        <span class="slds-assistive-text">#c2dbf7</span>
                                    </span>
                                </a>
                            </li>
                            <li class="slds-color-picker__swatch" role="presentation">
                                <a class="slds-color-picker__swatch-trigger" href="#" role="option" tabindex="-1">
                                    <span class="slds-swatch" style="background:#9fd6ff">
                                        <span class="slds-assistive-text">#9fd6ff</span>
                                    </span>
                                </a>
                            </li>
                            <li class="slds-color-picker__swatch" role="presentation">
                                <a class="slds-color-picker__swatch-trigger" href="#" role="option" tabindex="-1">
                                    <span class="slds-swatch" style="background:#9de7da">
                                        <span class="slds-assistive-text">#9de7da</span>
                                    </span>
                                </a>
                            </li>
                            <li class="slds-color-picker__swatch" role="presentation">
                                <a class="slds-color-picker__swatch-trigger" href="#" role="option" tabindex="-1">
                                    <span class="slds-swatch" style="background:#9df0c0">
                                        <span class="slds-assistive-text">#9df0c0</span>
                                    </span>
                                </a>
                            </li>
                            <li class="slds-color-picker__swatch" role="presentation">
                                <a class="slds-color-picker__swatch-trigger" href="#" role="option" tabindex="-1">
                                    <span class="slds-swatch" style="background:#fff099">
                                        <span class="slds-assistive-text">#fff099</span>
                                    </span>
                                </a>
                            </li>
                            <li class="slds-color-picker__swatch" role="presentation">
                                <a class="slds-color-picker__swatch-trigger" href="#" role="option" tabindex="-1">
                                    <span class="slds-swatch" style="background:#fed49a">
                                        <span class="slds-assistive-text">#fed49a</span>
                                    </span>
                                </a>
                            </li>
                            <li class="slds-color-picker__swatch" role="presentation">
                                <a class="slds-color-picker__swatch-trigger" href="#" role="option" tabindex="-1">
                                    <span class="slds-swatch" style="background:#d073e0">
                                        <span class="slds-assistive-text">#d073e0</span>
                                    </span>
                                </a>
                            </li>
                            <li class="slds-color-picker__swatch" role="presentation">
                                <a class="slds-color-picker__swatch-trigger" href="#" role="option" tabindex="-1">
                                    <span class="slds-swatch" style="background:#86baf3">
                                        <span class="slds-assistive-text">#86baf3</span>
                                    </span>
                                </a>
                            </li>
                            <li class="slds-color-picker__swatch" role="presentation">
                                <a class="slds-color-picker__swatch-trigger" href="#" role="option" tabindex="-1">
                                    <span class="slds-swatch" style="background:#5ebbff">
                                        <span class="slds-assistive-text">#5ebbff</span>
                                    </span>
                                </a>
                            </li>
                            <li class="slds-color-picker__swatch" role="presentation">
                                <a class="slds-color-picker__swatch-trigger" href="#" role="option" tabindex="-1">
                                    <span class="slds-swatch" style="background:#44d8be">
                                        <span class="slds-assistive-text">#44d8be</span>
                                    </span>
                                </a>
                            </li>
                            <li class="slds-color-picker__swatch" role="presentation">
                                <a class="slds-color-picker__swatch-trigger" href="#" role="option" tabindex="-1">
                                    <span class="slds-swatch" style="background:#3be282">
                                        <span class="slds-assistive-text">#3be282</span>
                                    </span>
                                </a>
                            </li>
                            <li class="slds-color-picker__swatch" role="presentation">
                                <a class="slds-color-picker__swatch-trigger" href="#" role="option" tabindex="-1">
                                    <span class="slds-swatch" style="background:#ffe654">
                                        <span class="slds-assistive-text">#ffe654</span>
                                    </span>
                                </a>
                            </li>
                            <li class="slds-color-picker__swatch" role="presentation">
                                <a class="slds-color-picker__swatch-trigger" href="#" role="option" tabindex="-1">
                                    <span class="slds-swatch" style="background:#ffb758">
                                        <span class="slds-assistive-text">#ffb758</span>
                                    </span>
                                </a>
                            </li>
                            <li class="slds-color-picker__swatch" role="presentation">
                                <a class="slds-color-picker__swatch-trigger" href="#" role="option" tabindex="-1">
                                    <span class="slds-swatch" style="background:#bd35bd">
                                        <span class="slds-assistive-text">#bd35bd</span>
                                    </span>
                                </a>
                            </li>
                            <li class="slds-color-picker__swatch" role="presentation">
                                <a class="slds-color-picker__swatch-trigger" href="#" role="option" tabindex="-1">
                                    <span class="slds-swatch" style="background:#5779c1">
                                        <span class="slds-assistive-text">#5779c1</span>
                                    </span>
                                </a>
                            </li>
                            <li class="slds-color-picker__swatch" role="presentation">
                                <a class="slds-color-picker__swatch-trigger" href="#" role="option" tabindex="-1">
                                    <span class="slds-swatch" style="background:#5ebbff">
                                        <span class="slds-assistive-text">#5ebbff</span>
                                    </span>
                                </a>
                            </li>
                            <li class="slds-color-picker__swatch" role="presentation">
                                <a class="slds-color-picker__swatch-trigger" href="#" role="option" tabindex="-1">
                                    <span class="slds-swatch" style="background:#00aea9">
                                        <span class="slds-assistive-text">#00aea9</span>
                                    </span>
                                </a>
                            </li>
                            <li class="slds-color-picker__swatch" role="presentation">
                                <a class="slds-color-picker__swatch-trigger" href="#" role="option" tabindex="-1">
                                    <span class="slds-swatch" style="background:#3cba4c">
                                        <span class="slds-assistive-text">#3cba4c</span>
                                    </span>
                                </a>
                            </li>
                            <li class="slds-color-picker__swatch" role="presentation">
                                <a class="slds-color-picker__swatch-trigger" href="#" role="option" tabindex="-1">
                                    <span class="slds-swatch" style="background:#f5bc25">
                                        <span class="slds-assistive-text">#f5bc25</span>
                                    </span>
                                </a>
                            </li>
                            <li class="slds-color-picker__swatch" role="presentation">
                                <a class="slds-color-picker__swatch-trigger" href="#" role="option" tabindex="-1">
                                    <span class="slds-swatch" style="background:#f99221">
                                        <span class="slds-assistive-text">#f99221</span>
                                    </span>
                                </a>
                            </li>
                            <li class="slds-color-picker__swatch" role="presentation">
                                <a class="slds-color-picker__swatch-trigger" href="#" role="option" tabindex="-1">
                                    <span class="slds-swatch" style="background:#580d8c">
                                        <span class="slds-assistive-text">#580d8c</span>
                                    </span>
                                </a>
                            </li>
                            <li class="slds-color-picker__swatch" role="presentation">
                                <a class="slds-color-picker__swatch-trigger" href="#" role="option" tabindex="-1">
                                    <span class="slds-swatch" style="background:#001970">
                                        <span class="slds-assistive-text">#001970</span>
                                    </span>
                                </a>
                            </li>
                            <li class="slds-color-picker__swatch" role="presentation">
                                <a class="slds-color-picker__swatch-trigger" href="#" role="option" tabindex="-1">
                                    <span class="slds-swatch" style="background:#0a2399">
                                        <span class="slds-assistive-text">#0a2399</span>
                                    </span>
                                </a>
                            </li>
                            <li class="slds-color-picker__swatch" role="presentation">
                                <a class="slds-color-picker__swatch-trigger" href="#" role="option" tabindex="-1">
                                    <span class="slds-swatch" style="background:#0b7477">
                                        <span class="slds-assistive-text">#0b7477</span>
                                    </span>
                                </a>
                            </li>
                            <li class="slds-color-picker__swatch" role="presentation">
                                <a class="slds-color-picker__swatch-trigger" href="#" role="option" tabindex="-1">
                                    <span class="slds-swatch" style="background:#0b6b50">
                                        <span class="slds-assistive-text">#0b6b50</span>
                                    </span>
                                </a>
                            </li>
                            <li class="slds-color-picker__swatch" role="presentation">
                                <a class="slds-color-picker__swatch-trigger" href="#" role="option" tabindex="-1">
                                    <span class="slds-swatch" style="background:#b67e11">
                                        <span class="slds-assistive-text">#b67e11</span>
                                    </span>
                                </a>
                            </li>
                            <li class="slds-color-picker__swatch" role="presentation">
                                <a class="slds-color-picker__swatch-trigger" href="#" role="option" tabindex="-1">
                                    <span class="slds-swatch" style="background:#b85d0d">
                                        <span class="slds-assistive-text">#b85d0d</span>
                                    </span>
                                </a>
                            </li>
                        </ul>
                    </div>
                    <div id="color-picker-custom" class="slds-tabs_default__content slds-hide" role="tabpanel" aria-labelledby="color-picker-custom__item">
                        <div class="slds-color-picker__custom">
                            <p id="color-picker-instructions" class="slds-assistive-text">
                                Use arrow keys to select a saturation and brightness, on an x and y axis.
                            </p>
                            <div class="slds-color-picker__custom-range" style="background:hsl(220, 100%, 50%)">
                                <a
                                    class="slds-color-picker__range-indicator"
                                    style="bottom:45%;left:46%"
                                    href="#"
                                    aria-live="assertive"
                                    aria-atomic="true"
                                    aria-describedby="color-picker-instructions">
                                    <span class="slds-assistive-text">Saturation: 46%. Brightness: 45%.</span>
                                </a>
                            </div>
                            <div class="slds-color-picker__hue-and-preview">
                                <label class="slds-assistive-text" for="color-picker-input-range-3">
                                    Select Hue
                                </label>
                                <input
                                    id="color-picker-input-range-3"
                                    type="range"
                                    class="slds-color-picker__hue-slider"
                                    min="0"
                                    max="360"
                                    value="208">
                                <span class="slds-swatch" style="background:#5679C0">
                                    <span class="slds-assistive-text" aria-hidden="true">#5679C0</span>
                                </span>
                            </div>
                            <div class="slds-color-picker__custom-inputs">
                                <div class="slds-form-element slds-color-picker__input-custom-hex">
                                    <label class="slds-form-element__label" for="color-picker-input-hex-3">
                                        Hex
                                    </label>
                                    <div class="slds-form-element__control">
                                        <input id="color-picker-input-hex-3" type="text" class="slds-input" value="#5679C0">
                                    </div>
                                </div>
                                <div class="slds-form-element">
                                    <label class="slds-form-element__label" for="color-picker-input-r-3">
                                        <abbr title="Red">R</abbr>
                                    </label>
                                    <div class="slds-form-element__control">
                                        <input id="color-picker-input-r-3" type="text" class="slds-input" value="86">
                                    </div>
                                </div>
                                <div class="slds-form-element">
                                    <label class="slds-form-element__label" for="color-picker-input-g-3">
                                        <abbr title="Green">G</abbr>
                                    </label>
                                    <div class="slds-form-element__control">
                                        <input id="color-picker-input-g-3" type="text" class="slds-input" value="121">
                                    </div>
                                </div>
                                <div class="slds-form-element">
                                    <label class="slds-form-element__label" for="color-picker-input-b-3">
                                        <abbr title="blue">B</abbr>
                                    </label>
                                    <div class="slds-form-element__control">
                                        <input id="color-picker-input-b-3" type="text" class="slds-input" value="192">
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <footer class="slds-popover__footer">
                <div class="slds-color-picker__selector-footer">
                    <button class="slds-button slds-button_neutral">
                        Cancel
                    </button>
                    <button class="slds-button slds-button_brand">
                        Done
                    </button>
                </div>
            </footer>
        </section>
    </div>
</template>

<script>
export default {
    name: "SldsColorPicker"
}
</script>

<style scoped>

</style>
