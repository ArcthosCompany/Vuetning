<template>
    <div class="slds-builder-header_container">
        <header class="slds-builder-header">
            <div class="slds-builder-header__item">
                <div class="slds-builder-header__item-label slds-media slds-media_center">
                    <div class="slds-media__figure">
                        <span class="slds-icon_container slds-icon-utility-builder slds-current-color">
                            <svg class="slds-icon slds-icon_x-small" aria-hidden="true">
                                <use xlink:href="/assets/icons/utility-sprite/svg/symbols.svg#builder"/>
                            </svg>
                        </span>
                    </div>
                    <div class="slds-media__body">
                        App Name
                    </div>
                </div>
            </div>
            <nav class="slds-builder-header__item slds-builder-header__nav">
                <ul class="slds-builder-header__nav-list">
                    <li class="slds-builder-header__nav-item">
                        <a href="javascript:void(0);" class="slds-builder-header__item-action slds-media slds-media_center">
                            <span class="slds-media__figure">
                                <span class="slds-icon_container slds-icon-utility-settings slds-current-color">
                                    <svg class="slds-icon slds-icon_x-small" aria-hidden="true">
                                        <use xlink:href="/assets/icons/utility-sprite/svg/symbols.svg#settings"/>
                                    </svg>
                                </span>
                            </span>
                            <span class="slds-media__body">
                                <span class="slds-truncate" title="Link">Link</span>
                            </span>
                        </a>
                    </li>
                    <li class="slds-builder-header__nav-item">
                        <button class="slds-button slds-builder-header__item-action slds-media slds-media_center" aria-haspopup="true" title="Click to open menu">
                            <span class="slds-media__figure">
                                <span class="slds-icon_container slds-icon-utility-page slds-current-color">
                                    <svg class="slds-icon slds-icon_x-small" aria-hidden="true">
                                        <use xlink:href="/assets/icons/utility-sprite/svg/symbols.svg#page"/>
                                    </svg>
                                </span>
                            </span>
                            <span class="slds-media__body">
                                <span class="slds-truncate" title="Dropdown">Dropdown</span>
                                <span class="slds-icon_container slds-icon-utility-chevrondown slds-current-color slds-m-left_small">
                                    <svg class="slds-icon slds-icon_x-small" aria-hidden="true">
                                        <use xlink:href="/assets/icons/utility-sprite/svg/symbols.svg#chevrondown"/>
                                    </svg>
                                </span>
                            </span>
                        </button>
                    </li>
                </ul>
            </nav>
            <div class="slds-builder-header__item slds-has-flexi-truncate">
                <h1 class="slds-builder-header__item-label">
                    <span class="slds-truncate" title="Page Type">Page Type</span>
                </h1>
            </div>
            <div class="slds-builder-header__item slds-builder-header__utilities">
                <div class="slds-builder-header__utilities-item">
                    <a href="javascript:void(0);" class="slds-builder-header__item-action slds-media slds-media_center">
                        <div class="slds-media__figure">
                            <span class="slds-icon_container slds-icon-utility-back slds-current-color">
                                <svg class="slds-icon slds-icon_x-small" aria-hidden="true">
                                    <use xlink:href="/assets/icons/utility-sprite/svg/symbols.svg#back"/>
                                </svg>
                            </span>
                        </div>
                        <div class="slds-media__body">
                            Back
                        </div>
                    </a>
                </div>
                <div class="slds-builder-header__utilities-item">
                    <a href="javascript:void(0);" class="slds-builder-header__item-action slds-media slds-media_center">
                        <div class="slds-media__figure">
                            <span class="slds-icon_container slds-icon-utility-help slds-current-color">
                                <svg class="slds-icon slds-icon_x-small" aria-hidden="true">
                                    <use xlink:href="/assets/icons/utility-sprite/svg/symbols.svg#help"/>
                                </svg>
                            </span>
                        </div>
                        <div class="slds-media__body">
                            Help
                        </div>
                    </a>
                </div>
            </div>
        </header>
    </div>
</template>

<script>
export default {
    name: "SldsBuilderHeader"
}
</script>

<style scoped>

</style>
