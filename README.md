#ETH - 21.06 / max DCA_2 = 1,31% / 10 trade
#———————————— BUY ------------------------- =
ETH_A_buy_strategy =  HIGHBB 
ETH_A_buy_value =  20 
ETH_A_buy_value_limit =  -40 

#———————————— SELL ------------------------- =
ETH_A_sell_strategy (GAIN is mandatory) =  GAIN 
ETH_A_sell_value =  0.3 

#—————————— TRAILING ---------------------- =
ETH_trailing_buy =  0.1 
ETH_DCA_trailing_buy =  0.1 
ETH_trailing_profit =  0.2 

#——————————— DCA BUY ---------------------- =
ETH_DCA_B_buy_strategy =  HIGHBB 
ETH_DCA_B_buy_value =  5 
ETH_DCA_B_buy_value_limit =  -40 

#————————— ANDERSON DCA ------------------- =
ETH_DCA_enabled = true
ETH_DCA_max_buy_times =  0 
ETH_DCA_ignore_sell_only_mode = false
ETH_DCA_buy_trigger =  -0.9 
ETH_DCA_buy_trigger_1 =  -0.9 
ETH_DCA_buy_trigger_2 =  -0.9 
ETH_DCA_buy_trigger_3 =  -0.9
ETH_DCA_buy_trigger_4 =  -0.9
ETH_DCA_buy_trigger_5 =  -0.9 
ETH_DCA_buy_trigger_6 =  -0.9 
ETH_DCA_buy_trigger_7 =  -0.9 
ETH_DCA_buy_trigger_8 =  -0.9 
ETH_DCA_buy_trigger_9 =  -0.9 
ETH_DCA_buy_percentage =  100 
ETH_DCA_buy_percentage_1 =  100 
ETH_DCA_buy_percentage_2 =  100 
ETH_DCA_buy_percentage_3 =  100 
ETH_DCA_buy_percentage_4 =  100 
ETH_DCA_buy_percentage_5 =  100 
ETH_DCA_buy_percentage_6 =  100 
ETH_DCA_buy_percentage_7 =  100 
ETH_DCA_buy_percentage_8 =  100 
ETH_DCA_buy_percentage_9 =  100

