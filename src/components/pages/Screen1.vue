<template>
  <NucGridPage v-bind:gap="{'col':0,'row':0}" v-bind:rows="[1]"
    v-bind:schema="{'r0-c0':{'col':0,'row':0,'showIn':['xs','sm','md','lg'],'colSpan':1,'rowSpan':1}}"
    v-bind:columns="[1]" overflow="auto" v-bind:designMode="false" v-bind:minNsLimit="1330"
    v-bind:style="{'background':'#FFFFFF','paddingTop':'0px','paddingLeft':'0px','paddingRight':'0px','paddingBottom':'0px'}">
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="hidden" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left"
      id="4344b866-90e8-4ea5-9f91-1918c8954b6b" v-bind:col="0" v-bind:row="0" v-bind:colSpan="1" v-bind:rowSpan="1"
      v-bind:marginTop="0" v-bind:marginLeft="0" v-bind:marginRight="0" v-bind:marginBottom="0"
      v-bind:style="{'height':'auto','background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r0-c0" area="r0-c0">
      <NucGroupElement top="0%" left="0%" v-bind:snapX="false" v-bind:snapY="false" v-bind:isLock="true" bgColor=""
        position="absolute" ncTooltipText="" id="51ea2237-9c87-49ec-b83d-8b014f10053e"
        v-bind:style="{'color':'#FFFFFF','width':'1330px','height':'776.15px','zIndex':2,'fontSize':'10.686602250000002px','maxWidth':'','minWidth':'7.1244015','tabIndex':'-0.71244015','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'7.1244015','textAlign':'center','background':'','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','lineHeight':'0.8905501875','marginLeft':'0px','paddingTop':'','textShadow':'','visibility':'visible','borderColor':'#767676','borderStyle':'solid','marginRight':'0px','paddingLeft':'','marginBottom':'0px','paddingRight':'','paddingBottom':'','borderTopWidth':'0.71244015px','textDecoration':'none','borderLeftWidth':'0.71244015px','borderRightWidth':'0.71244015px','borderBottomWidth':'0.71244015px','borderTopLeftRadius':'0px','borderTopRightRadius':'0px','borderBottomLeftRadius':'0px','borderBottomRightRadius':'0px'}">
        <WImage top="0%" left="0%" v-bind:blank="false" v-bind:snapX="false" v-bind:snapY="false" v-bind:rounded="false"
          stretch="none"
          imageUrl="https://images03.nicepage.com/a1389d7bc73adea1e1c1fb7e/712b89659f255a38a470337b/pexels-photo-459762.jpeg"
          position="absolute" v-bind:isEnabled="true" v-bind:thumbnail="false" blankColor="black"
          v-bind:aspectRatio="true" dataLoading="static" ncTooltipText="Please write a text to display in tooltip..."
          v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':true,'structure':[{'type':'string','update':{'type':'dataModelForDynamicType'},'propName':'imageUrl','displayName':'Value'}]}"
          ncClickBorderColor="black" ncHoverBorderColor="black" dataModelForDynamicType="string"
          id="c563d567-5dc0-460e-8cf9-510700c1b094"
          v-bind:style="{'width':'1328.1px','height':'703.9499999999999px','zIndex':4,'maxWidth':'','minWidth':'','boxShadow':'','marginTop':'0px','maxHeight':'','minHeight':'','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','borderColor':'#4B74FF','borderStyle':'solid','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'0px','borderTopRightRadius':'0px','borderBottomLeftRadius':'0px','borderBottomRightRadius':'0px'}"/>
        <WLabel top="26.530651231207138%" left="8.298309934722347%" text="Gadgets for" v-bind:snapX="false"
          v-bind:snapY="false" theme="theme--light01" position="absolute" ncTypography="custom" ncTooltipText=""
          v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
          id="dc53a337-0e18-4790-8f2a-3a066bd7dade"
          v-bind:style="{'color':'#ffffff','width':'291.65px','height':'60.8px','zIndex':5,'fontSize':'46.30860975px','maxWidth':'','minWidth':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'left','fontFamily':'OpenSans-Bold,Open Sans','fontWeight':'normal','lineHeight':'0.9974162099999998','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'none'}"/>
        <WLabel top="34.23309836284792%" left="8.655995707770723%" text="your game" v-bind:snapX="false"
          v-bind:snapY="false" theme="theme--light01" position="absolute" ncTypography="custom" ncTooltipText=""
          v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
          id="6cf1ad41-37a3-42d5-91dd-afbbc89a0cef"
          v-bind:style="{'color':'#ffffff','width':'270.75px','height':'61.75px','zIndex':6,'fontSize':'46.30860975px','maxWidth':'','minWidth':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'left','fontFamily':'OpenSans-Bold,Open Sans','fontWeight':'normal','lineHeight':'0.9974162099999998','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'none'}"/>
        <WOutlinePrimaryDefaultButton tag="button" top="52.90123833550347%" left="8.35069497426351%" v-bind:pill="false"
          size="md" text="VIEW ALL" type="button" v-bind:block="false" color="#FFFFFF" v-bind:snapX="false"
          v-bind:snapY="false" theme="theme--light01" v-bind:squared="false" variant="outline-primary"
          position="absolute" v-bind:isEnabled="true" background="" borderColor="#FFFFFF" borderWidth="3px"
          ncTypography="custom" v-bind:resetTrigger="false" ncTooltipText="" verticalWidth="60px"
          v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
          verticalHeight="60px" horizontalWidth="72.4479px" horizontalHeight="37.5347px" ncClickFontColor="#FFFFFF"
          ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF" ncClickBorderColor="#4285f4"
          ncDisableFontColor="#FFFFFF" ncFocusBorderColor="#4285f4" ncHoverBorderColor="#4285f4"
          ncDisableBorderColor="transparent" ncClickBackgroundColor="#4285f4" ncFocusBackgroundColor="#4285f4"
          ncHoverBackgroundColor="#4285f4" ncDisableBackgroundColor="#969696" id="8a341041-b2d9-49e6-8d76-2a6a14c288f5"
          v-bind:style="{'width':'138.92582925px','height':'47.02104990000001px','zIndex':7,'fontSize':'14.248803px','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'center','fontFamily':'OpenSans-Bold,Open Sans','fontWeight':'bold','lineHeight':'0.9974162099999998','marginLeft':'0px','paddingTop':'','textShadow':'','visibility':'visible','borderStyle':'solid','marginRight':'0px','paddingLeft':'','marginBottom':'0px','paddingRight':'','paddingBottom':'','borderTopWidth':'2.1373204500000003px','textDecoration':'none','borderLeftWidth':'2.1373204500000003px','borderRightWidth':'2.1373204500000003px','horizontalHeight':'26.741227298205004px','borderBottomWidth':'2.1373204500000003px','borderTopLeftRadius':'2.8497606px','borderTopRightRadius':'2.8497606px','borderBottomLeftRadius':'2.8497606px','borderBottomRightRadius':'2.8497606px'}"/>
        <WImage top="0%" left="68.6695278969957%" v-bind:blank="false" v-bind:snapX="false" v-bind:snapY="false"
          v-bind:rounded="false" stretch="none"
          imageUrl="https://mobwallpapershd.com/wp-content/uploads/2021/07/Gaming-Wallpapers-1-576x1024.jpg"
          position="absolute" v-bind:isEnabled="true" v-bind:thumbnail="false" blankColor="black"
          v-bind:aspectRatio="true" borderWidth="5px" dataLoading="static"
          ncTooltipText="Please write a text to display in tooltip..."
          v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':true,'structure':[{'type':'string','update':{'type':'dataModelForDynamicType'},'propName':'imageUrl','displayName':'Value'}]}"
          ncClickBorderColor="black" ncHoverBorderColor="black" dataModelForDynamicType="string"
          id="e60db5a5-a670-4163-8e9e-4dc924a23b7c"
          v-bind:style="{'width':'416.09999999999997px','height':'688.75px','zIndex':8,'maxWidth':'','minWidth':'','boxShadow':'','marginTop':'0px','maxHeight':'','minHeight':'','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','borderColor':'#FFFFFF','borderStyle':'solid','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'3.56220075px','borderLeftWidth':'3.56220075px','borderRightWidth':'0px','borderBottomWidth':'3.56220075px','borderTopLeftRadius':'0px','borderTopRightRadius':'0px','borderBottomLeftRadius':'0px','borderBottomRightRadius':'0px'}"/>
        <WLabel top="3.423309836284792%" left="69.82026289904319%" text="Innovation in" v-bind:snapX="false"
          v-bind:snapY="false" theme="theme--light01" position="absolute" ncTypography="custom" ncTooltipText=""
          v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
          id="2c501832-3ab7-46a5-877f-374f4dad4af6"
          v-bind:style="{'color':'#ffffff','width':'302.09999999999997px','height':'47.5px','zIndex':9,'fontSize':'49.870810500000005px','maxWidth':'','minWidth':'','fontStyle':'','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'left','fontFamily':'Roboto-Regular,Roboto','fontWeight':'bold','lineHeight':'0.71244015','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':''}"/>
        <WLabel top="11.370279099088773%" left="69.82026289904319%" text="the game" v-bind:snapX="false"
          v-bind:snapY="false" theme="theme--light01" position="absolute" ncTypography="custom" ncTooltipText=""
          v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
          id="b836fd66-ee86-45a1-9b63-29054ff9e002"
          v-bind:style="{'color':'#ffffff','width':'240.35px','height':'54.15px','zIndex':10,'fontSize':'49.870810500000005px','maxWidth':'','minWidth':'','fontStyle':'','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'left','fontFamily':'Roboto-Regular,Roboto','fontWeight':'bold','lineHeight':'0.71244015','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':''}"/>
        <WLabel top="20.295336886545552%" left="69.82026289904319%" text="industry" v-bind:snapX="false"
          v-bind:snapY="false" theme="theme--light01" position="absolute" ncTypography="custom" ncTooltipText=""
          v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
          id="4ba62f4c-6a29-4bbc-9875-54ae3b4364e1"
          v-bind:style="{'color':'#ffffff','width':'211.85px','height':'58.9px','zIndex':11,'fontSize':'49.870810500000005px','maxWidth':'','minWidth':'','fontStyle':'','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'left','fontFamily':'Roboto-Regular,Roboto','fontWeight':'bold','lineHeight':'0.71244015','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':''}"/>
        <WBoxColorAdvertisement top="88.95705521472392%" left="0%" v-bind:blank="true" v-bind:snapX="false"
          v-bind:snapY="false" imgSrc="" v-bind:overlay="true" cardText="" position="absolute" bgVariant="primary"
          changeColor="#333333" textVariant="white"
          v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'imgSrc','displayName':'ImageUrl'},{'type':'string','propName':'cardText','displayName':'Value'}]}"
          verticalPosition="align-items-center" horizontalPosition="justify-content-center"
          id="ae77595b-969d-48fe-a903-bbace85c63cd"
          v-bind:style="{'width':'1328.1px','height':'85.5px','zIndex':12,'maxWidth':'','minWidth':'','marginTop':'0px','maxHeight':'','minHeight':'','marginLeft':'0px','paddingTop':'0px','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px'}"/>
        <WLink top="92.9965490797546%" href="" left="36.21468168812589%" v-bind:exact="false" v-bind:snapX="false"
          v-bind:snapY="false" v-bind:active="false" v-bind:append="false" caption="Website Templates"
          v-bind:disabled="false" position="absolute" routerTag="a" linkTarget="_self" ncLinkType="link"
          ncOverflow="hidden" v-bind:visibility="true" activeClass="" ncTypography="custom" ncTooltipText=""
          v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'href','displayName':'Href'},{'type':'string','propName':'caption','displayName':'Caption'}]}"
          toForRouterLink="to" exactActiveClass="" ncClickFontColor="#0000FF" ncFocusFontColor="#00FF00"
          ncHoverFontColor="#ff0000" ncDisableFontColor="#4285f4" id="125a5050-76b7-4f6e-a5d7-62a3701285bb"
          v-bind:style="{'color':'#4285f4','width':'','height':'','zIndex':13,'fontSize':'12.111482550000002px','maxWidth':'','minWidth':'','tabIndex':'-0.71244015','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'left','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','lineHeight':'0.9974162099999998','marginLeft':'0px','paddingTop':'0px','textShadow':'','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'underline'}"/>
        <WLabel top="92.9965490797546%" left="44.07971208869814%" text="created with" v-bind:snapX="false"
          v-bind:snapY="false" theme="theme--light01" position="absolute" ncTypography="custom" ncTooltipText=""
          v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
          id="5c1f398e-4a89-4c63-9e25-f867891c3ee7"
          v-bind:style="{'color':'#ffffff','width':'','height':'','zIndex':14,'fontSize':'12.111482550000002px','maxWidth':'','minWidth':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'left','fontFamily':'OpenSans-Regular,Open Sans','fontWeight':'normal','lineHeight':'0.9974162099999998','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'none'}"/>
        <WLink top="92.8125%" href="" left="49.756348354792564%" v-bind:exact="false" v-bind:snapX="false"
          v-bind:snapY="false" v-bind:active="false" v-bind:append="false" caption=" Website Builder Software."
          v-bind:disabled="false" position="absolute" routerTag="a" linkTarget="_self" ncLinkType="link"
          ncOverflow="hidden" v-bind:visibility="true" activeClass="" ncTypography="custom" ncTooltipText=""
          v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'href','displayName':'Href'},{'type':'string','propName':'caption','displayName':'Caption'}]}"
          toForRouterLink="to" exactActiveClass="" ncClickFontColor="#0000FF" ncFocusFontColor="#00FF00"
          ncHoverFontColor="#ff0000" ncDisableFontColor="#4285f4" id="3836a374-10d0-4b78-8abd-c996d57930eb"
          v-bind:style="{'color':'#4285f4','width':'','height':'','zIndex':15,'fontSize':'12.111482550000002px','maxWidth':'','minWidth':'','tabIndex':'-0.71244015','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'left','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','lineHeight':'0.9974162099999998','marginLeft':'0px','paddingTop':'0px','textShadow':'','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'underline'}"/>
        <WPagination v-bind:fill="false" size="md" limit="5" v-bind:pills="false" value="1" perPage="1" lastText="»"
          nextText="›" prevText="‹" firstText="«" v-bind:isEnabled="true" totalRows="13" v-bind:lastNumber="false"
          v-bind:firstNumber="false" ellipsisText="..." v-bind:hideEllipsis="false" ncTooltipText="Tooltip text"
          v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'number','propName':'value','displayName':'Value'}]}"
          v-bind:hideGotoEndButtons="false" position="absolute" top="16.896990997953672%" left="35.46917293233083%"
          id="e9a8f7ff-3d9e-4d38-9c7a-447049d7fe60"
          v-bind:style="{'width':'','height':'32.798','fontSize':'8.556px','maxWidth':'','minWidth':'','tabIndex':'','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','fontFamily':'Roboto-Regular,Roboto','fontWeight':'','lineHeight':'','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','borderColor':'#000000','borderStyle':'none','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','ncTypography':'NaN','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','textDecoration':'none','borderLeftWidth':'0px','borderRightWidth':'0px','horizontalHeight':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'3.565px','borderTopRightRadius':'3.565px','borderBottomLeftRadius':'3.565px','borderBottomRightRadius':'3.565px','zIndex':16}"/>
        <WRangeInput id="6e65bf01-6cd8-4e91-ae01-f566460a0903" v-bind:lazy="false" size="md" text="" v-bind:trim="false"
          v-bind:noWheel="false" v-bind:disabled="false" v-bind:readonly="false" v-bind:required="false" wordList=""
          v-bind:autofocus="false" v-bind:plaintext="false" background="" ariaInvalid="false" v-bind:debounceVal="0"
          ncInputType="range" placeholder="" v-bind:previewMode="true" autocomplete="" ncTypography="body1"
          v-bind:lazyFormatter="false" ncTooltipText="" v-bind:isWordListOpen="false"
          v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':true,'structure':[{'type':'string','ncKey':'type','ncType':{'ncInputType':'number'},'ncValue':'number','propName':'text','displayName':'Value','nsDefaultValue':'string'}]}"
          v-bind:isNumberConvert="false" ncClickFontColor="#434855" ncFocusFontColor="#434855"
          ncHoverFontColor="#434855" ncMaxNumberValue="100" ncMinNumberValue="0" ncClickBorderColor="#000000"
          ncDisableFontColor="#434855" ncFocusBorderColor="#000000" ncHoverBorderColor="#000000"
          ncDisableBorderColor="#000000" formatterFunctionName="" ncClickBackgroundColor="#ffffff"
          ncFocusBackgroundColor="#ffffff" ncHoverBackgroundColor="#ffffff" ncDisableBackgroundColor="#ffffff"
          position="absolute" top="74.22997895165959%" left="14.711278195488722%"
          v-bind:style="{'color':'','width':'112.654px','height':'','fontSize':'8.556px','maxWidth':'','minWidth':'','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'left','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','lineHeight':'0.713','marginLeft':'0px','paddingTop':'0px','visibility':'visible','borderColor':'#D1D1D6','borderStyle':'none','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'none','zIndex':17}"/>
      </NucGroupElement>
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