<!DOCTYPE html>
<html lang="en" class="scroll-smooth"><head><script data-bard-client-injected="true">(function(firebaseConfig, initialAuthToken, appId) {
        window.__firebase_config = firebaseConfig;
        window.__initial_auth_token = initialAuthToken;
        window.__app_id = appId;
            })("\n{\n  \"apiKey\": \"AIzaSyCqyCcs2R2e7AegGjvFAwG98wlamtbHvZY\",\n  \"authDomain\": \"bard-frontend.firebaseapp.com\",\n  \"projectId\": \"bard-frontend\",\n  \"storageBucket\": \"bard-frontend.firebasestorage.app\",\n  \"messagingSenderId\": \"175205271074\",\n  \"appId\": \"1:175205271074:web:2b7bd4d34d33bf38e6ec7b\"\n}\n","eyJhbGciOiJSUzI1NiIsImtpZCI6IjExNjRiNzdiNDMzZDdhMDAyMWI4NjE4YjhjYTU3ZTMyZGI5MWUxMTMiLCJ0eXAiOiJKV1QifQ.eyJzdWIiOiJmaXJlYmFzZS1hZG1pbnNkay1mYnN2Y0BiYXJkLWZyb250ZW5kLmlhbS5nc2VydmljZWFjY291bnQuY29tIiwiYXVkIjoiaHR0cHM6Ly9pZGVudGl0eXRvb2xraXQuZ29vZ2xlYXBpcy5jb20vZ29vZ2xlLmlkZW50aXR5LmlkZW50aXR5dG9vbGtpdC52MS5JZGVudGl0eVRvb2xraXQiLCJ1aWQiOiIxNzg1NDA0NzIyMDY3NTI1MDIwMCIsImlzcyI6ImZpcmViYXNlLWFkbWluc2RrLWZic3ZjQGJhcmQtZnJvbnRlbmQuaWFtLmdzZXJ2aWNlYWNjb3VudC5jb20iLCJjbGFpbXMiOnsiYXBwSWQiOiJjXzY1NzA1Y2NiZjNhZjk1NjVfaW5kZXguaHRtbC01NzQifSwiZXhwIjoxNzkwOTU3MTA4LCJpYXQiOjE3OTA5NTM1MDgsImFsZyI6IlJTMjU2In0.bSjHy-CjXlAJ-hCpmTmPSJFP_di36_TxkS1LQ6KI16gkGTPap9uuk-j55Vs_DWHlzUcyCDCso0infBabOOp6rBsohnS8jK_KqlJJuztW14bteFDGY4hi3BGBPoyeZ_sF3tPjzK16MLRdL5_UdR77PKn1E2M9bf7sDfAiRpwiBRp9MhxP6PEi_WDsXxdCuXjDyozozmWUOJ2R6Ixwu_IsBUGoL9K1_W2kXh-zkJnJxPxAUBoQigR972WWw-KEt4b_sIS33N6TivZD3ALa6a0Kxg_RCR86XwtRL2ue_71aEeTkAxIlDDGsOD34J4mZC_putyBEZFKOzVrbdzoSEd1X5A","c_65705ccbf3af9565_index.html-574")</script><script data-bard-client-injected="true">
  document.addEventListener('input', (event) => {
    if (event.target && (event.target.isContentEditable || event.target.hasAttribute('contenteditable'))) {
      const clonedDoc = document.cloneNode(true);
      const injectedScripts = clonedDoc.querySelectorAll('[data-bard-client-injected="true"]');
      injectedScripts.forEach(el => el.remove());
      window.parent.postMessage({
        type: 'inlineEdit',
        html: '<!DOCTYPE html>\n' + clonedDoc.documentElement.outerHTML
      }, '*');
    }
  });
</script><script data-bard-client-injected="true">(function(){'use strict';window.addEventListener("message",a=>{a.data&&a.data.type==="SUPPLEMENTAL_DATA_UPDATE"&&window.dispatchEvent(new CustomEvent("supplementaldataupdate",{detail:a.data.data}))});}).call(this);
</script><script data-bard-client-injected="true">(function() {
  const SCROLL_KEYS = new Set([
    'ArrowUp', 'ArrowDown', 'ArrowLeft', 'ArrowRight',
    ' ', 'Spacebar', 'PageUp', 'PageDown', 'Home', 'End',
  ]);
  const HORIZONTAL_KEYS = new Set(['ArrowLeft', 'ArrowRight']);

  function isTextEntryTarget(target) {
    if (!target) return false;
    const tagName = target.tagName;
    return tagName === 'INPUT' || tagName === 'TEXTAREA' ||
        tagName === 'SELECT' || target.isContentEditable === true;
  }

  // An element absorbs the key only if it both overflows on the axis being
  // scrolled and is configured to scroll on that axis. The cheap dimension
  // test runs first because getComputedStyle forces a style recalc, and this
  // runs on every keypress. Each axis is read from its own longhand: the
  // 'overflow' shorthand serializes as two values when the axes differ, which
  // is the common 'overflow-x: hidden; overflow-y: auto' pane.
  function canScroll(node, horizontal) {
    const overflows = horizontal ? node.scrollWidth > node.clientWidth
                                 : node.scrollHeight > node.clientHeight;
    if (!overflows) return false;
    const style = window.getComputedStyle(node);
    const overflow = horizontal ? style.overflowX : style.overflowY;
    return overflow === 'auto' || overflow === 'scroll';
  }

  // Walks up from the event target so nested scrollers keep their behavior.
  // <body> is included because pages that pin the root height make it the
  // scroll container.
  function hasScrollableAncestor(target, horizontal) {
    let node = target;
    while (node && node !== document.documentElement) {
      if (canScroll(node, horizontal)) return true;
      node = node.parentElement;
    }
    return false;
  }

  function rootCanScroll(horizontal) {
    const scroller = document.scrollingElement || document.documentElement;
    if (!scroller) return false;
    // Tolerate a pixel of rounding so subpixel layouts do not look scrollable.
    return horizontal ? scroller.scrollWidth > window.innerWidth + 1
                      : scroller.scrollHeight > window.innerHeight + 1;
  }

  window.addEventListener('keydown', function(event) {
    if (!SCROLL_KEYS.has(event.key)) return;
    if (event.defaultPrevented) return;
    // Alt and Meta turn arrows into browser history navigation, and Ctrl is
    // reserved for shortcuts, so none of them are scroll intent.
    if (event.altKey || event.metaKey || event.ctrlKey) return;

    const target = event.target;
    if (isTextEntryTarget(target)) return;

    // Anything that can still absorb the scroll gets to keep it.
    const horizontal = HORIZONTAL_KEYS.has(event.key);
    if (rootCanScroll(horizontal)) return;
    if (hasScrollableAncestor(target, horizontal)) return;

    event.preventDefault();
  }, {capture: true, passive: false});
})();</script><script data-bard-client-injected="true">(function() {
  // Ensure this script is executed only once
  if (window.firebaseAuthBridgeScriptLoaded) {
    return;
  }
  window.firebaseAuthBridgeScriptLoaded = true;

  let nextTokenPromiseId = 0;

  // Stores { resolve, reject } for ongoing token requests
  const pendingTokenPromises = {};

  // Listen for messages from the Host Application
  window.addEventListener('message', function(event) {

    const messageData = event.data;

  if (messageData && messageData.type === 'RESOLVE_NEW_FIREBASE_TOKEN') {
      const { success, token, error, promiseId } = messageData ?? {};
      if (pendingTokenPromises[promiseId]) {
        if (success) {
          pendingTokenPromises[promiseId].resolve(token);
        } else {
          pendingTokenPromises[promiseId].reject(new Error(error || 'Token refresh failed from host.'));
        }
        delete pendingTokenPromises[promiseId];
      }
    }
  });

  // Expose a function for the Generated App to request a new Firebase token
  window.requestNewFirebaseToken = function() {
    const currentPromiseId = nextTokenPromiseId++;
    const promise = new Promise((resolve, reject) => {
      pendingTokenPromises[currentPromiseId] = { resolve, reject };
    });
    if (window.parent && window.parent !== window) {
      window.parent.postMessage({
        type: 'REQUEST_NEW_FIREBASE_TOKEN',
        promiseId: currentPromiseId
      }, '*');
    } else {
      pendingTokenPromises[currentPromiseId].reject(new Error('No parent window to request token from.'));
      delete pendingTokenPromises[currentPromiseId];
    }
    return promise;
  };
})();</script><script data-bard-client-injected="true">
let realOriginalGetUserMedia = null;
if (navigator.mediaDevices && navigator.mediaDevices.getUserMedia) {
  realOriginalGetUserMedia = navigator.mediaDevices.getUserMedia.bind(navigator.mediaDevices);
}

(function() {
  if (navigator.mediaDevices && navigator.mediaDevices.__proto__) {
    try {
      Object.defineProperty(navigator.mediaDevices.__proto__, 'getUserMedia', {
        get: function() {
          return undefined; // Or throw an error
        },
        configurable: false
      });
    } catch (error) {
      console.error("Error defining prototype getter:", error);
    }
  }
})();

