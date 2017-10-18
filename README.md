# Vue private project snippets

Vue.js 2.x + ES6 snippets for Atom

## Need this package
(language-vue)[https://atom.io/packages/language-vue]

### import
```Javascript
i-cal              // import calendar from '../../../components/ui/Calendar.vue'
i-timePicker       // import timePicker from '../../../components/ui/TimePicker.vue'
i-useTimePicker    // import useTimePicker from '../../../components/ui/UseTimePicker.vue'
i-numberInput      // import numberInput from '../../../components/ui/NumberInput.vue'
i-loading          // import numberInput from '../../../components/ui/Loading.vue'
i-modal            // import numberInput from '../../../components/ui/Modal.vue'
i-select           // import numberInput from '../../../components/ui/Select.vue'
i-rsvProperty      // import { ${1:func} } from '../../../common/utils/rsvProperty'
i-objectAssign     // import objectAssign from 'object-assign'
i-lodash           // import objectAssign from 'lodash'
i-moment           // import objectAssign from 'moment'
```

### script
```Javascript
s-cptd             // computed: objectAssign({...},{})
s-gtst             // computed getter setter: ${something}: { get() {}, set() {} }
s-func             // methods func: ${something} () { ... }
s-dispatch         // script vuex: dispatch: this.$store.dispatch('namespaced/something', value)
s-commit           // script vuex: commit: this.$store.commit('namespaced/SOME_THING', val)
```

### template tag
```Javascript
t-calendar         // components: Calendar
t-timePicker       // components: TimePicker
t-useTimePicker    // components: UseTimePicker
t-checkBox         // components: CustomCheckBox
t-numberInput      // components: NumberInput
```
