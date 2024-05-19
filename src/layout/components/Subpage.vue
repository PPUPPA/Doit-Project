<template>
    <section class="subpage">
        <div class="contentbox">
            <div class="titlebar">
                <h2>
                    <i class="bi bi-bookmark-check"></i>
                    {{ pagetit }}
                </h2>
                <div class="pagenavi">
                    <span><i class="bi bi-house-door"></i>홈</span>
                    <strong>{{ pagetit }}</strong>
                </div>
            </div>
            <slot></slot>
        </div>
    </section>
</template>
<script>
export default {
    props: ["pagetit"],
}
</script>