(function() {
  const pendingMediaResolvers = {};
  let nextMediaPromiseId = 0;

  function requestMediaPermissions(constraints) {
    const mediaPromiseId = nextMediaPromiseId++;
    const promise = new Promise((resolve, reject) => {
      pendingMediaResolvers[mediaPromiseId] = (granted) => {
        delete pendingMediaResolvers[mediaPromiseId];
        resolve(granted);
      };
    });

    window.parent.postMessage({
      type: 'requestMediaPermission',
      constraints: constraints,
      promiseId: mediaPromiseId,
    }, '*');

    return promise;
  }

  let originalGetUserMedia = realOriginalGetUserMedia;

  function interceptGetUserMedia() {
    if (navigator.mediaDevices) {
      Object.defineProperty(navigator.mediaDevices, 'getUserMedia', {
        value: function(constraints) {
          return requestMediaPermissions(constraints).then((granted) => {
            if (granted) {
              if (originalGetUserMedia) {
                return originalGetUserMedia(constraints);
              } else {
                throw new Error("Original getUserMedia not available.");
              }
            } else {
              throw new DOMException('Permission denied', 'NotAllowedError');
            }
          });
        },
        writable: false,
        configurable: false
      });
    }
  }

  interceptGetUserMedia();

  const observer = new MutationObserver(function(mutationsList, observer) {
    for (const mutation of mutationsList) {
      if (mutation.type === 'reconfigured' && mutation.name === 'getUserMedia' && mutation.object === navigator.mediaDevices) {
        interceptGetUserMedia();
      } else if (mutation.type === 'attributes' && mutation.attributeName === 'getUserMedia' && mutation.target === navigator.mediaDevices) {
        interceptGetUserMedia();
      } else if (mutation.type === 'childList' && mutation.addedNodes) {
        mutation.addedNodes.forEach(node => {
          if (node === navigator.mediaDevices) {
            interceptGetUserMedia();
          }
        });
      }
    }
  });

  function interceptSpeechRecognition() {
    if (!window.SpeechRecognition && !window.webkitSpeechRecognition) {
      return;
    }

    const OriginalSpeechRecognition = window.SpeechRecognition || window.webkitSpeechRecognition;

    const SpeechRecognitionWrapper = function(...args) {
      const recognizer = new OriginalSpeechRecognition(...args);
      const originalStart = recognizer.start.bind(recognizer);

      recognizer.start = function() {
        requestMediaPermissions({ audio: true }).then(granted => {
          if (granted) {
            originalStart();
          } else {
            const errorEvent = new SpeechRecognitionErrorEvent('error');
            errorEvent.error = 'not-allowed'; // This is the standard error for permission denial.
            recognizer.dispatchEvent(errorEvent);
          }
        });
      };

      return recognizer;
    };

    SpeechRecognitionWrapper.prototype = OriginalSpeechRecognition.prototype;
    SpeechRecognitionWrapper.prototype.constructor = SpeechRecognitionWrapper;

    if (window.SpeechRecognition) {
      window.SpeechRecognition = SpeechRecognitionWrapper;
    }
    if (window.webkitSpeechRecognition) {
      window.webkitSpeechRecognition = SpeechRecognitionWrapper;
    }
  }

  interceptSpeechRecognition();

  window.addEventListener('message', function(event) {
    if (event.data) {
      if (event.data.type === 'resolveMediaPermission') {
        const { promiseId, granted } = event.data;
        if (pendingMediaResolvers[promiseId]) {
          pendingMediaResolvers[promiseId](granted);
        }
      }
    }
  });

})();</script><script ws-interception-config="{&quot;parentOrigin&quot;:&quot;https://gemini.google.com&quot;,&quot;proxiedDomains&quot;:[]}" data-bard-client-injected="true">(function(){'use strict';var u=typeof Object.defineProperties=="function"?Object.defineProperty:function(b,d,e){if(b==Array.prototype||b==Object.prototype)return b;b[d]=e.value;return b};function v(b){b=["object"==typeof globalThis&&globalThis,b,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var d=0;d<b.length;++d){var e=b[d];if(e&&e.Math==Math)return e}throw Error("Cannot find global object");}var w=v(this);
function y(b,d){if(d)a:{var e=w;b=b.split(".");for(var h=0;h<b.length-1;h++){var k=b[h];if(!(k in e))break a;e=e[k]}b=b[b.length-1];h=e[b];d=d(h);d!=h&&d!=null&&u(e,b,{configurable:!0,writable:!0,value:d})}}function z(b){function d(h){return b.next(h)}function e(h){return b.throw(h)}return new Promise(function(h,k){function m(n){n.done?h(n.value):Promise.resolve(n.value).then(d,e).then(m,k)}m(b.next())})}y("globalThis",function(b){return b||w});/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
function A(b,d){function e(){}e.prototype=d.prototype;b.j=d.prototype;b.prototype=new e;b.prototype.constructor=b;b.h=function(h,k,m){for(var n=Array(arguments.length-2),p=2;p<arguments.length;p++)n[p-2]=arguments[p];return d.prototype[k].apply(h,n)}};function B(b,d,e="*"){function h(a){if(typeof a==="string")return F.encode(a).buffer;if(a instanceof ArrayBuffer)return a.slice(0);if(ArrayBuffer.isView(a))return a.buffer.slice(a.byteOffset,a.byteOffset+a.byteLength);throw Error("Invalid data type");}function k(a){a=h(a);var f={type:"send",data:new Uint8Array(a)},g;(g=r)==null||g.postMessage(f,[a])}function m(){if(!r)throw Error("Data port not captured yet.");r.onmessage=a=>{if(a.data.type==="message"){a=new MessageEvent("message",{data:G.decode(a.data.data)});
let f;(f=c.onmessage)==null||f.call(c,a);c.dispatchEvent(a)}}}function n(){if(!t)throw Error("Control port not captured yet.");t.onmessage=a=>{switch(a.data.type){case "open":l=1;var f=new Event("open"),g;(g=c.onopen)==null||g.call(c,f);c.dispatchEvent(f);q.forEach(H=>{k(H)});q=[];break;case "close":g=a.data;l=3;g=new CloseEvent("close",{code:g.code,reason:g.reason,wasClean:g.wasClean});(f=c.onclose)==null||f.call(c,g);c.dispatchEvent(g);break;case "error":l=3;f=new Event("error");let x;(x=c.onerror)==
null||x.call(c,f);c.dispatchEvent(f)}}}function p(a){return z(function*(){var f=new MessageChannel;t=f.port1;var g=new MessageChannel;r=g.port1;n();m();window.parent.postMessage({type:"websocket_open",portOrdering:["control","data"],url:b,protocols:a||[],connectionId:I},e,[f.port2,g.port2])}())}var c=Reflect.construct(EventTarget,[],new.target);c.CONNECTING=0;c.OPEN=1;c.CLOSING=2;c.CLOSED=3;c.url=b;c.binaryType="arraybuffer";c.protocol="";c.i="";var l=0,t=null,r=null,q=[],F=new TextEncoder,G=new TextDecoder;
c.onopen=null;c.onmessage=null;c.onclose=null;c.onerror=null;Object.defineProperty(c,"readyState",{get:()=>l,enumerable:!0,configurable:!0});Object.defineProperty(c,"bufferedAmount",{get:()=>{var a=0;q.forEach(f=>{a+=typeof f==="string"?f.length:f.byteLength});return a},enumerable:!0,configurable:!0});var I=function(){var a;return((a=globalThis.crypto)==null?0:a.randomUUID)?globalThis.crypto.randomUUID():"xxxxxxxx-xxxx-4xxx-yxxx-xxxxxxxxxxxx".replace(/[xy]/g,f=>{var g=Math.random()*16|0;return(f===
"x"?g:g&3|8).toString(16)})}();c.send=a=>{if(l===1)a instanceof Blob?a.arrayBuffer().then(f=>{k(f)}):k(a);else if(l===0)if(typeof a==="string")q.push(a);else if(a instanceof ArrayBuffer||ArrayBuffer.isView(a))q.push(h(a));else throw Error("Sending Blob is not supported before the connection is open.");else console.debug("WebSocket send called in CLOSING or CLOSED state; ignored.")};c.close=(a=1E3,f="")=>{if(l!==2&&l!==3){l=2;a={type:"close",code:a,reason:f,wasClean:a===1E3};var g;(g=t)==null||g.postMessage(a)}};
Promise.resolve().then(()=>p(d));return c}A(B,EventTarget);var C=document.currentScript,D=C==null?void 0:C.getAttribute("ws-interception-config");if(!D)throw Error("WebSocket Interceptor: Missing ws-interception-config attribute in the script tag.");var E=JSON.parse(D);if(!E.parentOrigin||typeof E.parentOrigin!=="string")throw Error("WebSocket Interceptor: Invalid parentOrigin in ws-interception-config");
(function(b){var d=Object.getOwnPropertyDescriptor(window,"WebSocket");if(!d||d.writable||d.configurable)d=Object.assign(function(e,h){try{let k=(new URL(e)).hostname;if(b.proxiedDomains.some(m=>k===m||k.endsWith(`.${m}`)))return new B(e,h,b.parentOrigin)}catch(k){throw window.parent.postMessage({type:"websocket_blocked",url:e,reason:"blocked_invalid_url"},b.parentOrigin),new DOMException(`WebSocket connection to '${e}' is not allowed in Canvas.`,"SecurityError");}window.parent.postMessage({type:"websocket_blocked",
url:e,reason:"blocked_domain_not_allowlisted"},b.parentOrigin);throw new DOMException(`WebSocket connection to '${e}' is not allowed in Canvas.`,"SecurityError");},{CONNECTING:0,OPEN:1,CLOSING:2,CLOSED:3}),Object.defineProperty(window,"WebSocket",{value:d,writable:!1,configurable:!1})})({proxiedDomains:E.proxiedDomains||[],parentOrigin:E.parentOrigin});}).call(this);
</script><script data-bard-client-injected="true">((function(modelInformation) {
  const originalFetch = window.fetch;
  // TODO: b/421908508 - Move these out of the script and match all generative AI model calls.
  let googleLlmBaseApiUrls = [
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.textModelName + ':streamGenerateContent',
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.textModelName + ':generateContent',
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.imageModelName + ':predict',
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.imageModelName + ':predictLongRunning',
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.imageEditModelName + ':generateContent',
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.imageTransformModelName + ':generateContent',
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.videoModelName + ':predict',
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.videoModelName + ':predictLongRunning',
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.ttsModelName + ':generateContent',
  ];
  modelInformation.deprecatedTextModelNames.forEach((modelName) => {
    googleLlmBaseApiUrls.push(
      'https://generativelanguage.googleapis.com/v1beta/models/' + modelName + ':streamGenerateContent',
      'https://generativelanguage.googleapis.com/v1beta/models/' + modelName + ':generateContent',
    );
  });
  modelInformation.deprecatedImageModelNames.forEach((modelName) => {
    googleLlmBaseApiUrls.push(
      'https://generativelanguage.googleapis.com/v1beta/models/' + modelName + ':predict',
      'https://generativelanguage.googleapis.com/v1beta/models/' + modelName + ':predictLongRunning',
      'https://generativelanguage.googleapis.com/v1beta/models/' + modelName + ':generateContent',
      'https://generativelanguage.googleapis.com/v1beta/models/' + modelName + ':streamGenerateContent',
    );
  });
  modelInformation.deprecatedGenerateImageModelNames.forEach((modelName) => {
    googleLlmBaseApiUrls.push(
      'https://generativelanguage.googleapis.com/v1beta/models/' + modelName + ':generateContent',
      'https://generativelanguage.googleapis.com/v1beta/models/' + modelName + ':streamGenerateContent',
    );
  });
  modelInformation.deprecatedImageTransformModelNames.forEach((modelName) => {
    googleLlmBaseApiUrls.push(
      'https://generativelanguage.googleapis.com/v1beta/models/' + modelName + ':generateContent',
      'https://generativelanguage.googleapis.com/v1beta/models/' + modelName + ':streamGenerateContent',
    );
  });

  const pendingFetchResolvers = {};
  let nextPromiseId = 0;

  function handleStringInput(input, optionsArgument) {
    const actualUrl = input;
    const fetchCallArgs = [actualUrl, optionsArgument];
    const effectiveOptions = optionsArgument || {};
    const bodyForApiKeyCheck = effectiveOptions.body;
    const bodyForPostMessage = effectiveOptions.body;
    return { actualUrl, fetchCallArgs, effectiveOptions, bodyForApiKeyCheck, bodyForPostMessage };
  }

  function handleRequestInput(input, optionsArgument) {
    const actualUrl = input.url;
    const fetchCallArgs = [input, optionsArgument];
    const effectiveOptions = { method: input.method, headers: new Headers(input.headers) };
    let bodyForApiKeyCheck;
    let bodyForPostMessage;

    if (optionsArgument) {
      if (optionsArgument.method) effectiveOptions.method = optionsArgument.method;
      if (optionsArgument.headers) effectiveOptions.headers = new Headers(optionsArgument.headers);
      if ('body' in optionsArgument) {
        bodyForApiKeyCheck = optionsArgument.body;
        bodyForPostMessage = optionsArgument.body;
      } else {
        bodyForApiKeyCheck = undefined;
        bodyForPostMessage = input.body;
      }
    } else {
      bodyForApiKeyCheck = undefined;
      bodyForPostMessage = input.body;
    }
    return { actualUrl, fetchCallArgs, effectiveOptions, bodyForApiKeyCheck, bodyForPostMessage };
  }

  window.fetch = function(input, optionsArgument) {
    let actualUrl;
    let fetchCallArgs;
    let effectiveOptions = {};
    let bodyForApiKeyCheck;
    let bodyForPostMessage;

    if (typeof input === 'string') {
      ({actualUrl, fetchCallArgs, effectiveOptions, bodyForApiKeyCheck, bodyForPostMessage} = handleStringInput(input, optionsArgument));
    } else if (input instanceof Request) {
      ({actualUrl, fetchCallArgs, effectiveOptions, bodyForApiKeyCheck, bodyForPostMessage} = handleRequestInput(input, optionsArgument));
    } else {
      return originalFetch.apply(window, [input, optionsArgument]);
    }

    effectiveOptions.method = effectiveOptions.method || 'GET';
    if (!effectiveOptions.headers) {
      effectiveOptions.headers = new Headers();
    }


    if (typeof actualUrl === 'string' && googleLlmBaseApiUrls.some((url) => actualUrl.startsWith(url))) {
      let apiKeyIsNull = true;

      const regex = new RegExp("models/([^:]+)");
      const modelNameMatch = actualUrl.match(regex);
      const modelName = modelNameMatch ? modelNameMatch[1] : 'unspecified';


      try {
        const urlObject = new URL(actualUrl);  // Use URL object for robust parsing
        const apiKeyParam = urlObject.searchParams.get('key');
        if (apiKeyParam) {
          apiKeyIsNull = false;
        }
      } catch (e) {
        // Continue checks even if URL parsing fails
      }

      if (apiKeyIsNull && effectiveOptions.headers) {
        const h = new Headers(effectiveOptions.headers);
        const apiKeyHeaderValue = h.get('X-API-Key') || h.get('x-api-key');
        if (apiKeyHeaderValue) {
          apiKeyIsNull = false;
          return originalFetch.apply(window, fetchCallArgs);
        }
      }

      if (apiKeyIsNull && effectiveOptions.method && ['POST', 'PUT', 'PATCH'].includes(effectiveOptions.method.toUpperCase()) && typeof bodyForApiKeyCheck === 'string') {
        try {
          const bodyData = JSON.parse(bodyForApiKeyCheck);
          if (bodyData && bodyData.apiKey) {
            apiKeyIsNull = false;
            return originalFetch.apply(window, fetchCallArgs);
          }
        } catch (e) {
          // Ignore JSON parsing errors
        }
      }

      if(apiKeyIsNull) {
        const promiseId = nextPromiseId++;
        const promise = new Promise((resolve) => {
          pendingFetchResolvers[promiseId] = (resolvedResponse) => {
            delete pendingFetchResolvers[promiseId];
            resolve(resolvedResponse);
          };
        });

        let serializedBodyForPostMessage;
        if (typeof bodyForPostMessage === 'string' || bodyForPostMessage == null) {
            serializedBodyForPostMessage = bodyForPostMessage;
        } else if (bodyForPostMessage instanceof ReadableStream) {
            serializedBodyForPostMessage = null;
        } else {
            try {
                serializedBodyForPostMessage = JSON.stringify(bodyForPostMessage);
            } catch (e) {
                serializedBodyForPostMessage = null;
            }
        }

        const messageOptions = {
            method: effectiveOptions.method,
            headers: Object.fromEntries(new Headers(effectiveOptions.headers).entries()),
            body: serializedBodyForPostMessage
        };

        window.parent.postMessage({
          type: 'requestFetch',
          url: actualUrl,
          modelName: modelName,
          options: messageOptions,
          promiseId: promiseId,
        }, '*');

        return promise;
      }
      return originalFetch.apply(window, fetchCallArgs);
    }
    return originalFetch.apply(window, fetchCallArgs);
  };

  window.addEventListener('message', function(event) {
    if (event.data && event.data.type === 'resolveFetch') {
      const { promiseId, response } = event.data;
      if (pendingFetchResolvers[promiseId]) {
        try {
          const reconstructedResponse = new Response(response.body, {
            status: response.status,
            statusText: response.statusText,
            headers: new Headers(response.headers),
          });
          pendingFetchResolvers[promiseId](reconstructedResponse);
        } catch (error) {
          pendingFetchResolvers[promiseId](new Response(null, { status: 500, statusText: "Interceptor Response Reconstruction Error" }));
        }
      }
    }
  });

}))({"textModelName":"gemini-3-flash-preview","imageModelName":"imagen-4.0-generate-001","imageEditModelName":"gemini-3.1-flash-image","imageTransformModelName":"gemini-3-pro-image","videoModelName":"veo-2.0-generate-001","ttsModelName":"gemini-2.5-flash-preview-tts","deprecatedTextModelNames":["gemini-2.0-flash","gemini-2.5-flash","gemini-2.5-flash-preview-04-17","gemini-2.5-flash-preview-05-20","gemini-2.5-flash-preview-09-2025"],"deprecatedImageModelNames":["imagen-3.0-generate-001","imagen-3.0-generate-002"],"deprecatedGenerateImageModelNames":["gemini-2.5-flash-image-preview","gemini-2.5-flash-image","gemini-3.1-flash-image-preview"],"deprecatedImageTransformModelNames":["gemini-3-pro-image-preview-11-2025"]})</script><script data-bard-client-injected="true">(function(){'use strict';function a(){window.parent.postMessage({type:"interaction"},"*")}window.addEventListener("click",a,{capture:!0,passive:!0});window.addEventListener("touchstart",a,{capture:!0,passive:!0});window.addEventListener("keydown",a,{capture:!0,passive:!0});}).call(this);
</script><script data-bard-client-injected="true">(function() {
  const originalConsoleLog = console.log;
  const originalConsoleError = console.error;

    /**
   * Normalizes an error event or a promise rejection reason into a structured error object.
   * @param {*} errorEventOrReason The error object or reason.
   * @return {object} Structured error data { message, name, stack }.
   */
  function getErrorObject(errorEventOrReason) {
    if (errorEventOrReason instanceof Error) {
      return {
        message: errorEventOrReason.message,
        name: errorEventOrReason.name,
        stack: errorEventOrReason.stack,
      };
    }
    // Fallback for non-Error objects.
    try {
      return {
        message: JSON.stringify(errorEventOrReason),
        name: 'UnknownErrorType',
        stack: null,
      };
    } catch (e) {
      return {
        message: String(errorEventOrReason),
        name: 'UnknownErrorTypeNonStringifiable',
        stack: null,
      };
    }
  }

  /**
   * Converts an array of arguments (from log/error) into a single string.
   * Handles Error objects specially to include their message and stack.
   * @param {Array<*>} args - Arguments passed to console methods.
   * @return {string} A string representation of the arguments.
   */
  function stringifyArgs(args) {
    return args
      .map((arg) => {
        if (arg instanceof Error) {
          const {message, stack} = arg;
          return `Error: ${message}${stack ? ('\nStack: ' + stack) : ''}`;
        }
        if (typeof arg === 'object' && arg !== null) {
          try {
            return JSON.stringify(arg);
          } catch (error) {
            return '[Circular Object]';
          }
        } else {
          return String(arg);
        }
      })
      .join(' ');
  }

  console.log = function(...args) {
    const logString = stringifyArgs(args);
    window.parent.postMessage({ type: 'log', message: logString }, '*');
    originalConsoleLog.apply(console, args);
  };

  console.error = function(...args) {
    let errorData;
    if (args.length > 0 && args[0] instanceof Error) {
      const err = args[0];
      // If the first arg is an Error, capture its details.
      errorData = {
        type: 'error',
        source: 'CONSOLE_ERROR',
        ...getErrorObject(err),
        rawArgsString: stringifyArgs(args.slice(1)),
        timestamp: new Date().toISOString(),
      };
    } else {
      // If not an Error object, treat all args as a general error message.
      errorData = {
        type: 'error',
        source: 'CONSOLE_ERROR',
        message: stringifyArgs(args),
        name: 'ConsoleLoggedError',
        stack: null,
        timestamp: new Date().toISOString(),
      };
    }
    window.parent.postMessage(errorData, '*');
    originalConsoleError.apply(console, args);
  };

  // Listen for global unhandled synchronous errors.
  window.addEventListener('error', function(event) {
    const errorDetails = event.error ? getErrorObject(event.error) : {
      message: event.message,
      name: 'GlobalError',
      stack: null,
      filename: event.filename,
      lineno: event.lineno,
      colno: event.colno,
    };

    window.parent.postMessage({
      type: 'error',
      source: 'global',
      ...errorDetails,
      message: errorDetails.message || event.message,
      timestamp: new Date().toISOString(),
    }, '*');
  });

  // Listen for unhandled promise rejections (asynchronous errors).
  window.addEventListener('unhandledrejection', function(event) {
    const errorDetails = getErrorObject(event.reason);

    window.parent.postMessage({
      type: 'error',
      source: 'unhandledrejection',
      ...errorDetails,
      message: errorDetails.message || 'Unhandled Promise Rejection',
      timestamp: new Date().toISOString(),
    }, '*');
  });

})();</script>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>William Guzman | Rutgers Senior Finance Portfolio</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts: Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&amp;display=swap" rel="stylesheet">
    
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    colors: {
                        rutgers: {
                            DEFAULT: '#CC0033',
                            dark: '#990026',
                            light: '#ff1a47',
                            glow: 'rgba(204, 0, 51, 0.15)'
                        },
                        navy: {
                            800: '#0f172a',
                            900: '#0b0f19',
                            950: '#060911'
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    
    <style>
        /* Custom scrollbar and glassmorphism styling */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #0f172a;
        }
        ::-webkit-scrollbar-thumb {
            background: #cc0033;
            border-radius: 4px;
        }
        .glass-panel {
            background: rgba(15, 23, 42, 0.85);
            backdrop-filter: blur(12px);
            -webkit-backdrop-filter: blur(12px);
        }
        .scarlet-gradient {
            background: linear-gradient(135deg, #cc0033 0%, #800020 100%);
        }
    </style>
<style>*, ::before, ::after{--tw-border-spacing-x:0;--tw-border-spacing-y:0;--tw-translate-x:0;--tw-translate-y:0;--tw-rotate:0;--tw-skew-x:0;--tw-skew-y:0;--tw-scale-x:1;--tw-scale-y:1;--tw-pan-x: ;--tw-pan-y: ;--tw-pinch-zoom: ;--tw-scroll-snap-strictness:proximity;--tw-gradient-from-position: ;--tw-gradient-via-position: ;--tw-gradient-to-position: ;--tw-ordinal: ;--tw-slashed-zero: ;--tw-numeric-figure: ;--tw-numeric-spacing: ;--tw-numeric-fraction: ;--tw-ring-inset: ;--tw-ring-offset-width:0px;--tw-ring-offset-color:#fff;--tw-ring-color:rgb(59 130 246 / 0.5);--tw-ring-offset-shadow:0 0 #0000;--tw-ring-shadow:0 0 #0000;--tw-shadow:0 0 #0000;--tw-shadow-colored:0 0 #0000;--tw-blur: ;--tw-brightness: ;--tw-contrast: ;--tw-grayscale: ;--tw-hue-rotate: ;--tw-invert: ;--tw-saturate: ;--tw-sepia: ;--tw-drop-shadow: ;--tw-backdrop-blur: ;--tw-backdrop-brightness: ;--tw-backdrop-contrast: ;--tw-backdrop-grayscale: ;--tw-backdrop-hue-rotate: ;--tw-backdrop-invert: ;--tw-backdrop-opacity: ;--tw-backdrop-saturate: ;--tw-backdrop-sepia: ;--tw-contain-size: ;--tw-contain-layout: ;--tw-contain-paint: ;--tw-contain-style: }::backdrop{--tw-border-spacing-x:0;--tw-border-spacing-y:0;--tw-translate-x:0;--tw-translate-y:0;--tw-rotate:0;--tw-skew-x:0;--tw-skew-y:0;--tw-scale-x:1;--tw-scale-y:1;--tw-pan-x: ;--tw-pan-y: ;--tw-pinch-zoom: ;--tw-scroll-snap-strictness:proximity;--tw-gradient-from-position: ;--tw-gradient-via-position: ;--tw-gradient-to-position: ;--tw-ordinal: ;--tw-slashed-zero: ;--tw-numeric-figure: ;--tw-numeric-spacing: ;--tw-numeric-fraction: ;--tw-ring-inset: ;--tw-ring-offset-width:0px;--tw-ring-offset-color:#fff;--tw-ring-color:rgb(59 130 246 / 0.5);--tw-ring-offset-shadow:0 0 #0000;--tw-ring-shadow:0 0 #0000;--tw-shadow:0 0 #0000;--tw-shadow-colored:0 0 #0000;--tw-blur: ;--tw-brightness: ;--tw-contrast: ;--tw-grayscale: ;--tw-hue-rotate: ;--tw-invert: ;--tw-saturate: ;--tw-sepia: ;--tw-drop-shadow: ;--tw-backdrop-blur: ;--tw-backdrop-brightness: ;--tw-backdrop-contrast: ;--tw-backdrop-grayscale: ;--tw-backdrop-hue-rotate: ;--tw-backdrop-invert: ;--tw-backdrop-opacity: ;--tw-backdrop-saturate: ;--tw-backdrop-sepia: ;--tw-contain-size: ;--tw-contain-layout: ;--tw-contain-paint: ;--tw-contain-style: }/* ! tailwindcss v3.4.17 | MIT License | https://tailwindcss.com */*,::after,::before{box-sizing:border-box;border-width:0;border-style:solid;border-color:#e5e7eb}::after,::before{--tw-content:''}:host,html{line-height:1.5;-webkit-text-size-adjust:100%;-moz-tab-size:4;tab-size:4;font-family:Inter, sans-serif;font-feature-settings:normal;font-variation-settings:normal;-webkit-tap-highlight-color:transparent}body{margin:0;line-height:inherit}hr{height:0;color:inherit;border-top-width:1px}abbr:where([title]){-webkit-text-decoration:underline dotted;text-decoration:underline dotted}h1,h2,h3,h4,h5,h6{font-size:inherit;font-weight:inherit}a{color:inherit;text-decoration:inherit}b,strong{font-weight:bolder}code,kbd,pre,samp{font-family:ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;font-feature-settings:normal;font-variation-settings:normal;font-size:1em}small{font-size:80%}sub,sup{font-size:75%;line-height:0;position:relative;vertical-align:baseline}sub{bottom:-.25em}sup{top:-.5em}table{text-indent:0;border-color:inherit;border-collapse:collapse}button,input,optgroup,select,textarea{font-family:inherit;font-feature-settings:inherit;font-variation-settings:inherit;font-size:100%;font-weight:inherit;line-height:inherit;letter-spacing:inherit;color:inherit;margin:0;padding:0}button,select{text-transform:none}button,input:where([type=button]),input:where([type=reset]),input:where([type=submit]){-webkit-appearance:button;background-color:transparent;background-image:none}:-moz-focusring{outline:auto}:-moz-ui-invalid{box-shadow:none}progress{vertical-align:baseline}::-webkit-inner-spin-button,::-webkit-outer-spin-button{height:auto}[type=search]{-webkit-appearance:textfield;outline-offset:-2px}::-webkit-search-decoration{-webkit-appearance:none}::-webkit-file-upload-button{-webkit-appearance:button;font:inherit}summary{display:list-item}blockquote,dd,dl,figure,h1,h2,h3,h4,h5,h6,hr,p,pre{margin:0}fieldset{margin:0;padding:0}legend{padding:0}menu,ol,ul{list-style:none;margin:0;padding:0}dialog{padding:0}textarea{resize:vertical}input::placeholder,textarea::placeholder{opacity:1;color:#9ca3af}[role=button],button{cursor:pointer}:disabled{cursor:default}audio,canvas,embed,iframe,img,object,svg,video{display:block;vertical-align:middle}img,video{max-width:100%;height:auto}[hidden]:where(:not([hidden=until-found])){display:none}.pointer-events-none{pointer-events:none}.fixed{position:fixed}.absolute{position:absolute}.relative{position:relative}.inset-0{inset:0px}.left-0{left:0px}.left-1\/2{left:50%}.right-0{right:0px}.top-0{top:0px}.top-1\/4{top:25%}.bottom-5{bottom:1.25rem}.right-4{right:1rem}.right-5{right:1.25rem}.top-4{top:1rem}.z-10{z-index:10}.z-40{z-index:40}.z-50{z-index:50}.mx-auto{margin-left:auto;margin-right:auto}.-mt-1{margin-top:-0.25rem}.mb-10{margin-bottom:2.5rem}.mb-3{margin-bottom:0.75rem}.mb-6{margin-bottom:1.5rem}.mb-1{margin-bottom:0.25rem}.mb-12{margin-bottom:3rem}.mb-2{margin-bottom:0.5rem}.mb-4{margin-bottom:1rem}.mb-8{margin-bottom:2rem}.mr-1{margin-right:0.25rem}.mr-1\.5{margin-right:0.375rem}.mr-2{margin-right:0.5rem}.mt-6{margin-top:1.5rem}.block{display:block}.flex{display:flex}.inline-flex{display:inline-flex}.grid{display:grid}.hidden{display:none}.h-10{height:2.5rem}.h-16{height:4rem}.h-2{height:0.5rem}.h-96{height:24rem}.h-1{height:0.25rem}.h-12{height:3rem}.h-full{height:100%}.max-h-48{max-height:12rem}.max-h-\[90vh\]{max-height:90vh}.min-h-screen{min-height:100vh}.w-10{width:2.5rem}.w-2{width:0.5rem}.w-96{width:24rem}.w-12{width:3rem}.w-8{width:2rem}.w-full{width:100%}.max-w-3xl{max-width:48rem}.max-w-5xl{max-width:64rem}.max-w-7xl{max-width:80rem}.max-w-2xl{max-width:42rem}.max-w-4xl{max-width:56rem}.max-w-6xl{max-width:72rem}.max-w-xl{max-width:36rem}.flex-1{flex:1 1 0%}.-translate-x-1\/2{--tw-translate-x:-50%;transform:translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y))}.-translate-y-1\/2{--tw-translate-y:-50%;transform:translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y))}.translate-y-20{--tw-translate-y:5rem;transform:translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y))}.transform{transform:translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y))}@keyframes pulse{50%{opacity:.5}}.animate-pulse{animation:pulse 2s cubic-bezier(0.4, 0, 0.6, 1) infinite}.cursor-pointer{cursor:pointer}.grid-cols-1{grid-template-columns:repeat(1, minmax(0, 1fr))}.flex-col{flex-direction:column}.flex-wrap{flex-wrap:wrap}.items-start{align-items:flex-start}.items-center{align-items:center}.justify-center{justify-content:center}.justify-between{justify-content:space-between}.gap-2{gap:0.5rem}.gap-3{gap:0.75rem}.gap-4{gap:1rem}.gap-8{gap:2rem}.gap-6{gap:1.5rem}.space-y-3 > :not([hidden]) ~ :not([hidden]){--tw-space-y-reverse:0;margin-top:calc(0.75rem * calc(1 - var(--tw-space-y-reverse)));margin-bottom:calc(0.75rem * var(--tw-space-y-reverse))}.space-y-6 > :not([hidden]) ~ :not([hidden]){--tw-space-y-reverse:0;margin-top:calc(1.5rem * calc(1 - var(--tw-space-y-reverse)));margin-bottom:calc(1.5rem * var(--tw-space-y-reverse))}.overflow-hidden{overflow:hidden}.overflow-y-auto{overflow-y:auto}.scroll-smooth{scroll-behavior:smooth}.truncate{overflow:hidden;text-overflow:ellipsis;white-space:nowrap}.rounded-2xl{border-radius:1rem}.rounded-full{border-radius:9999px}.rounded-lg{border-radius:0.5rem}.rounded-xl{border-radius:0.75rem}.rounded{border-radius:0.25rem}.rounded-3xl{border-radius:1.5rem}.border{border-width:1px}.border-b{border-bottom-width:1px}.border-t{border-top-width:1px}.border-emerald-500\/20{border-color:rgb(16 185 129 / 0.2)}.border-rutgers\/30{border-color:rgb(204 0 51 / 0.3)}.border-slate-700{--tw-border-opacity:1;border-color:rgb(51 65 85 / var(--tw-border-opacity, 1))}.border-slate-700\/80{border-color:rgb(51 65 85 / 0.8)}.border-slate-800{--tw-border-opacity:1;border-color:rgb(30 41 59 / var(--tw-border-opacity, 1))}.border-slate-800\/80{border-color:rgb(30 41 59 / 0.8)}.border-blue-500\/20{border-color:rgb(59 130 246 / 0.2)}.border-purple-500\/20{border-color:rgb(168 85 247 / 0.2)}.border-rutgers\/20{border-color:rgb(204 0 51 / 0.2)}.border-slate-700\/60{border-color:rgb(51 65 85 / 0.6)}.bg-emerald-400{--tw-bg-opacity:1;background-color:rgb(52 211 153 / var(--tw-bg-opacity, 1))}.bg-emerald-500\/10{background-color:rgb(16 185 129 / 0.1)}.bg-rutgers{--tw-bg-opacity:1;background-color:rgb(204 0 51 / var(--tw-bg-opacity, 1))}.bg-rutgers\/10{background-color:rgb(204 0 51 / 0.1)}.bg-rutgers\/20{background-color:rgb(204 0 51 / 0.2)}.bg-slate-800{--tw-bg-opacity:1;background-color:rgb(30 41 59 / var(--tw-bg-opacity, 1))}.bg-slate-800\/80{background-color:rgb(30 41 59 / 0.8)}.bg-slate-900{--tw-bg-opacity:1;background-color:rgb(15 23 42 / var(--tw-bg-opacity, 1))}.bg-amber-500{--tw-bg-opacity:1;background-color:rgb(245 158 11 / var(--tw-bg-opacity, 1))}.bg-amber-500\/10{background-color:rgb(245 158 11 / 0.1)}.bg-blue-500{--tw-bg-opacity:1;background-color:rgb(59 130 246 / var(--tw-bg-opacity, 1))}.bg-blue-500\/10{background-color:rgb(59 130 246 / 0.1)}.bg-emerald-500{--tw-bg-opacity:1;background-color:rgb(16 185 129 / var(--tw-bg-opacity, 1))}.bg-indigo-500{--tw-bg-opacity:1;background-color:rgb(99 102 241 / var(--tw-bg-opacity, 1))}.bg-indigo-500\/10{background-color:rgb(99 102 241 / 0.1)}.bg-purple-500{--tw-bg-opacity:1;background-color:rgb(168 85 247 / var(--tw-bg-opacity, 1))}.bg-purple-500\/10{background-color:rgb(168 85 247 / 0.1)}.bg-slate-700{--tw-bg-opacity:1;background-color:rgb(51 65 85 / var(--tw-bg-opacity, 1))}.bg-slate-800\/60{background-color:rgb(30 41 59 / 0.6)}.bg-slate-950{--tw-bg-opacity:1;background-color:rgb(2 6 23 / var(--tw-bg-opacity, 1))}.bg-slate-950\/80{background-color:rgb(2 6 23 / 0.8)}.bg-gradient-to-b{background-image:linear-gradient(to bottom, var(--tw-gradient-stops))}.from-slate-950{--tw-gradient-from:#020617 var(--tw-gradient-from-position);--tw-gradient-to:rgb(2 6 23 / 0) var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), var(--tw-gradient-to)}.via-slate-900{--tw-gradient-to:rgb(15 23 42 / 0)  var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), #0f172a var(--tw-gradient-via-position), var(--tw-gradient-to)}.to-slate-900{--tw-gradient-to:#0f172a var(--tw-gradient-to-position)}.p-2{padding:0.5rem}.p-6{padding:1.5rem}.p-2\.5{padding:0.625rem}.p-3{padding:0.75rem}.p-4{padding:1rem}.p-5{padding:1.25rem}.px-3\.5{padding-left:0.875rem;padding-right:0.875rem}.px-4{padding-left:1rem;padding-right:1rem}.px-6{padding-left:1.5rem;padding-right:1.5rem}.py-1\.5{padding-top:0.375rem;padding-bottom:0.375rem}.py-2{padding-top:0.5rem;padding-bottom:0.5rem}.py-3\.5{padding-top:0.875rem;padding-bottom:0.875rem}.px-2\.5{padding-left:0.625rem;padding-right:0.625rem}.px-3{padding-left:0.75rem;padding-right:0.75rem}.px-5{padding-left:1.25rem;padding-right:1.25rem}.py-1{padding-top:0.25rem;padding-bottom:0.25rem}.py-16{padding-top:4rem;padding-bottom:4rem}.py-2\.5{padding-top:0.625rem;padding-bottom:0.625rem}.py-20{padding-top:5rem;padding-bottom:5rem}.py-3{padding-top:0.75rem;padding-bottom:0.75rem}.py-8{padding-top:2rem;padding-bottom:2rem}.pb-20{padding-bottom:5rem}.pb-6{padding-bottom:1.5rem}.pt-2{padding-top:0.5rem}.pt-32{padding-top:8rem}.pt-4{padding-top:1rem}.text-center{text-align:center}.font-sans{font-family:Inter, sans-serif}.font-mono{font-family:ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace}.text-4xl{font-size:2.25rem;line-height:2.5rem}.text-lg{font-size:1.125rem;line-height:1.75rem}.text-sm{font-size:0.875rem;line-height:1.25rem}.text-xl{font-size:1.25rem;line-height:1.75rem}.text-xs{font-size:0.75rem;line-height:1rem}.text-2xl{font-size:1.5rem;line-height:2rem}.text-3xl{font-size:1.875rem;line-height:2.25rem}.text-base{font-size:1rem;line-height:1.5rem}.font-black{font-weight:900}.font-bold{font-weight:700}.font-medium{font-weight:500}.font-semibold{font-weight:600}.font-extrabold{font-weight:800}.uppercase{text-transform:uppercase}.leading-relaxed{line-height:1.625}.tracking-tight{letter-spacing:-0.025em}.tracking-wider{letter-spacing:0.05em}.tracking-widest{letter-spacing:0.1em}.text-emerald-400{--tw-text-opacity:1;color:rgb(52 211 153 / var(--tw-text-opacity, 1))}.text-rutgers{--tw-text-opacity:1;color:rgb(204 0 51 / var(--tw-text-opacity, 1))}.text-slate-100{--tw-text-opacity:1;color:rgb(241 245 249 / var(--tw-text-opacity, 1))}.text-slate-200{--tw-text-opacity:1;color:rgb(226 232 240 / var(--tw-text-opacity, 1))}.text-slate-300{--tw-text-opacity:1;color:rgb(203 213 225 / var(--tw-text-opacity, 1))}.text-slate-400{--tw-text-opacity:1;color:rgb(148 163 184 / var(--tw-text-opacity, 1))}.text-white{--tw-text-opacity:1;color:rgb(255 255 255 / var(--tw-text-opacity, 1))}.text-amber-400{--tw-text-opacity:1;color:rgb(251 191 36 / var(--tw-text-opacity, 1))}.text-blue-400{--tw-text-opacity:1;color:rgb(96 165 250 / var(--tw-text-opacity, 1))}.text-indigo-400{--tw-text-opacity:1;color:rgb(129 140 248 / var(--tw-text-opacity, 1))}.text-purple-400{--tw-text-opacity:1;color:rgb(192 132 252 / var(--tw-text-opacity, 1))}.text-slate-500{--tw-text-opacity:1;color:rgb(100 116 139 / var(--tw-text-opacity, 1))}.accent-rutgers{accent-color:#CC0033}.opacity-0{opacity:0}.shadow-2xl{--tw-shadow:0 25px 50px -12px rgb(0 0 0 / 0.25);--tw-shadow-colored:0 25px 50px -12px var(--tw-shadow-color);box-shadow:var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow)}.shadow-lg{--tw-shadow:0 10px 15px -3px rgb(0 0 0 / 0.1), 0 4px 6px -4px rgb(0 0 0 / 0.1);--tw-shadow-colored:0 10px 15px -3px var(--tw-shadow-color), 0 4px 6px -4px var(--tw-shadow-color);box-shadow:var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow)}.shadow-md{--tw-shadow:0 4px 6px -1px rgb(0 0 0 / 0.1), 0 2px 4px -2px rgb(0 0 0 / 0.1);--tw-shadow-colored:0 4px 6px -1px var(--tw-shadow-color), 0 2px 4px -2px var(--tw-shadow-color);box-shadow:var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow)}.shadow-xl{--tw-shadow:0 20px 25px -5px rgb(0 0 0 / 0.1), 0 8px 10px -6px rgb(0 0 0 / 0.1);--tw-shadow-colored:0 20px 25px -5px var(--tw-shadow-color), 0 8px 10px -6px var(--tw-shadow-color);box-shadow:var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow)}.shadow-rutgers\/20{--tw-shadow-color:rgb(204 0 51 / 0.2);--tw-shadow:var(--tw-shadow-colored)}.shadow-rutgers\/30{--tw-shadow-color:rgb(204 0 51 / 0.3);--tw-shadow:var(--tw-shadow-colored)}.blur-3xl{--tw-blur:blur(64px);filter:var(--tw-blur) var(--tw-brightness) var(--tw-contrast) var(--tw-grayscale) var(--tw-hue-rotate) var(--tw-invert) var(--tw-saturate) var(--tw-sepia) var(--tw-drop-shadow)}.backdrop-blur-md{--tw-backdrop-blur:blur(12px);-webkit-backdrop-filter:var(--tw-backdrop-blur) var(--tw-backdrop-brightness) var(--tw-backdrop-contrast) var(--tw-backdrop-grayscale) var(--tw-backdrop-hue-rotate) var(--tw-backdrop-invert) var(--tw-backdrop-opacity) var(--tw-backdrop-saturate) var(--tw-backdrop-sepia);backdrop-filter:var(--tw-backdrop-blur) var(--tw-backdrop-brightness) var(--tw-backdrop-contrast) var(--tw-backdrop-grayscale) var(--tw-backdrop-hue-rotate) var(--tw-backdrop-invert) var(--tw-backdrop-opacity) var(--tw-backdrop-saturate) var(--tw-backdrop-sepia)}.transition-all{transition-property:all;transition-timing-function:cubic-bezier(0.4, 0, 0.2, 1);transition-duration:150ms}.transition-colors{transition-property:color, background-color, border-color, fill, stroke, -webkit-text-decoration-color;transition-property:color, background-color, border-color, text-decoration-color, fill, stroke;transition-property:color, background-color, border-color, text-decoration-color, fill, stroke, -webkit-text-decoration-color;transition-timing-function:cubic-bezier(0.4, 0, 0.2, 1);transition-duration:150ms}.transition-transform{transition-property:transform;transition-timing-function:cubic-bezier(0.4, 0, 0.2, 1);transition-duration:150ms}.duration-300{transition-duration:300ms}.selection\:bg-rutgers *::selection{--tw-bg-opacity:1;background-color:rgb(204 0 51 / var(--tw-bg-opacity, 1))}.selection\:text-white *::selection{--tw-text-opacity:1;color:rgb(255 255 255 / var(--tw-text-opacity, 1))}.selection\:bg-rutgers::selection{--tw-bg-opacity:1;background-color:rgb(204 0 51 / var(--tw-bg-opacity, 1))}.selection\:text-white::selection{--tw-text-opacity:1;color:rgb(255 255 255 / var(--tw-text-opacity, 1))}.hover\:-translate-y-0\.5:hover{--tw-translate-y:-0.125rem;transform:translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y))}.hover\:-translate-y-1:hover{--tw-translate-y:-0.25rem;transform:translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y))}.hover\:scale-105:hover{--tw-scale-x:1.05;--tw-scale-y:1.05;transform:translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y))}.hover\:border-rutgers:hover{--tw-border-opacity:1;border-color:rgb(204 0 51 / var(--tw-border-opacity, 1))}.hover\:border-rutgers\/50:hover{border-color:rgb(204 0 51 / 0.5)}.hover\:border-rutgers\/60:hover{border-color:rgb(204 0 51 / 0.6)}.hover\:bg-rutgers-dark:hover{--tw-bg-opacity:1;background-color:rgb(153 0 38 / var(--tw-bg-opacity, 1))}.hover\:bg-slate-700:hover{--tw-bg-opacity:1;background-color:rgb(51 65 85 / var(--tw-bg-opacity, 1))}.hover\:text-rutgers:hover{--tw-text-opacity:1;color:rgb(204 0 51 / var(--tw-text-opacity, 1))}.hover\:text-white:hover{--tw-text-opacity:1;color:rgb(255 255 255 / var(--tw-text-opacity, 1))}.group:hover .group-hover\:scale-105{--tw-scale-x:1.05;--tw-scale-y:1.05;transform:translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y))}.group:hover .group-hover\:scale-110{--tw-scale-x:1.1;--tw-scale-y:1.1;transform:translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y))}.group:hover .group-hover\:text-rutgers{--tw-text-opacity:1;color:rgb(204 0 51 / var(--tw-text-opacity, 1))}.group:hover .group-hover\:text-blue-400{--tw-text-opacity:1;color:rgb(96 165 250 / var(--tw-text-opacity, 1))}.group:hover .group-hover\:text-purple-400{--tw-text-opacity:1;color:rgb(192 132 252 / var(--tw-text-opacity, 1))}@media (min-width: 640px){.sm\:grid-cols-2{grid-template-columns:repeat(2, minmax(0, 1fr))}.sm\:grid-cols-3{grid-template-columns:repeat(3, minmax(0, 1fr))}.sm\:flex-row{flex-direction:row}.sm\:items-center{align-items:center}.sm\:p-8{padding:2rem}.sm\:p-10{padding:2.5rem}.sm\:px-6{padding-left:1.5rem;padding-right:1.5rem}.sm\:text-6xl{font-size:3.75rem;line-height:1}.sm\:text-xl{font-size:1.25rem;line-height:1.75rem}.sm\:text-3xl{font-size:1.875rem;line-height:2.25rem}.sm\:text-5xl{font-size:3rem;line-height:1}}@media (min-width: 768px){.md\:flex{display:flex}.md\:hidden{display:none}.md\:grid-cols-3{grid-template-columns:repeat(3, minmax(0, 1fr))}.md\:flex-row{flex-direction:row}.md\:items-center{align-items:center}.md\:pb-28{padding-bottom:7rem}.md\:pt-40{padding-top:10rem}}@media (min-width: 1024px){.lg\:col-span-6{grid-column:span 6 / span 6}.lg\:grid-cols-12{grid-template-columns:repeat(12, minmax(0, 1fr))}.lg\:grid-cols-3{grid-template-columns:repeat(3, minmax(0, 1fr))}.lg\:px-8{padding-left:2rem;padding-right:2rem}}</style></head>
<body class="bg-slate-900 text-slate-100 font-sans transition-colors duration-300 min-h-screen flex flex-col selection:bg-rutgers selection:text-white">

    <!-- Top Navigation Bar -->
    <nav class="fixed top-0 left-0 right-0 z-40 glass-panel border-b border-slate-800/80">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-16">
                <!-- Brand Logo -->
                <a href="#hero" class="flex items-center gap-3 group">
                    <div class="w-10 h-10 rounded-lg bg-rutgers flex items-center justify-center font-black text-white text-xl shadow-lg shadow-rutgers/30 group-hover:scale-105 transition-transform">
                        R
                    </div>
                    <div>
                        <span class="font-bold text-lg tracking-tight block text-white group-hover:text-rutgers transition-colors">William Guzman</span>
                        <span class="text-xs text-slate-400 block -mt-1 font-medium">Rutgers Finance '26</span>
                    </div>
                </a>

                <!-- Nav Links -->
                <div class="hidden md:flex items-center gap-8 text-sm font-semibold">
                    <a href="#about" class="text-slate-300 hover:text-rutgers transition-colors">Personal Statement</a>
                    <a href="#skills" class="text-slate-300 hover:text-rutgers transition-colors">Skills</a>
                    <a href="#projects" class="text-slate-300 hover:text-rutgers transition-colors">Projects</a>
                    <a href="#dcf-calculator" class="text-slate-300 hover:text-rutgers transition-colors">Interactive DCF</a>
                    <a href="#contact" class="text-slate-300 hover:text-rutgers transition-colors">Contact</a>
                </div>

                <!-- Action Controls -->
                <div class="flex items-center gap-3">
                    <a href="#export-section" class="bg-rutgers hover:bg-rutgers-dark text-white px-4 py-2 rounded-lg text-xs font-bold uppercase tracking-wider flex items-center gap-2 shadow-md shadow-rutgers/20 transition-all hover:scale-105">
                        <i class="fa-solid fa-code"></i> Copy / Export Code
                    </a>
                    <button id="mobileMenuBtn" class="md:hidden text-slate-300 hover:text-white p-2">
                        <i class="fa-solid fa-bars text-xl"></i>
                    </button>
                </div>
            </div>
        </div>

        <!-- Mobile Menu Drawer -->
        <div id="mobileMenu" class="hidden md:hidden border-t border-slate-800 bg-slate-900 px-4 pt-2 pb-6 space-y-3">
            <a href="#about" class="mobile-nav-link block py-2 text-slate-300 hover:text-rutgers">Personal Statement</a>
            <a href="#skills" class="mobile-nav-link block py-2 text-slate-300 hover:text-rutgers">Skills</a>
            <a href="#projects" class="mobile-nav-link block py-2 text-slate-300 hover:text-rutgers">Projects</a>
            <a href="#dcf-calculator" class="mobile-nav-link block py-2 text-slate-300 hover:text-rutgers">Interactive DCF</a>
            <a href="#contact" class="mobile-nav-link block py-2 text-slate-300 hover:text-rutgers">Contact</a>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="hero" class="pt-32 pb-20 md:pt-40 md:pb-28 relative overflow-hidden bg-gradient-to-b from-slate-950 via-slate-900 to-slate-900 border-b border-slate-800">
        <!-- Rutgers Scarlet Background Glow -->
        <div class="absolute top-1/4 left-1/2 -translate-x-1/2 -translate-y-1/2 w-96 h-96 bg-rutgers/10 rounded-full blur-3xl pointer-events-none"></div>
        
        <div class="max-w-5xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10 text-center">
            <!-- University & Status Badges -->
            <div class="inline-flex flex-wrap items-center justify-center gap-3 mb-6">
                <span class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full text-xs font-bold bg-rutgers/20 text-rutgers border border-rutgers/30">
                    <i class="fa-solid fa-graduation-cap"></i> Senior Finance Major | Rutgers Business School
                </span>
                <span class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full text-xs font-semibold bg-emerald-500/10 text-emerald-400 border border-emerald-500/20">
                    <span class="w-2 h-2 rounded-full bg-emerald-400 animate-pulse"></span> Seeking Financial Analyst Roles
                </span>
            </div>

            <!-- Full Name Header -->
            <h1 class="text-4xl sm:text-6xl font-black text-white tracking-tight mb-6">
                William Guzman
            </h1>

            <!-- Requirement 1: Personal Statement Card -->
            <div id="about" class="bg-slate-800/80 backdrop-blur-md p-6 sm:p-8 rounded-2xl border border-slate-700/80 shadow-2xl max-w-3xl mx-auto mb-10">
                <div class="text-xs font-bold uppercase tracking-widest text-rutgers mb-3 flex items-center justify-center gap-2">
                    <i class="fa-solid fa-quote-left"></i> Personal Statement
                </div>
                <p class="text-lg sm:text-xl font-medium text-slate-100 leading-relaxed">
                    "A senior Finance major at Rutgers University leveraging quantitative analysis, DCF financial modeling, and data analytics to deliver strategic insights and investment value."
                </p>
            </div>

            <!-- Call to Action Buttons -->
            <div class="flex flex-wrap justify-center items-center gap-4">
                <a href="#projects" class="px-6 py-3.5 rounded-xl bg-rutgers hover:bg-rutgers-dark text-white font-bold shadow-lg shadow-rutgers/30 transition-all hover:-translate-y-0.5 flex items-center gap-2 text-sm">
                    <i class="fa-solid fa-chart-line"></i> View Financial Projects
                </a>
                <a href="#dcf-calculator" class="px-6 py-3.5 rounded-xl bg-slate-800 hover:bg-slate-700 text-slate-200 border border-slate-700 font-bold transition-all hover:-translate-y-0.5 flex items-center gap-2 text-sm">
                    <i class="fa-solid fa-calculator"></i> Try DCF Model
                </a>
            </div>
        </div>
    </section>

    <!-- Requirement 2: Skills Showcase Section -->
    <section id="skills" class="py-20 bg-slate-900 border-b border-slate-800">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            
            <div class="text-center max-w-2xl mx-auto mb-12">
                <h2 class="text-3xl font-bold text-white mb-3 flex items-center justify-center gap-3">
                    <span class="w-8 h-1 bg-rutgers rounded-full"></span>
                    Skills Showcase
                    <span class="w-8 h-1 bg-rutgers rounded-full"></span>
                </h2>
                <p class="text-slate-400">Quantitative skills, financial modeling capabilities, and technical software tools tailored for investment analysis.</p>
            </div>

            <!-- Interactive Skill Category Filters -->
            <div class="flex flex-wrap justify-center gap-2 mb-10" id="skill-filters">
                <button class="skill-filter-btn active bg-rutgers text-white px-4 py-2 rounded-lg text-xs font-bold uppercase tracking-wider transition-all" data-filter="all">
                    All Skills
                </button>
                <button class="skill-filter-btn bg-slate-800 text-slate-300 hover:bg-slate-700 px-4 py-2 rounded-lg text-xs font-bold uppercase tracking-wider transition-all" data-filter="valuation">
                    Valuation &amp; Modeling
                </button>
                <button class="skill-filter-btn bg-slate-800 text-slate-300 hover:bg-slate-700 px-4 py-2 rounded-lg text-xs font-bold uppercase tracking-wider transition-all" data-filter="tech">
                    Data &amp; Tools
                </button>
                <button class="skill-filter-btn bg-slate-800 text-slate-300 hover:bg-slate-700 px-4 py-2 rounded-lg text-xs font-bold uppercase tracking-wider transition-all" data-filter="finance">
                    Corporate Finance
                </button>
            </div>

            <!-- Skills Cards Grid -->
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6" id="skills-grid">
                
                <!-- Skill 1 -->
                <div class="skill-card bg-slate-800/60 border border-slate-700/60 rounded-xl p-5 hover:border-rutgers/60 transition-all hover:-translate-y-1" data-category="valuation">
                    <div class="flex items-center justify-between mb-3">
                        <div class="w-10 h-10 rounded-lg bg-rutgers/10 text-rutgers flex items-center justify-center text-lg font-bold">
                            <i class="fa-solid fa-calculator"></i>
                        </div>
                        <span class="text-xs font-bold text-emerald-400 bg-emerald-500/10 px-2.5 py-1 rounded-full">Advanced</span>
                    </div>
                    <h3 class="font-bold text-lg text-white mb-1">Discounted Cash Flow (DCF)</h3>
                    <p class="text-slate-400 text-xs leading-relaxed mb-4">Multi-stage FCF projections, terminal value estimates (Gordon Growth &amp; Exit Multiples), and WACC calculations.</p>
                    <div class="w-full bg-slate-700 h-2 rounded-full overflow-hidden">
                        <div class="bg-rutgers h-full rounded-full" style="width: 95%;"></div>
                    </div>
                </div>

                <!-- Skill 2 -->
                <div class="skill-card bg-slate-800/60 border border-slate-700/60 rounded-xl p-5 hover:border-rutgers/60 transition-all hover:-translate-y-1" data-category="valuation">
                    <div class="flex items-center justify-between mb-3">
                        <div class="w-10 h-10 rounded-lg bg-blue-500/10 text-blue-400 flex items-center justify-center text-lg">
                            <i class="fa-solid fa-scale-balanced"></i>
                        </div>
                        <span class="text-xs font-bold text-emerald-400 bg-emerald-500/10 px-2.5 py-1 rounded-full">Advanced</span>
                    </div>
                    <h3 class="font-bold text-lg text-white mb-1">Valuation &amp; Trading Comps</h3>
                    <p class="text-slate-400 text-xs leading-relaxed mb-4">Comparable company analysis, precedent transactions, EV/EBITDA benchmarking, and P/E multi-stage comparisons.</p>
                    <div class="w-full bg-slate-700 h-2 rounded-full overflow-hidden">
                        <div class="bg-blue-500 h-full rounded-full" style="width: 90%;"></div>
                    </div>
                </div>

                <!-- Skill 3 -->
                <div class="skill-card bg-slate-800/60 border border-slate-700/60 rounded-xl p-5 hover:border-rutgers/60 transition-all hover:-translate-y-1" data-category="tech">
                    <div class="flex items-center justify-between mb-3">
                        <div class="w-10 h-10 rounded-lg bg-emerald-500/10 text-emerald-400 flex items-center justify-center text-lg">
                            <i class="fa-solid fa-file-excel"></i>
                        </div>
                        <span class="text-xs font-bold text-emerald-400 bg-emerald-500/10 px-2.5 py-1 rounded-full">Advanced</span>
                    </div>
                    <h3 class="font-bold text-lg text-white mb-1">Advanced MS Excel</h3>
                    <p class="text-slate-400 text-xs leading-relaxed mb-4">Dynamic sensitivity tables, XLOOKUP, Index/Match, financial scenario modeling, and automated dashboard building.</p>
                    <div class="w-full bg-slate-700 h-2 rounded-full overflow-hidden">
                        <div class="bg-emerald-500 h-full rounded-full" style="width: 95%;"></div>
                    </div>
                </div>

                <!-- Skill 4 -->
                <div class="skill-card bg-slate-800/60 border border-slate-700/60 rounded-xl p-5 hover:border-rutgers/60 transition-all hover:-translate-y-1" data-category="tech">
                    <div class="flex items-center justify-between mb-3">
                        <div class="w-10 h-10 rounded-lg bg-amber-500/10 text-amber-400 flex items-center justify-center text-lg">
                            <i class="fa-brands fa-python"></i>
                        </div>
                        <span class="text-xs font-bold text-blue-400 bg-blue-500/10 px-2.5 py-1 rounded-full">Proficient</span>
                    </div>
                    <h3 class="font-bold text-lg text-white mb-1">Python &amp; Financial Analytics</h3>
                    <p class="text-slate-400 text-xs leading-relaxed mb-4">Pandas, NumPy, and Matplotlib for financial data manipulation, portfolio risk modeling, and backtesting.</p>
                    <div class="w-full bg-slate-700 h-2 rounded-full overflow-hidden">
                        <div class="bg-amber-500 h-full rounded-full" style="width: 80%;"></div>
                    </div>
                </div>

                <!-- Skill 5 -->
                <div class="skill-card bg-slate-800/60 border border-slate-700/60 rounded-xl p-5 hover:border-rutgers/60 transition-all hover:-translate-y-1" data-category="finance">
                    <div class="flex items-center justify-between mb-3">
                        <div class="w-10 h-10 rounded-lg bg-purple-500/10 text-purple-400 flex items-center justify-center text-lg">
                            <i class="fa-solid fa-chart-pie"></i>
                        </div>
                        <span class="text-xs font-bold text-emerald-400 bg-emerald-500/10 px-2.5 py-1 rounded-full">Advanced</span>
                    </div>
                    <h3 class="font-bold text-lg text-white mb-1">Portfolio Optimization</h3>
                    <p class="text-slate-400 text-xs leading-relaxed mb-4">Markowitz Efficient Frontier, Sharpe Ratio maximization, covariance matrix calculation, and asset allocation strategies.</p>
                    <div class="w-full bg-slate-700 h-2 rounded-full overflow-hidden">
                        <div class="bg-purple-500 h-full rounded-full" style="width: 88%;"></div>
                    </div>
                </div>

                <!-- Skill 6 -->
                <div class="skill-card bg-slate-800/60 border border-slate-700/60 rounded-xl p-5 hover:border-rutgers/60 transition-all hover:-translate-y-1" data-category="finance">
                    <div class="flex items-center justify-between mb-3">
                        <div class="w-10 h-10 rounded-lg bg-indigo-500/10 text-indigo-400 flex items-center justify-center text-lg">
                            <i class="fa-solid fa-file-invoice-dollar"></i>
                        </div>
                        <span class="text-xs font-bold text-emerald-400 bg-emerald-500/10 px-2.5 py-1 rounded-full">Advanced</span>
                    </div>
                    <h3 class="font-bold text-lg text-white mb-1">Financial Statement Analysis</h3>
                    <p class="text-slate-400 text-xs leading-relaxed mb-4">Integrated 3-statement modeling (Income Statement, Balance Sheet, Cash Flow), solvency metrics, and SEC 10-K analysis.</p>
                    <div class="w-full bg-slate-700 h-2 rounded-full overflow-hidden">
                        <div class="bg-indigo-500 h-full rounded-full" style="width: 92%;"></div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Requirement 3: Projects Showcase Section -->
    <section id="projects" class="py-20 bg-slate-950 border-b border-slate-800">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            
            <div class="text-center max-w-2xl mx-auto mb-12">
                <h2 class="text-3xl font-bold text-white mb-3 flex items-center justify-center gap-3">
                    <span class="w-8 h-1 bg-rutgers rounded-full"></span>
                    Projects Showcase
                    <span class="w-8 h-1 bg-rutgers rounded-full"></span>
                </h2>
                <p class="text-slate-400">Featured financial research projects, quantitative models, and corporate valuation studies conducted at Rutgers University.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                
                <!-- Project 1 -->
                <div class="bg-slate-900 border border-slate-800 rounded-2xl overflow-hidden shadow-xl flex flex-col hover:border-rutgers/50 transition-all hover:-translate-y-1 group">
                    <div class="p-6 flex-1 flex flex-col">
                        <div class="flex items-center justify-between mb-4">
                            <span class="text-xs font-bold uppercase tracking-wider text-rutgers bg-rutgers/10 px-3 py-1 rounded-full border border-rutgers/20">Valuation &amp; Equity</span>
                            <span class="text-xs text-slate-400"><i class="fa-regular fa-calendar"></i> 2026</span>
                        </div>
                        <h3 class="text-xl font-bold text-white mb-3 group-hover:text-rutgers transition-colors">
                            Rutgers Equity Valuation &amp; DCF Model
                        </h3>
                        <p class="text-slate-400 text-sm mb-6 flex-1">
                            Built a comprehensive 5-year Discounted Cash Flow (DCF) model and comparable company valuation to assess intrinsic target equity value.
                        </p>
                        
                        <div class="flex flex-wrap gap-2 mb-6">
                            <span class="text-xs bg-slate-800 text-slate-300 px-2.5 py-1 rounded">DCF Model</span>
                            <span class="text-xs bg-slate-800 text-slate-300 px-2.5 py-1 rounded">WACC</span>
                            <span class="text-xs bg-slate-800 text-slate-300 px-2.5 py-1 rounded">Sensitivity Analysis</span>
                        </div>

                        <div class="flex items-center gap-3 pt-4 border-t border-slate-800">
                            <button onclick="openProjectModal(1)" class="flex-1 bg-rutgers hover:bg-rutgers-dark text-white text-xs font-bold py-2.5 rounded-lg text-center transition-colors flex items-center justify-center gap-2">
                                <i class="fa-solid fa-expand"></i> View Analysis
                            </button>
                            <a href="https://github.com/WilliamGuzman/portfolio" target="_blank" class="bg-slate-800 hover:bg-slate-700 text-slate-200 text-xs font-bold p-2.5 rounded-lg transition-colors" title="View Code Repository">
                                <i class="fa-brands fa-github text-base"></i>
                            </a>
                        </div>
                    </div>
                </div>

                <!-- Project 2 -->
                <div class="bg-slate-900 border border-slate-800 rounded-2xl overflow-hidden shadow-xl flex flex-col hover:border-rutgers/50 transition-all hover:-translate-y-1 group">
                    <div class="p-6 flex-1 flex flex-col">
                        <div class="flex items-center justify-between mb-4">
                            <span class="text-xs font-bold uppercase tracking-wider text-purple-400 bg-purple-500/10 px-3 py-1 rounded-full border border-purple-500/20">Quantitative Risk</span>
                            <span class="text-xs text-slate-400"><i class="fa-regular fa-calendar"></i> 2026</span>
                        </div>
                        <h3 class="text-xl font-bold text-white mb-3 group-hover:text-purple-400 transition-colors">
                            Portfolio Optimization Engine
                        </h3>
                        <p class="text-slate-400 text-sm mb-6 flex-1">
                            Developed a quantitative asset allocation framework in Python and Excel to calculate covariance matrices and maximize historical Sharpe ratios.
                        </p>
                        
                        <div class="flex flex-wrap gap-2 mb-6">
                            <span class="text-xs bg-slate-800 text-slate-300 px-2.5 py-1 rounded">Python</span>
                            <span class="text-xs bg-slate-800 text-slate-300 px-2.5 py-1 rounded">Sharpe Ratio</span>
                            <span class="text-xs bg-slate-800 text-slate-300 px-2.5 py-1 rounded">Efficient Frontier</span>
                        </div>

                        <div class="flex items-center gap-3 pt-4 border-t border-slate-800">
                            <button onclick="openProjectModal(2)" class="flex-1 bg-rutgers hover:bg-rutgers-dark text-white text-xs font-bold py-2.5 rounded-lg text-center transition-colors flex items-center justify-center gap-2">
                                <i class="fa-solid fa-expand"></i> View Analysis
                            </button>
                            <a href="https://github.com/WilliamGuzman/portfolio-optimization" target="_blank" class="bg-slate-800 hover:bg-slate-700 text-slate-200 text-xs font-bold p-2.5 rounded-lg transition-colors" title="View Code Repository">
                                <i class="fa-brands fa-github text-base"></i>
                            </a>
                        </div>
                    </div>
                </div>

                <!-- Project 3 -->
                <div class="bg-slate-900 border border-slate-800 rounded-2xl overflow-hidden shadow-xl flex flex-col hover:border-rutgers/50 transition-all hover:-translate-y-1 group">
                    <div class="p-6 flex-1 flex flex-col">
                        <div class="flex items-center justify-between mb-4">
                            <span class="text-xs font-bold uppercase tracking-wider text-blue-400 bg-blue-500/10 px-3 py-1 rounded-full border border-blue-500/20">Financial Reporting</span>
                            <span class="text-xs text-slate-400"><i class="fa-regular fa-calendar"></i> 2025</span>
                        </div>
                        <h3 class="text-xl font-bold text-white mb-3 group-hover:text-blue-400 transition-colors">
                            SEC Solvency &amp; Health Analysis
                        </h3>
                        <p class="text-slate-400 text-sm mb-6 flex-1">
                            Analyzed multi-year SEC 10-K filings, liquidity ratios, and debt service coverage (DSCR) to evaluate corporate capital structures.
                        </p>
                        
                        <div class="flex flex-wrap gap-2 mb-6">
                            <span class="text-xs bg-slate-800 text-slate-300 px-2.5 py-1 rounded">10-K Filings</span>
                            <span class="text-xs bg-slate-800 text-slate-300 px-2.5 py-1 rounded">Leverage Ratios</span>
                            <span class="text-xs bg-slate-800 text-slate-300 px-2.5 py-1 rounded">Cash Flow Ratios</span>
                        </div>

                        <div class="flex items-center gap-3 pt-4 border-t border-slate-800">
                            <button onclick="openProjectModal(3)" class="flex-1 bg-rutgers hover:bg-rutgers-dark text-white text-xs font-bold py-2.5 rounded-lg text-center transition-colors flex items-center justify-center gap-2">
                                <i class="fa-solid fa-expand"></i> View Analysis
                            </button>
                            <a href="https://github.com/WilliamGuzman/financial-analysis" target="_blank" class="bg-slate-800 hover:bg-slate-700 text-slate-200 text-xs font-bold p-2.5 rounded-lg transition-colors" title="View Code Repository">
                                <i class="fa-brands fa-github text-base"></i>
                            </a>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Interactive Bonus Feature: Live DCF Intrinsic Valuation Calculator -->
    <section id="dcf-calculator" class="py-20 bg-slate-900 border-b border-slate-800">
        <div class="max-w-5xl mx-auto px-4 sm:px-6 lg:px-8">
            
            <div class="bg-slate-950 border border-slate-800 rounded-3xl p-6 sm:p-10 shadow-2xl">
                <div class="flex flex-col md:flex-row items-start md:items-center justify-between gap-4 mb-8 pb-6 border-b border-slate-800">
                    <div>
                        <span class="text-xs font-bold uppercase tracking-widest text-rutgers block mb-1">Interactive Financial Model</span>
                        <h2 class="text-2xl sm:text-3xl font-extrabold text-white">Live DCF Intrinsic Valuation Calculator</h2>
                    </div>
                    <span class="text-xs bg-slate-800 text-slate-300 px-3 py-1.5 rounded-lg border border-slate-700 font-semibold">
                        <i class="fa-solid fa-bolt text-amber-400 mr-1.5"></i> Real-Time Calculation
                    </span>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-12 gap-8">
                    <!-- Interactive Sliders -->
                    <div class="lg:col-span-6 space-y-6">
                        
                        <div>
                            <div class="flex justify-between text-sm font-semibold text-slate-300 mb-2">
                                <span>Year 1 Free Cash Flow ($M):</span>
                                <span id="fcf-val" class="text-rutgers font-mono font-bold">$100M</span>
                            </div>
                            <input type="range" id="fcf-input" min="20" max="500" value="100" step="5" class="w-full accent-rutgers bg-slate-800 rounded-lg cursor-pointer">
                        </div>

                        <div>
                            <div class="flex justify-between text-sm font-semibold text-slate-300 mb-2">
                                <span>5-Yr FCF Growth Rate (%):</span>
                                <span id="growth-val" class="text-rutgers font-mono font-bold">8%</span>
                            </div>
                            <input type="range" id="growth-input" min="1" max="25" value="8" step="0.5" class="w-full accent-rutgers bg-slate-800 rounded-lg cursor-pointer">
                        </div>

                        <div>
                            <div class="flex justify-between text-sm font-semibold text-slate-300 mb-2">
                                <span>Discount Rate / WACC (%):</span>
                                <span id="wacc-val" class="text-rutgers font-mono font-bold">9.5%</span>
                            </div>
                            <input type="range" id="wacc-input" min="5" max="18" value="9.5" step="0.5" class="w-full accent-rutgers bg-slate-800 rounded-lg cursor-pointer">
                        </div>

                        <div>
                            <div class="flex justify-between text-sm font-semibold text-slate-300 mb-2">
                                <span>Terminal Growth Rate (%):</span>
                                <span id="terminal-val" class="text-rutgers font-mono font-bold">2.5%</span>
                            </div>
                            <input type="range" id="terminal-input" min="1" max="5" value="2.5" step="0.25" class="w-full accent-rutgers bg-slate-800 rounded-lg cursor-pointer">
                        </div>

                    </div>

                    <!-- Computed Outputs -->
                    <div class="lg:col-span-6 bg-slate-900 border border-slate-800 rounded-2xl p-6 flex flex-col justify-between">
                        <div>
                            <div class="text-xs uppercase font-bold text-slate-400 tracking-wider mb-2">Implied Enterprise Value</div>
                            <div id="ev-result" class="text-4xl sm:text-5xl font-black text-emerald-400 font-mono tracking-tight mb-6">$1846.5M</div>

                            <div class="space-y-3 text-sm border-t border-slate-800 pt-4">
                                <div class="flex justify-between text-slate-300">
                                    <span>PV of 5-Yr Cash Flows:</span>
                                    <span id="pv-cashflows" class="font-mono text-white font-semibold">$479.8M</span>
                                </div>
                                <div class="flex justify-between text-slate-300">
                                    <span>PV of Terminal Value:</span>
                                    <span id="pv-terminal" class="font-mono text-white font-semibold">$1366.7M</span>
                                </div>
                                <div class="flex justify-between text-slate-300">
                                    <span>Implied Terminal Multiple:</span>
                                    <span id="implied-multiple" class="font-mono text-rutgers font-semibold">14.6x</span>
                                </div>
                            </div>
                        </div>

                        <div class="mt-6 p-3 bg-slate-950 rounded-lg border border-slate-800/80 text-xs text-slate-400">
                            <i class="fa-solid fa-info-circle text-rutgers mr-1"></i> Calculation: Gordon Growth Model EV = PV(5-Yr FCF) + [ (FCF₅ × (1+g)) / (WACC - g) ] / (1+WACC)⁵
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Contact & Homework Links -->
    <section id="contact" class="py-20 bg-slate-950 border-b border-slate-800">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            
            <h2 class="text-3xl font-bold text-white mb-3">Connect With Me</h2>
            <p class="text-slate-400 max-w-xl mx-auto mb-10">Feel free to reach out regarding financial analyst opportunities or academic collaboration at Rutgers.</p>

            <div class="grid grid-cols-1 sm:grid-cols-3 gap-6 mb-12">
                <a href="mailto:william.guzman@rutgers.edu" class="bg-slate-900 border border-slate-800 p-6 rounded-2xl hover:border-rutgers transition-all group">
                    <div class="w-12 h-12 rounded-xl bg-rutgers/10 text-rutgers flex items-center justify-center text-xl mx-auto mb-4 group-hover:scale-110 transition-transform">
                        <i class="fa-solid fa-envelope"></i>
                    </div>
                    <div class="font-bold text-white text-sm mb-1">Email</div>
                    <div class="text-slate-400 text-xs truncate">william.guzman@rutgers.edu</div>
                </a>

                <a href="https://linkedin.com" target="_blank" class="bg-slate-900 border border-slate-800 p-6 rounded-2xl hover:border-rutgers transition-all group">
                    <div class="w-12 h-12 rounded-xl bg-blue-500/10 text-blue-400 flex items-center justify-center text-xl mx-auto mb-4 group-hover:scale-110 transition-transform">
                        <i class="fa-brands fa-linkedin"></i>
                    </div>
                    <div class="font-bold text-white text-sm mb-1">LinkedIn</div>
                    <div class="text-slate-400 text-xs">/in/william-guzman</div>
                </a>

                <a href="https://github.com/WilliamGuzman" target="_blank" class="bg-slate-900 border border-slate-800 p-6 rounded-2xl hover:border-rutgers transition-all group">
                    <div class="w-12 h-12 rounded-xl bg-purple-500/10 text-purple-400 flex items-center justify-center text-xl mx-auto mb-4 group-hover:scale-110 transition-transform">
                        <i class="fa-brands fa-github"></i>
                    </div>
                    <div class="font-bold text-white text-sm mb-1">GitHub</div>
                    <div class="text-slate-400 text-xs">@WilliamGuzman</div>
                </a>
            </div>

        </div>
    </section>

    <!-- Code Copy / Export Section -->
    <section id="export-section" class="py-16 bg-slate-900 border-b border-slate-800">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="bg-slate-950 border border-slate-800 rounded-2xl p-6 sm:p-8">
                <div class="flex flex-col sm:flex-row items-start sm:items-center justify-between gap-4 mb-6">
                    <div>
                        <h3 class="text-xl font-bold text-white"><i class="fa-solid fa-download text-rutgers mr-2"></i>Download or Copy Your Code</h3>
                        <p class="text-xs text-slate-400">Save this entire single file as <code>index.html</code> to upload to your public GitHub repository.</p>
                    </div>
                    <div class="flex gap-3">
                        <button onclick="downloadSourceCode()" class="bg-rutgers hover:bg-rutgers-dark text-white px-4 py-2.5 rounded-lg text-xs font-bold uppercase tracking-wider flex items-center gap-2">
                            <i class="fa-solid fa-file-arrow-down"></i> Download index.html
                        </button>
                        <button onclick="copyFullSourceCode()" class="bg-slate-800 hover:bg-slate-700 text-white px-4 py-2.5 rounded-lg text-xs font-bold uppercase tracking-wider flex items-center gap-2 border border-slate-700">
                            <i class="fa-solid fa-copy"></i> Copy Code
                        </button>
                    </div>
                </div>

                <div class="bg-slate-900 p-4 rounded-xl border border-slate-800 font-mono text-xs text-slate-400 max-h-48 overflow-y-auto" id="exportPreview">&lt;html lang="en" class="scroll-smooth"&gt;&lt;head&gt;&lt;script data-bard-client-injected="true"&gt;(function(firebaseConfig, initialAuthToken, appId) {
        window.__firebase_config = firebaseConfig;
        window.__initial_auth_token = initialAuthToken;
        window.__app_id = appId;
            })("\n{\n  \"apiKey\": \"AIzaSyCqyCcs2R2e7AegGjvFAwG98wlamtbHvZY\",\n  \"authDomain\": \"bard-frontend.firebaseapp.com\",\n  \"projectId\": \"bard-frontend\",\n  \"storageBucket\": \"bard-frontend.firebasestorage.app\",\n  \"messagingSenderId\": \"175205271074\",\n  \"appId\": \"1:175205271074:web:2b7bd4d34d33bf38e6ec7b\"\n}\n","eyJhbGciOiJSUzI1NiIsImtpZCI6IjExNjRiNzdiNDMzZDdhMDAyMWI4NjE4YjhjYTU3ZTMyZGI5MWUxMTMiLCJ0eXAiOiJKV1QifQ.eyJzdWIiOiJmaXJlYmFzZS1hZG1pbnNkay1mYnN2Y0BiYXJkLWZyb250ZW5kLmlhbS5nc2Vydmlj

... [Full Code Downloadable Below]</div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-8 bg-slate-950 text-center text-slate-500 text-xs">
        <p>© 2026 William Guzman | Rutgers University Senior Portfolio</p>
    </footer>

    <!-- Project Detail Modal -->
    <div id="projectModal" class="fixed inset-0 z-50 hidden flex items-center justify-center p-4 bg-slate-950/80 backdrop-blur-md">
        <div class="bg-slate-900 border border-slate-800 rounded-2xl max-w-2xl w-full p-6 sm:p-8 relative max-h-[90vh] overflow-y-auto shadow-2xl">
            <button onclick="closeProjectModal()" class="absolute top-4 right-4 text-slate-400 hover:text-white p-2">
                <i class="fa-solid fa-xmark text-xl"></i>
            </button>
            <div id="modalContent"></div>
        </div>
    </div>

    <!-- Notification Toast -->
    <div id="toast" class="fixed bottom-5 right-5 z-50 bg-rutgers text-white px-5 py-3 rounded-xl shadow-2xl font-semibold text-xs transition-all duration-300 transform translate-y-20 opacity-0 flex items-center gap-2">
        <i class="fa-solid fa-circle-check"></i> <span id="toast-msg">Copied to clipboard!</span>
    </div>

    <script>
        // DCF Calculator Script
        const fcfInput = document.getElementById('fcf-input');
        const growthInput = document.getElementById('growth-input');
        const waccInput = document.getElementById('wacc-input');
        const terminalInput = document.getElementById('terminal-input');

        function calculateDCF() {
            const fcf = parseFloat(fcfInput.value);
            const growth = parseFloat(growthInput.value) / 100;
            const wacc = parseFloat(waccInput.value) / 100;
            const termGrowth = parseFloat(terminalInput.value) / 100;

            document.getElementById('fcf-val').innerText = `$${fcf}M`;
            document.getElementById('growth-val').innerText = `${growthInput.value}%`;
            document.getElementById('wacc-val').innerText = `${waccInput.value}%`;
            document.getElementById('terminal-val').innerText = `${terminalInput.value}%`;

            if (wacc <= termGrowth) {
                document.getElementById('ev-result').innerText = "WACC Must Be > Term Rate";
                return;
            }

            let pvCashFlows = 0;
            let currentFCF = fcf;

            for (let i = 1; i <= 5; i++) {
                currentFCF *= (1 + growth);
                pvCashFlows += currentFCF / Math.pow(1 + wacc, i);
            }

            const terminalValue = (currentFCF * (1 + termGrowth)) / (wacc - termGrowth);
            const pvTerminalValue = terminalValue / Math.pow(1 + wacc, 5);
            const enterpriseValue = pvCashFlows + pvTerminalValue;
            const impliedMultiple = terminalValue / currentFCF;

            document.getElementById('ev-result').innerText = `$${enterpriseValue.toFixed(1)}M`;
            document.getElementById('pv-cashflows').innerText = `$${pvCashFlows.toFixed(1)}M`;
            document.getElementById('pv-terminal').innerText = `$${pvTerminalValue.toFixed(1)}M`;
            document.getElementById('implied-multiple').innerText = `${impliedMultiple.toFixed(1)}x`;
        }

        [fcfInput, growthInput, waccInput, terminalInput].forEach(input => {
            input.addEventListener('input', calculateDCF);
        });

        calculateDCF();

        // Skill Filters Script
        const filterBtns = document.querySelectorAll('.skill-filter-btn');
        const skillCards = document.querySelectorAll('.skill-card');

        filterBtns.forEach(btn => {
            btn.addEventListener('click', () => {
                filterBtns.forEach(b => {
                    b.classList.remove('bg-rutgers', 'text-white', 'active');
                    b.classList.add('bg-slate-800', 'text-slate-300');
                });
                btn.classList.add('bg-rutgers', 'text-white', 'active');
                btn.classList.remove('bg-slate-800', 'text-slate-300');

                const filter = btn.getAttribute('data-filter');

                skillCards.forEach(card => {
                    if (filter === 'all' || card.getAttribute('data-category') === filter) {
                        card.style.display = 'block';
                    } else {
                        card.style.display = 'none';
                    }
                });
            });
        });

        // Project Modal Data
        const projectData = {
            1: {
                title: "Rutgers Equity Valuation & DCF Model",
                category: "Valuation & Equity Research",
                description: "Built a comprehensive Discounted Cash Flow (DCF) model and comparable company valuation to assess intrinsic target equity value for academic investment research.",
                highlights: [
                    "Forecasted 5-year Free Cash Flows based on historical operating metrics and revenue growth.",
                    "Calculated Weighted Average Cost of Capital (WACC) using CAPM beta and treasury benchmarks.",
                    "Built 2-way sensitivity tables analyzing valuation ranges under varying exit multiples and discount rates."
                ],
                repo: "https://github.com/WilliamGuzman/portfolio"
            },
            2: {
                title: "Portfolio Optimization Engine",
                category: "Quantitative Risk & Asset Management",
                description: "Developed a quantitative asset allocation framework in Python and Excel to calculate covariance matrices and maximize historical Sharpe ratios.",
                highlights: [
                    "Calculated historical variance-covariance matrices across equity indices, treasuries, and commodities.",
                    "Executed Markowitz Efficient Frontier optimization maximizing portfolio Sharpe ratios.",
                    "Backtested risk-adjusted performance against benchmark S&P 500 returns."
                ],
                repo: "https://github.com/WilliamGuzman/portfolio-optimization"
            },
            3: {
                title: "SEC Solvency & Health Analysis",
                category: "Financial Statement Analysis & Advisory",
                description: "Analyzed multi-year SEC 10-K filings, liquidity ratios, and debt service coverage (DSCR) to evaluate corporate capital structures.",
                highlights: [
                    "Evaluated Interest Coverage, Debt-to-EBITDA, and Quick Ratios across three balance sheet cycles.",
                    "Constructed cash flow bridges identifying working capital bottlenecks.",
                    "Delivered strategic recommendations on debt refinancing and capital reallocation."
                ],
                repo: "https://github.com/WilliamGuzman/financial-analysis"
            }
        };

        function openProjectModal(id) {
            const proj = projectData[id];
            const content = document.getElementById('modalContent');
            
            content.innerHTML = `
                <div class="text-xs font-bold uppercase tracking-wider text-rutgers mb-1">${proj.category}</div>
                <h2 class="text-2xl font-bold text-white mb-4">${proj.title}</h2>
                <p class="text-slate-300 text-sm mb-6">${proj.description}</p>
                <h4 class="font-bold text-white text-sm mb-3">Key Project Highlights:</h4>
                <ul class="space-y-2 text-slate-300 text-xs mb-8">
                    ${proj.highlights.map(h => `<li class="flex items-start gap-2"><i class="fa-solid fa-check text-rutgers mt-0.5"></i> <span>${h}</span></li>`).join('')}
                </ul>
                <div class="flex gap-3 pt-4 border-t border-slate-800">
                    <a href="${proj.repo}" target="_blank" class="flex-1 bg-rutgers hover:bg-rutgers-dark text-white font-bold py-2.5 rounded-lg text-center text-xs transition-colors flex items-center justify-center gap-2">
                        <i class="fa-brands fa-github"></i> Open Code Repository
                    </a>
                </div>
            `;
            
            document.getElementById('projectModal').classList.remove('hidden');
        }

        function closeProjectModal() {
            document.getElementById('projectModal').classList.add('hidden');
        }

        function showToast(msg) {
            const toast = document.getElementById('toast');
            document.getElementById('toast-msg').innerText = msg;
            toast.classList.remove('translate-y-20', 'opacity-0');
            setTimeout(() => {
                toast.classList.add('translate-y-20', 'opacity-0');
            }, 3000);
        }

        function copyFullSourceCode() {
            const fullCode = "<!DOCTYPE html>\n" + document.documentElement.outerHTML;
            const temp = document.createElement("textarea");
            temp.value = fullCode;
            document.body.appendChild(temp);
            temp.select();
            document.execCommand("copy");
            document.body.removeChild(temp);
            showToast("Full HTML source code copied!");
        }

        function downloadSourceCode() {
            const fullCode = "<!DOCTYPE html>\n" + document.documentElement.outerHTML;
            const blob = new Blob([fullCode], { type: "text/html" });
            const url = URL.createObjectURL(blob);
            const a = document.createElement("a");
            a.href = url;
            a.download = "index.html";
            document.body.appendChild(a);
            a.click();
            document.body.removeChild(a);
            URL.revokeObjectURL(url);
            showToast("index.html file downloaded!");
        }

        // Initialize preview box content
        document.addEventListener("DOMContentLoaded", () => {
            const exportPreview = document.getElementById('exportPreview');
            if(exportPreview) {
                exportPreview.textContent = document.documentElement.outerHTML.substring(0, 800) + "\n\n... [Full Code Downloadable Below]";
            }
        });

        // Mobile drawer script
        const mobileMenuBtn = document.getElementById('mobileMenuBtn');
        const mobileMenu = document.getElementById('mobileMenu');
        
        mobileMenuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        document.querySelectorAll('.mobile-nav-link').forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
            });
        });
    </script>

</body></html>
