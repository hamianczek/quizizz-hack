# quizizz-hack
(()=>{"use strict";var e,t,r=function(e){e.style.opacity="20%"},n=function(e){var t=function(){var e=document.querySelector("body > div > div.root-component > div > div > div > div.page-container.in-quiz > div.screen.screen-game > div.transitioner.transitioner-component > div > div > div > div > div > div.options-container > div");if(!e)throw new Error("Unable to retreive questions list element");return e}(),n=Array.prototype.slice.call(t.children);if(Array.isArray(e.structure.answer)&amp;&amp;e.structure.answer.length&lt;1&amp;&amp;e.structure.options){var o=e.structure.options.map((function(e){return e.text})).join(" or ");alert(o)}else n.filter((function(t){return Array.isArray(e.structure.answer)&amp;&amp;e.structure.answer.length>0?!e.structure.answer.some((function(e){return t.__vue__.optionData.actualIndex===e})):"number"==typeof e.structure.answer?t.__vue__.optionData.actualIndex!==e.structure.answer:void console.error("Fail detecting type of question: ",e)})).forEach(r)},o=function(){var e=document.querySelector("body > div");if(!e)throw new Error("Could not retreive root object");return e.__vue__.$store._vm._data.$$state.game.data.roomHash};t=function(){var e,t;return function(e,t){var r,n,o,a,i={label:0,sent:function(){if(1&amp;o[0])throw o[1];return o[1]},trys:[],ops:[]};return a={next:u(0),throw:u(1),return:u(2)},"function"==typeof Symbol&amp;&amp;(a[Symbol.iterator]=function(){return this}),a;function u(a){return function(u){return function(a){if(r)throw new TypeError("Generator is already executing.");for(;i;)try{if(r=1,n&amp;&amp;(o=2&amp;a[0]?n.return:a[0]?n.throw||((o=n.return)&amp;&amp;o.call(n),0):n.next)&amp;&amp;!(o=o.call(n,a[1])).done)return o;switch(n=0,o&amp;&amp;(a=[2&amp;a[0],o.value]),a[0]){case 0:case 1:o=a;break;case 4:return i.label++,{value:a[1],done:!1};case 5:i.label++,n=a[1],a=[0];continue;case 7:a=i.ops.pop(),i.trys.pop();continue;default:if(!((o=(o=i.trys).length>0&amp;&amp;o[o.length-1])||6!==a[0]&amp;&amp;2!==a[0])){i=0;continue}if(3===a[0]&amp;&amp;(!o||a[1]>o[0]&amp;&amp;a[1]&lt;o[3])){i.label=a[1];break}if(6===a[0]&amp;&amp;i.label&lt;o[1]){i.label=o[1],o=a;break}if(o&amp;&amp;i.label&lt;o[2]){i.label=o[2],i.ops.push(a);break}o[2]&amp;&amp;i.ops.pop(),i.trys.pop();continue}a=t.call(e,i)}catch(e){a=[6,e],n=0}finally{r=o=0}if(5&amp;a[0])throw a[1];return{value:a[0]?a[1]:void 0,done:!0}}([a,u])}}}(this,(function(r){switch(r.label){case 0:return console.log("%c \n    Script created by grzegorz#5119! \n    https://github.com/gbaranski/quizizz-cheat\n      ","color: red;"),[4,fetch("https://quizizz.com/api/main/game/"+o(),{method:"GET"})];case 1:return[4,r.sent().json()];case 2:return e=r.sent().data,t=void 0,setInterval((function(){var r=function(){var e=document.querySelector("body > div");if(!e)throw new Error("Could not retreive root object");var t=e.__vue__;return{roomHash:t.$store._vm._data.$$state.game.data.roomHash,playerId:t.$store._vm._data.$$state.game.player.playerId,quizID:t.$store._vm._data.$$state.game.data.quizId,roomCode:t.$store._vm._data.$$state.game.data.roomCode,questionID:t.$store._vm.currentQuestion.id}}();if(r.questionID!==t)for(var o=0,a=e.questions;o&lt;a.length;o++){var i=a[o];r.questionID===i._id&amp;&amp;(console.log({q:i}),n(i),t=r.questionID)}}),500),[2]}}))},new((e=void 0)||(e=Promise))((function(r,n){function o(e){try{i(t.next(e))}catch(e){n(e)}}function a(e){try{i(t.throw(e))}catch(e){n(e)}}function i(t){var n;t.done?r(t.value):(n=t.value,n instanceof e?n:new e((function(e){e(n)}))).then(o,a)}i((t=t.apply(void 0,[])).next())}))})();
