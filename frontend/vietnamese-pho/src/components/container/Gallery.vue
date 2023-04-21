<template>
    <div>
        <div
            class="grid grid-cols-2 p-[15rem] animate__animated animate__bounceInLeft pt-[24rem]"
        >
            <div class="flex">
                <div class="flex flex-col items-center px-10">
                    <p class="text-3xl text-white font-bold bg-black p-16">
                        Đây là website bán phở Việt, nơi mà bạn có thể tìm thấy những món phở ngon nhất của Việt Nam. Chúng tôi tự hào mang đến cho bạn những trải nghiệm tuyệt vời về ẩm thực Việt Nam.
                    </p>
                </div>
            </div>
            <div
                class="border-8 w-96 h-96 transform rotate-12 relative -left-[20rem] -top-[21rem]"
            >
                <img
                    src="../../assets/images/VNY-1-800x800.jpg"
                    alt=""
                    class="object-cover"
                />
            </div>
        </div>
        <div
            class="grid grid-cols-2 px-[15rem] animate__animated animate__bounceInLeft pt-[5rem]"
        >
            <div>
                <div
                    class="border-8 w-96 h-96 transform rotate-6 relative -right-[52rem] -top-[21rem]"
                >
                    <img
                        src="../../assets/images/2-800x614.jpg"
                        alt=""
                        class="object-cover h-full"
                    />
                </div>
                <div
                    class="border-8 w-96 h-96 transform rotate-12 relative -right-[90rem] -top-[12rem]"
                >
                    <img
                        src="../../assets/images/3-700x800.jpg"
                        alt=""
                        class="object-cover h-full w-full"
                    />
                </div>
            </div>
            <div class="flex">
                <div class="flex flex-col items-center px-10">
                    <p class="text-3xl text-white font-bold bg-black p-16">
                        Chúng tôi đã chọn lựa các nguyên liệu tươi ngon nhất để tạo ra món phở thơm ngon đậm đà, đúng với hương vị truyền thống của Việt Nam. Bên cạnh đó, chúng tôi cũng đảm bảo món ăn của bạn được phục vụ nhanh chóng và đúng hạn.
                    </p>
                </div>
            </div>
        </div>
        <div
            class="grid grid-cols-2 p-[15rem] animate__animated animate__bounceInLeft pt-[5rem]"
        >
            <div class="flex">
                <div class="flex flex-col items-center px-10">
                    <p class="text-3xl text-white font-bold bg-black p-16">
                        Với mong muốn đem đến cho khách hàng những trải nghiệm ẩm thực tuyệt vời nhất, chúng tôi luôn sẵn sàng lắng nghe và đáp ứng mọi nhu cầu của bạn.
                    </p>
                </div>
            </div>
            <div>
                <div
                    class="border-8 w-96 h-96 transform rotate-12 relative -left-[20rem] -top-[21rem]"
                >
                    <img
                        src="../../assets/images/4.jpg"
                        alt=""
                        class="object-cover h-full"
                    />
                </div>
                <div
                    class="border-8 w-96 h-96 transform rotate-6 relative -left-[60rem] -top-[10rem]"
                >
                    <img
                        src="../../assets/images/202112_Pho_JanHot_Z6II_0231_SML-800x800.jpg"
                        alt=""
                        class="object-cover h-full"
                    />
                </div>
            </div>
        </div>

        <Cart />
    </div>
</template>

<script>
import Cart from "../Cart.vue";
export default {
    name: "Our Story",
    components: {
        Cart,
    },
};
</script>

<style>
.about {
    font-size: 5rem;
    font-weight: bold;
}
</style>
