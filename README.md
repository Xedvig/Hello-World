<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:otp="http://www.dk.hu/otprusoa">
   <soapenv:Header/>
   <soapenv:Body>
      <otp:MsgReply>
         <Header>
            <!--Optional:-->
            <DebugLevel></DebugLevel>
            <!--Optional:-->
            <ErrorCode></ErrorCode>
            <!--Optional:-->
            <ErrorDetail></ErrorDetail>
            <!--Optional:-->
            <MsgVersion></MsgVersion>
            <ProgName></ProgName>
            <ProgVer></ProgVer>
            <!--Optional:-->
            <Scnr></Scnr>
            <TimeStamp></TimeStamp>
         </Header>
         <!--Optional:-->
         <Body>
            <ResponseCode>0</ResponseCode>
            <!--Optional:-->
            <ErrorDescription></ErrorDescription>
            <!--Optional:-->
            <ErrorAction></ErrorAction>
            <!--Optional:-->
            <ExternalSessionId></ExternalSessionId>
         </Body>
      </otp:MsgReply>
   </soapenv:Body>
</soapenv:Envelope>
