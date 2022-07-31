/*
 * Copyright (c) 2020 The ZMK Contributors
 *
 * SPDX-License-Identifier: MIT
 */

#include <behaviors.dtsi>
#include <dt-bindings/zmk/keys.h>

/ {
	keymap {
		compatible = "zmk,keymap";

		default_layer {
				// -----------------------------------------------------------------------------------------
				// |  TAB  |  Q   |  W   |  E   |  R   |  T   |   Y   |  U    |  I   |  O   |   P   | BSPC  |
				// |  ESC  |  A   |  S   |  D   |  F   |  G   |   H   |  J    |  K   |  L   |   ;   |  '    |
				// | SHIFT |  Z   |  X   |  C   |  V   |  B   |   N   |  M    |  ,   |  .   |   /   |  RET  |
				// | RSHIFT| LCTL | LGUI | LALT | LOWR |     SPACE    |  RAIS | LARW | DARW | UARW  |  RARW |

           bindings = <
               &kp Q &kp W &kp E &kp R &kp T &trans                       &trans &kp Z &kp U &kp I &kp O &kp P 
               &kp A &lt 5 S &lt 1 D &lt 3 F &kp G &trans                 &trans &kp H &lt 4 J &lt 2 K &lt 6 L &kp DOT 
               &kp Y &kp X &mt LEFT_ALT C &kp V &kp B &trans              &trans &kp N &kp M &mt LEFT_ALT KC_NO &kp F20 &lt 7 KC_NO
               &trans &trans &trans &kp SPACE &kp LEFT_SHIFT &trans       &kp RIGHT_CONTROL &kp LEFT_GUI &trans &trans &trans
           >;

			sensor-bindings = <&inc_dec_kp PG_UP PG_DN>;
		};

		lower {
        
            bindings = <
                &trans &trans &trans &trans &kp P &trans         &trans &trans KC_BTN1 KC_WH_U KC_BTN2 &trans &trans KC_BTN2 &trans KC_BTN1 &trans 
                &trans &trans &trans KC_MS_L KC_MS_D KC_MS_U KC_MS_R &trans &trans &trans          &trans &trans &trans &trans &trans KC_WH_L KC_WH_D KC_WH_R 
                &trans &trans &trans &trans &trans &trans           &trans &trans &trans &trans &trans &trans
            >;

			sensor-bindings = <&inc_dec_kp C_VOL_UP C_VOL_DN>;
		};


		raise {
            bindings = <
                &trans &trans &trans &trans &kp P &trans       &trans &trans KC_BTN1 KC_WH_U KC_BTN2 &trans &trans KC_BTN2 &trans KC_BTN1 &trans 
                &trans &trans &trans KC_MS_L KC_MS_D KC_MS_U KC_MS_R &trans &trans &trans       &trans &trans &trans &trans &trans KC_WH_L KC_WH_D KC_WH_R &trans 
                &trans &trans &trans &trans &trans &trans       &trans &trans &trans &trans &trans
          >;

		};
layer2 {
           bindings = <
               &trans &trans &kp PAGE_UP &trans &kp P &trans &trans &trans &kp C &kp R &kp L &kp BACKSPACE &kp LEFT &kp UP &kp DOWN &kp RIGHT &kp U &trans &trans &kp H &kp LEFT_GUI &kp N LCTL(KC_LALT) LCA(KC_LSFT) &trans &kp HOME &kp PAGE_DOWN &kp END &kp K &trans &trans &trans &trans &trans &trans &trans &trans &trans &trans &trans &kp DELETE &trans &kp SPACE &trans &trans &trans &trans
        >;
      };
layer2 {
           bindings = <
               &trans &trans &kp PAGE_UP &trans &kp P &trans &trans &trans &kp C &kp R &kp L &kp BACKSPACE &kp LEFT &kp UP &kp DOWN &kp RIGHT &kp U &trans &trans &kp H &kp LEFT_GUI &kp N LCTL(KC_LALT) LCA(KC_LSFT) &trans &kp HOME &kp PAGE_DOWN &kp END &kp K &trans &trans &trans &trans &trans &trans &trans &trans &trans &trans &trans &kp DELETE &trans &kp SPACE &trans &trans &trans &trans
        >;
      };
layer2 {
        bindings = <
        &trans &trans &kp PAGE_UP &trans &kp P &trans &trans &trans &kp C &kp R &kp L &kp BACKSPACE &kp LEFT &kp UP &kp DOWN &kp RIGHT &kp U &trans &trans &kp H &kp LEFT_GUI &kp N LCTL(KC_LALT) LCA(KC_LSFT) &trans &kp HOME &kp PAGE_DOWN &kp END &kp K &trans &trans &trans &trans &trans &trans &trans &trans &trans &trans &trans &kp DELETE &trans &kp SPACE &trans &trans &trans &trans
        >;
      }

	};
};

