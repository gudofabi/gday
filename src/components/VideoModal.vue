<template>
    <transition name="fade">
        <div class="malouf-modal-container bg-light-grey" v-show="showModal">
            <div class="malouf-modal">
                <div class="modal-body">
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close" @click="func_close">
                        <span aria-hidden="true">&times;</span>
                    </button>        
                    <!-- 16:9 aspect ratio -->
                    <div class="embed-responsive embed-responsive-16by9">
                        <iframe class="embed-responsive-item" :src="videoSource" id="video"  allowscriptaccess="always"></iframe>
                    </div>
                </div>
            </div>
        </div>
    </transition>
</template>

<script>
export default {
    name: 'VideoModal',
    props: {
        videoSource: {
            type: String,
            default: 'none'
        },
        showModal: {
            type: Boolean,
            default: false
        }
    },
    methods: {
        func_close() {
            this.$emit('close', false);
        }
    }
}
</script>

<style lang="scss" scoped>
.fade-enter-active, .fade-leave-active {
  transition: opacity .5s;
}
.fade-enter, .fade-leave-to /* .fade-leave-active below version 2.1.8 */ {
  opacity: 0;
}
</style>