Для TradingView
{
  "------ PTStratX 1.0.7 - Easy Strats and more ---------": "1.0.7",
  "------ for Profittrailer 2 and other Bots  -------": "",
  "------------------------- BUY -------------------------": "",
  "DEFAULT_A_buy_strategy": "HIGHBB",
  "DEFAULT_A_buy_value": "20",
  "DEFAULT_A_buy_value_limit": "-40",
  "-------------------------------------------------------": "",
  "DEFAULT_B_buy_strategy": "--",
  "DEFAULT_B_buy_value": "-0.01",
  "DEFAULT_B_buy_value_limit": "-3",
  "--------------------------------------------------------": "",
  "DEFAULT_C_buy_strategy": "--",
  "DEFAULT_C_buy_value": "-0.001",
  "DEFAULT_C_buy_value_limit": "-0.01",
  "DEFAULT_D_buy_strategy": "--",
  "DEFAULT_D_buy_value": "-20",
  "DEFAULT_D_buy_value_limit": "0",
  "DEFAULT_E_buy_strategy": "--",
  "DEFAULT_E_buy_value": "0",
  "DEFAULT_E_buy_value_limit": "0",
  "------------- INDICATOR PARAMETERS -------------": "",
  "EMA_slow_length (blue)": "100",
  "EMA_fast_length (green)": "20",
  "EMA_cross_candles": "3",
  "EMA_candle_period (in Sec)": "   60s / 1m",
  "SMA_slow_length (blue)": "8",
  "SMA_fast_length (green)": "2",
  "SMA_cross_candles": "2",
  "SMA_candle_period (in Sec)": "   60s / 1m",
  "BB_length": "40",
  "BB_std": "2",
  "BB_candle_period (in Sec)": "   60s / 1m",
  "RSI_length": "14",
  "RSI_candle_period (in Sec)": "   60s / 1m",
  "STOCH_length": "14",
  "STOCH_candle_period (in Sec)": "   60s / 1m",
  "MACD_fast_length": "12",
  "MACD_slow_length": "26",
  "MACD_signal": "9",
  "MACD_candle_period (in Sec)": "   60s / 1m",
  "----------SOM Parameters-------------------": "",
  "DEFAULT_rebuy_timeout (in min)": "0",
  "DEFAULT_DCA_rebuy_timeout (in min)": "0",
  "min/max_change_percentage_length (PT use only 1440m / 1d) (in min)": "1440",
  "DEFAULT_buy_min_change_percentage": "-10",
  "DEFAULT_buy_max_change_percentage": "20",
  "DEFAULT_DCA_buy_min_change_percentage": "0.25",
  "DEFAULT_DCA_buy_max_change_percentage": "10",
  "price_drop_trigger (in %)": "5",
  "price_drop_recover_trigger (in %)": "3",
  "price_rise_trigger (in %)": "7",
  "price_rise_recover_trigger (in %)": "6",
  "price_trigger_market": "BTC",
  "SOM_trigger_length (5 Minute Candles * X)": "288",
  "----------------------- DCA BUY ----------------------": "",
  "DEFAULT_DCA_A_buy_strategy": "--",
  "DEFAULT_DCA_A_buy_value": "-0.01",
  "DEFAULT_DCA_A_buy_value_limit": "0",
  "DEFAULT_DCA_B_buy_strategy": "HIGHBB",
  "DEFAULT_DCA_B_buy_value": "5",
  "DEFAULT_DCA_B_buy_value_limit": "-40",
  "DEFAULT_DCA_C_buy_strategy": "--",
  "DEFAULT_DCA_C_buy_value": "-0.001",
  "DEFAULT_DCA_C_buy_value_limit": "-0.01",
  "DEFAULT_DCA_D_buy_strategy": "--",
  "DEFAULT_DCA_D_buy_value": "-0.01",
  "DEFAULT_DCA_D_buy_value_limit": "-3",
  "DEFAULT_DCA_E_buy_strategy": "--",
  "DEFAULT_DCA_E_buy_value": "50",
  "DEFAULT_DCA_E_buy_value_limit": "0",
  "------------------ ANDERSON DCA -------------------": "",
  "DEFAULT_DCA_enabled": true,
  "DEFAULT_DCA_max_buy_times": "0",
  "DEFAULT_DCA_ignore_sell_only_mode": false,
  "DEFAULT_DCA_buy_trigger": "-0.9",
  "DEFAULT_DCA_buy_trigger_1": "-0.9",
  "DEFAULT_DCA_buy_trigger_2": "-0.9",
  "DEFAULT_DCA_buy_trigger_3": "-0.9",
  "DEFAULT_DCA_buy_trigger_4": "-0.9",
  "DEFAULT_DCA_buy_trigger_5": "-0.9",
  "DEFAULT_DCA_buy_trigger_6": "-0.9",
  "DEFAULT_DCA_buy_trigger_7": "-0.9",
  "DEFAULT_DCA_buy_trigger_8": "-0.9",
  "DEFAULT_DCA_buy_trigger_9": "-0.9",
  "DEFAULT_DCA_buy_percentage": "100",
  "DEFAULT_DCA_buy_percentage_1": "100",
  "DEFAULT_DCA_buy_percentage_2": "100",
  "DEFAULT_DCA_buy_percentage_3": "100",
  "DEFAULT_DCA_buy_percentage_4": "100",
  "DEFAULT_DCA_buy_percentage_5": "100",
  "DEFAULT_DCA_buy_percentage_6": "100",
  "DEFAULT_DCA_buy_percentage_7": "100",
  "DEFAULT_DCA_buy_percentage_8": "100",
  "DEFAULT_DCA_buy_percentage_9": "100",
  "------------------------- SELL -------------------------": "",
  "DEFAULT_A_sell_strategy (GAIN is mandatory)": "GAIN",
  "DEFAULT_A_sell_value": "0.3",
  "DEFAULT_B_sell_strategy": "--",
  "DEFAULT_B_sell_value": "50",
  "DEFAULT_C_sell_strategy": "--",
  "DEFAULT_C_sell_value": "60",
  "DEFAULT_D_sell_strategy": "--",
  "DEFAULT_D_sell_value": "0",
  "DEFAULT_E_sell_strategy": "--",
  "DEFAULT_E_sell_value": "0",
  "DEFAULT_stop_loss_trigger": "0",
  "--------------------- TRAILING ----------------------": "",
  "DEFAULT_trailing_buy": "0.1",
  "DEFAULT_DCA_trailing_buy": "0.1",
  "DEFAULT_trailing_profit": "0.2",
  "-------------------- BACKTEST ----------------------": "",
  "From Minute": "0",
  "From Hour": "0",
  "From Month": "6",
  "From Day": "18",
  "From Year": "2018",
  "To Month": "1",
  "To Day": "1",
  "To Year": "10001",
  "--------------------- PLOTTING ----------------------": "",
  "Show Setting Debug Mode with letters; DCA=orange, Buy=green": false,
  "Show Buystrat ALL = true with Bars (green)": true,
  "Show Buystrat ALL = true with Arrows (green)": false,
  "Show Buystrat A = true with Letters (green Letter A)": true,
  "Show Buystrat B = true with Letters (green Letter B)": true,
  "Show Buystrat C = true with Letters (green Letter C)": true,
  "Show Buystrat D = true with Letters (green Letter D)": true,
  "Show Buystrat E = true with Letters (green Letter E)": true,
  "Show DCA Buystrat ALL = true with Bars (orange)": true,
  "Show DCA Buystrat A = true with Letters (orange Letter A)": false,
  "Show DCA Buystrat B = true with Letters (orange Letter B)": false,
  "Show DCA Buystrat C = true with Letters (orange Letter C)": false,
  "Show DCA Buystrat D = true with Letters (orange Letter D)": false,
  "Show DCA Buystrat E = true with Letters (orange Letter E)": false,
  "Show SellStrat All = true with Bars (red)": true,
  "Show Trailing Debug Informations": false
}
