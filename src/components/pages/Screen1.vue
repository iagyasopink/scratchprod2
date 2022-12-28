<template>
  <NucGridPage v-bind:gap="{'row':0,'col':0}" v-bind:designMode="false" overflow="auto" v-bind:rows="[1]"
    v-bind:columns="[1]"
    v-bind:schema="{'r0-c0':{'row':0,'col':0,'rowSpan':1,'colSpan':1,'showIn':['xs','sm','md','lg']}}"
    v-bind:minNsLimit="0"
    v-bind:style="{'background':'#FFFFFF','paddingTop':'0px','paddingBottom':'0px','paddingLeft':'0px','paddingRight':'0px'}">
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="hidden" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left" v-bind:row="0"
      v-bind:col="0" v-bind:rowSpan="1" v-bind:colSpan="1" v-bind:marginLeft="0" v-bind:marginRight="0"
      v-bind:marginTop="0" v-bind:marginBottom="0" id="228403f1-ca90-4309-9b5b-0f85e04ed530"
      v-bind:style="{'height':'auto','background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r0-c0" area="r0-c0">
      <WDangerLinkAlert v-bind:fade="false" v-bind:pill="false" show="false" size="md" v-bind:isLink="true"
        v-bind:squared="false" hrefLink="" alertLabel="This alert will dismiss after time lapse" background="#17a2b8"
        buttonLabel="Show alert with count-down timer" v-bind:dismissible="false" alertVariant="danger"
        dismissLabel="Close" ncTypography="body1" verticalWidth="60px" buttonsVariant="danger"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'buttonLabel','displayName':'ButtonLabel'},{'type':'string','propName':'alertLabel','displayName':'AlertLabel'}]}"
        verticalHeight="60px" horizontalWidth="" progressVariant="danger" v-bind:dismissCountDown="5"
        horizontalHeight="" ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF"
        ncClickBorderColor="#dc3545" ncFocusBorderColor="#dc3545" ncHoverBorderColor="#dc3545"
        ncClickBackgroundColor="#dc3545" ncFocusBackgroundColor="#dc3545" ncHoverBackgroundColor="#dc3545"
        position="absolute" top="38.86895475819033%" left="31.215217391304346%"
        id="53345b52-02c2-45e5-b552-6a07b81cd2c8"
        v-bind:style="{'color':'#FFFFFF','width':'','height':'','fontSize':'9.008px','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'left','fontFamily':'Roboto-Regular,Roboto','fontWeight':'225.2','lineHeight':'13.511999999999999px','marginLeft':'0px','paddingTop':'3.3779999999999997px','textShadow':'','visibility':'visible','borderColor':'#f8d7da','borderStyle':'none','marginRight':'0px','paddingLeft':'6.755999999999999px','marginBottom':'0px','paddingRight':'6.755999999999999px','paddingBottom':'3.3779999999999997px','borderTopWidth':'0px','textDecoration':'none','borderLeftWidth':'0px','borderRightWidth':'0px','horizontalHeight':'','borderBottomWidth':'0px','borderTopLeftRadius':'0px','borderTopRightRadius':'0px','borderBottomLeftRadius':'0px','borderBottomRightRadius':'0px','zIndex':2}"/>
      <WDarkLinkAlert v-bind:fade="false" v-bind:pill="false" show="false" size="md" v-bind:isLink="true"
        v-bind:squared="false" hrefLink="" alertLabel="This alert will dismiss after time lapse" background="#17a2b8"
        buttonLabel="Show alert with count-down timer" v-bind:dismissible="false" alertVariant="dark"
        dismissLabel="Close" ncTypography="body1" verticalWidth="60px" buttonsVariant="dark"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'buttonLabel','displayName':'ButtonLabel'},{'type':'string','propName':'alertLabel','displayName':'AlertLabel'}]}"
        verticalHeight="60px" horizontalWidth="" progressVariant="dark" v-bind:dismissCountDown="5" horizontalHeight=""
        ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF" ncClickBorderColor="#23272b"
        ncFocusBorderColor="#23272b" ncHoverBorderColor="#23272b" ncClickBackgroundColor="#23272b"
        ncFocusBackgroundColor="#23272b" ncHoverBackgroundColor="#23272b" position="absolute" top="48.69422776911077%"
        left="53.39021739130435%" id="487e86f5-730c-43a8-b3ba-566a00211e87"
        v-bind:style="{'color':'#FFFFFF','width':'','height':'','fontSize':'9.008px','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'left','fontFamily':'Roboto-Regular,Roboto','fontWeight':'225.2','lineHeight':'13.511999999999999px','marginLeft':'0px','paddingTop':'3.3779999999999997px','textShadow':'','visibility':'visible','borderColor':'#c6c8ca','borderStyle':'none','marginRight':'0px','paddingLeft':'6.755999999999999px','marginBottom':'0px','paddingRight':'6.755999999999999px','paddingBottom':'3.3779999999999997px','borderTopWidth':'0px','textDecoration':'none','borderLeftWidth':'0px','borderRightWidth':'0px','horizontalHeight':'','borderBottomWidth':'0px','borderTopLeftRadius':'0px','borderTopRightRadius':'0px','borderBottomLeftRadius':'0px','borderBottomRightRadius':'0px','zIndex':3}"/>
    </NucGridCell>
  </NucGridPage>
</template>
<script>
export default {
  name: 'Screen1',
  data() {
    return {};
  },
  props: {},
  created() {},
  mounted() {},
  computed: {},
  methods: {},
  watch: {},
};
</script>

<style scoped></style>