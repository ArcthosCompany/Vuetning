<template>
    <li class="slds-global-actions__item">
        <div class="slds-dropdown-trigger slds-dropdown-trigger_click">
            <button
                class="slds-button slds-button_icon slds-button_icon slds-button_icon-container slds-button_icon-small slds-global-actions__notifications slds-global-actions__item-action"
                title="no new notifications"
                aria-live="assertive"
                aria-atomic="true"
            >
                <!-- SVG -->
                <slds-svg
                    icon="utility:notification"
                    class="slds-button__icon slds-global-header__icon"
                />

                <!-- Assistive text -->
                <span class="slds-assistive-text">
                    No new notifications
                </span>

            </button>

            <!-- Badge -->
            <span aria-hidden="true" class="slds-notification-badge">
                0
            </span>

        </div>
    </li>
</template>


<script>
import SldsSvg from '@/components/slds-svg/svg'

export default {
    name: 'SldsGlobalActionNotifications',

    components: {
        SldsSvg
    }
}
</script>
