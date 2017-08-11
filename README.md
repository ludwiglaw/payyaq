		
		<link rel="stylesheet" href="https://api.epay.com/paymentApi/css/exchange.css?v=20170807" />
		<script src="https://api.epay.com/paymentApi/js/jquery-1.9.1.js"></script>
		<script src="https://api.epay.com/paymentApi/js/exchange1.js?v=20170807"></script>

	<input type="hidden" id="merchant_epay_account" value="ella@epay.com">
		<div class="width-w">
			<div id="formDiv"></div>
			<div class="width03-w1080">
				<div class="width-top">
					<p>E-currency Auto Exchange</p>
					<span><img src="https://api.epay.com/paymentApi/images/big-epay-logo_03.png"/></span>
				</div>
				<div class="rel">
					<img src="https://api.epay.com/paymentApi/images/bj_03.png"/>
					<ul class="rel-ul">
						<li>Send </li>
						<li>Amount</li>
						<li>Receive </li>
						<li>Amount </li>
					</ul>
				</div>
				<div class="main-content">
					<div class="main-fl">
						<ul>
							<li>
								<div name="leftDiv" class="select-bj pointer" id="pm_usd">
									<div class="text-fl">
										<span name="leftSpan" class="select-ok"  onclick="chooseGive(this);"></span>
										<i class="itwo"></i>
										<p class="f-s14">Perfect Money USD</p>
									</div>
									<div name="leftAmount" class="shurukuang text-fr">
										<input type="text" onkeyup="clearNum(this)" onblur="giveAmount(this,'USD','01');" name="AMOUNT" class="shurukuangchild" placeholder="Amount"/>
										<p class="blue-p">USD</p>
									</div>
								</div>
							</li>
							<li>
								<div name="leftDiv" class="select-nobj pointer" id="pm_eur" >
									<div class="text-fl">
										<span name="leftSpan" class="select-no"  onclick="chooseGive(this,'EUR');"></span>
										<i class="itwo"></i>
										<p class="f-s14">Perfect Money EUR</p>
									</div>
									<div name="leftAmount" class="shurukuang shukuangdisnoe text-fr">
										<input type="text" onkeyup="clearNum(this)" onblur="giveAmount(this,'EUR','01');" name="AMOUNT" class="shurukuangchild" placeholder="Amount"/>
										<p class="blue-p">EUR</p>
									</div>
								</div>
							</li>
							<li>
								<div name="leftDiv" id="ok_usd" class="select-nobj pointer" >
									<div class="text-fl">
										<span name="leftSpan" class="select-no" onclick="chooseGive(this);"></span>
										<i class="ithree" ></i>
										<p class="f-s14">OKPAY USD</p>
									</div>
									<div name="leftAmount" class="shurukuang shukuangdisnoe text-fr">
										<input type="text" onkeyup="clearNum(this)" onblur="giveAmount(this,'USD','05');" class="shurukuangchild" placeholder="Amount"/>
										<p class="blue-p" >USD</p>

									</div>
								</div>
							</li>
							<li>
								<div name="leftDiv" id="ok_eur" class="select-nobj pointer" >
									<div class="text-fl">
										<span name="leftSpan" class="select-no" onclick="chooseGive(this);"></span>
										<i class="ithree"></i>
										<p class="f-s14">OKPAY EUR</p>
									</div>
									
									<div name="leftAmount" class="shurukuang shukuangdisnoe text-fr">
										<input type="text" onkeyup="clearNum(this)" onblur="giveAmount(this,'EUR','05');" class="shurukuangchild" placeholder="Amount"/>
										<p class="blue-p">EUR</p>
									</div>
								</div>
							</li>
							<li>
								<div name="leftDiv" id="payeer_usd" class="select-nobj pointer" >
									<div class="text-fl">
										<span name="leftSpan" class="select-no" onclick="chooseGive(this);"></span>
										<i class="ifour"></i>
										<p class="f-s14">Payeer USD</p>
									</div>
									
									<div  name="leftAmount" class="shurukuang shukuangdisnoe text-fr">
										<input type="text" onkeyup="clearNum(this)" onblur="giveAmount(this,'USD','06');" class="shurukuangchild" placeholder="Amount"/>
										<p class="blue-p">USD</p>
									</div>
								</div>
							</li>
							<li>
								<div name="leftDiv" id="payeer_eur" class="select-nobj pointer" >
									<div class="text-fl">
										<span name="leftSpan" class="select-no" onclick="chooseGive(this);"></span>
									    <i class="ifour"></i>
										<p class="f-s14">Payeer EUR</p>
									</div>
									<div name="leftAmount" class="shurukuang shukuangdisnoe text-fr">
										<input type="text" onkeyup="clearNum(this)" onblur="giveAmount(this,'EUR','06');" class="shurukuangchild" placeholder="Amount"/>
										<p class="blue-p" >EUR</p>
									</div>
								</div>
							</li>
							<li>
								<div name="leftDiv" id="advcash_usd" class="select-nobj pointer" >
									<div class="text-fl">
										<span name="leftSpan" class="select-no" onclick="chooseGive(this);"></span>
									    <i class="ifive"></i>
										<p class="f-s14">AdvCash USD</p>
									</div>
									<div name="leftAmount" class="shurukuang shukuangdisnoe text-fr">
										<input type="text" onkeyup="clearNum(this)" onblur="giveAmount(this,'USD','02');" class="shurukuangchild" placeholder="Amount"/>
										<p class="blue-p" >USD</p>
									</div>
								</div>
							</li>
							<li>
								<div name="leftDiv" id="advcash_eur" class="select-nobj pointer" >
									<div class="text-fl">
										<span name="leftSpan" class="select-no" onclick="chooseGive(this);"></span>
									    <i class="ifive"></i>
										<p class="f-s14">AdvCash EUR</p>
									</div>
									<div name="leftAmount" class="shurukuang shukuangdisnoe text-fr">
										<input type="text" onkeyup="clearNum(this)" onblur="giveAmount(this,'EUR','02');" class="shurukuangchild" placeholder="Amount"/>
										<p class="blue-p" >EUR</p>
									</div>
								</div>
							</li>
							<li>
								<div name="leftDiv" id="fasapay_usd" class="select-nobj pointer">
									<div class="text-fl">
										<span name="leftSpan" class="select-no" onclick="chooseGive(this);"></span>
									    <i class="isix"></i>
										<p class="f-s14">FasaPay USD</p>
									</div>
									<div name="leftAmount" class="shurukuang shukuangdisnoe text-fr">
										<input type="text" onkeyup="clearNum(this)" onblur="giveAmount(this,'USD','08');" class="shurukuangchild" placeholder="Amount"/>
										<p class="blue-p" >USD</p>
									</div>
								</div>
							</li>
						</ul>
					</div>

					<!-- 右边 YOU GET -->
					<div class="main-fr">
						<form>
							<table id="rightTable01" class="bjblue-middl ">
								<tr class="midd-span">
									<td><i class="fl-icons"></i></td>
									<td class="sspan-p" align="left">Perfect Money</td>
									<td align="left">
										<div class="shurukuang1">
											<input type="text" class="getamount01 tex-input" readonly="readonly"/>
											<p class="getCurrency blue-p">USD</p>
										</div>
									</td>
									<td class="w-79" align="right"><a href="javascript:;" class="fl-p" onclick="showGet('01')">GO<i class="go-i"></i></a></td>
								</tr>
								<tr id="emailAccount01" class="ea midd-span dis-nonecont">
									<td>
										<div class="dis-inl">
											<p>Perfect Money Account:</p>
											<input id="account01" type="text" class="input-cl"/>
										</div>
										<div class="dis-inl padd-le36">
											<p>Contact Email:</p>
											<input id="email01" type="text" class="input-cl159"/>
										</div>
										<div class="blu-btn"><p onclick="getEmailAndAccount('01')">Exchange</p></div>
									</td>
								</tr>
							</table>
							<table id="rightTable05" class="bjblue-middl">
								<tr class="midd-span">
									<td align="right"><i class="p-ione"></i></td>
									<td class="sspan-p" align="left">OKPAY</td>
									<td align="left">
										<lebel class="shurukuang1 maleft-119">
											<input type="text" class="getamount05 tex-input" readonly="readonly"/>
											<p class="getCurrency blue-p">USD</p>
										</lebel>
									</td>
									<td class="w-79" align="right"><a href="javascript:;" class="fl-p" onclick="showGet('05')">GO<i class="go-i"></i></a></td>
								</tr>
								<tr id="emailAccount05" class="ea midd-span dis-nonecont">
									<td>
										<div class="dis-inl">
											<p>OKPAY Account:</p>
											<input id="account05" type="text" class="input-cl"/>
										</div>
										<div class="dis-inl padd-le36">
											<p>Contact Email:</p>
											<input id="email05" type="text" class="input-cl159"/>
										</div>
										<div class="blu-btn"><p onclick="getEmailAndAccount('05')">Exchange</p></div>
									</td>
								</tr>
							</table>
							<table id="rightTable06" class="bjblue-middl">
								<tr class="midd-span ">
									<td align="right"><i class="p-itwo"></i></td>
									<td class="sspan-p" align="left">Payeer</td>
									<td align="left">
										<lebel class="shurukuang1">
											<input type="text" class="getamount06 tex-input" readonly="readonly"/>
											<p class="getCurrency blue-p">USD</p>
										</lebel>
									</td>
									<td class="w-79" align="right"><a href="javascript:;" class="fl-p" onclick="showGet('06')">GO<i class="go-i"></i></a></td>
								</tr>
								<tr id="emailAccount06" class="ea midd-span dis-nonecont">
									<td>
										<div class="dis-inl">
											<p>Payeer Account:</p>
											<input id="account06" type="text" class="input-cl"/>
										</div>
										<div class="dis-inl padd-le36">
											<p>Contact Email:</p>
											<input id="email06" type="text" class="input-cl159"/>
										</div>
										<div class="blu-btn"><p onclick="getEmailAndAccount('06')">Exchange</p></div>
									</td>
								</tr>
							</table>
							<table id="rightTable02" class="bjblue-middl">
								<tr class="midd-span">
									<td align="right"><i class="p-ithree"></i></td>
									<td class="sspan-p" align="left">AdvCash</td>
									<td align="left">
										<lebel class="shurukuang1 maleft-108">
											<input type="text" class="getamount02 tex-input" readonly="readonly"/>
											<p class="getCurrency blue-p">USD</p>
										</lebel>
									</td>
									<td class="w-79" align="right"><a href="javascript:;" class="fl-p" onclick="showGet('02')">GO<i class="go-i"></i></a></td>
								</tr>
								<tr id="emailAccount02" class="ea midd-span dis-nonecont">
									<td>
										<div class="dis-inl">
											<p>Advcash Account:</p>
											<input id="account02" type="text" class="input-cl"/>
										</div>
										<div class="dis-inl padd-le36">
											<p>Contact Email:</p>
											<input id="email02" type="text" class="input-cl159"/>
										</div>
										<div class="blu-btn"><p onclick="getEmailAndAccount('02')">Exchange</p></div>
									</td>
								</tr>
							</table>
							<table id="rightTable08" class="bjblue-middl">
								<tr class="midd-span">
									<td align="right"><i class="p-ifour"></i></td>
									<td class="sspan-p" align="left">FasaPay</td>
									<td align="left">
										<lebel class="shurukuang1">
											<input type="text" class="getamount08 tex-input" readonly="readonly"/>
											<p class="getCurrency blue-p">USD</p>
										</lebel>
									</td>
									<td class="w-79" align="right"><a href="javascript:;" class="fl-p" onclick="showGet('08')">GO<i class="go-i"></i></a></td>
								</tr>
								<tr id="emailAccount08" class="ea midd-span dis-nonecont">
									<td>
										<div class="dis-inl">
											<p>Fasapay Account:</p>
											<input id="account08" type="text" class="input-cl"/>
										</div>
										<div class="dis-inl padd-le36">
											<p>Contact Email:</p>
											<input id="email08" type="text" class="input-cl159"/>
										</div>
										<div class="blu-btn"><p onclick="getEmailAndAccount('08')">Exchange</p></div>
									</td>
								</tr>
							</table>
							<table id="rightTable03" class="bjblue-middl">
								<tr class="midd-span">
									<td align="right"><i class="p-web"></i></td>
									<td class="sspan-p" align="left">WebMoney </td>
									<td align="left">
										<lebel class="shurukuang1">
											<input type="text" class="getamount03 tex-input" readonly="readonly"/>
											<p class="getCurrency blue-p">USD</p>
										</lebel>
									</td>
									<td class="w-79" align="right"><a href="javascript:;" class="fl-p" onclick="showGet('03')">GO<i class="go-i"></i></a></td>
								</tr>
								<tr id="emailAccount03" class="ea midd-span dis-nonecont">
									<td>
										<div class="dis-inl">
											<p>Webmoney Account:</p>
											<input id="account03" type="text" class="input-cl"/>
										</div>
										<div class="dis-inl padd-le36">
											<p>Contact Email:</p>
											<input id="email03" type="text" class="input-cl159"/>
										</div>
										<div class="blu-btn"><p onclick="getEmailAndAccount('03')">Exchange</p></div>
									</td>
								</tr>
							</table>
							<table id="rightTable07" class="bjblue-middl">
								<tr class="midd-span">
									<td align="right"><i class="p-pp"></i></td>
									<td class="sspan-p" align="left">Paypal </td>
									<td align="left">
										<lebel class="shurukuang1">
											<input type="text" class="getamount07 tex-input" readonly="readonly"/>
											<p class="getCurrency blue-p">USD</p>
										</lebel>
									</td>
									<td class="w-79" align="right"><a href="javascript:;" class="fl-p" onclick="showGet('07')">GO<i class="go-i"></i></a></td>
								</tr>
								<tr id="emailAccount07" class="ea midd-span dis-nonecont">
									<td>
										<div class="dis-inl">
											<p>Paypal Account:</p>
											<input id="account07" type="text" class="input-cl"/>
										</div>
										<div class="dis-inl padd-le36">
											<p>Contact Email:</p>
											<input id="email07" type="text" class="input-cl159"/>
										</div>
										<div class="blu-btn"><p onclick="getEmailAndAccount('07')">Exchange</p></div>
									</td>
								</tr>
							</table>
						</form>

						<div class="text-footer"><p>Powered by  <a href="https://www.epay.com">Epay.com</a></p></div>
					</div>
				</div>
			</div>
		</div>

	<input type="hidden" id="merchant_epay_account" value="ludwig.luo@gmail.com"><input type="hidden" id="merchant_epay_account" value="ludwig.luo@gmail.com">
