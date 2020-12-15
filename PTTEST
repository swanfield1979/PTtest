PAIRS
#########################
#GENERAL SETTINGS########
#########################
market = USDT
enabled_pairs = BTC, ETH
max_trading_pairs = 2
DEFAULT_buy_leverage = 10
DEFAULT_buy_margin_type = ISOLATED
#######################
#DEFAULT SETTINGS######
#######################
DEFAULT_trading_enabled = true
DEFAULT_DCA_enabled = false
DEFAULT_initial_cost = 250
DEFAULT_min_buy_volume = 25000000
#######################
#BUY SETTINGS##########
#######################
DEFAULT_A_buy_strategy_label = 1h_MACDSL
DEFAULT_A_buy_strategy = MACD
DEFAULT_B_buy_strategy_label = 1h_MACDLINE
DEFAULT_B_buy_strategy = MACD
DEFAULT_C_buy_strategy = RSI
DEFAULT_C_buy_value = 30
DEFAULT_D_buy_strategy_label = 1h_MACDHG
DEFAULT_D_buy_strategy = MACD
DEFAULT_D_buy_value = 0.000000001
DEFAULT_D_buy_value_limit = -99.00000000
DEFAULT_buy_strategy_level1_formula = C
DEFAULT_buy_strategy_level2_formula = SB > SA
DEFAULT_buy_strategy_level3_formula = D

#######################
#SELL SETTINGS#########
#######################
DEFAULT_trailing_profit = 5.00
DEFAULT_A_sell_strategy = RSI
DEFAULT_A_sell_value = 60
DEFAULT_B_sell_strategy_label = 1h_MACDSL
DEFAULT_B_sell_strategy = MACD
DEFAULT_C_sell_strategy_label = 1h_MACDLINE
DEFAULT_C_sell_strategy = MACD
DEFAULT_D_sell_strategy_label = 1h_MACDHG
DEFAULT_D_sell_strategy = MACD
DEFAULT_D_sell_value = 0.000000001
DEFAULT_D_sell_value_limit = -99.000000000
DEFAULT_sell_strategy_formula = A || SC < SB && D
DEFAULT_trailing_profit_enabled_formula = A

INDICATORS

1h_MACDSL_candle_period = 3600
1h_MACDSL_fast_Length = 12
1h_MACDSL_slow_Length = 26
1h_MACDSL_signal = 9
1h_MACDSL_return_value = SIGNALLINE

1h_MACDLINE_candle_period = 3600
1h_MACDLINE_fast_Length = 12
1h_MACDLINE_slow_Length = 26
1h_MACDLINE_signal = 9
1h_MACDLINE_return_value = MACDLINE

1h_MACDHG_candle_period = 3600
1h_MACDHG_fast_Length = 12
1h_MACDHG_slow_Length = 26
1h_MACDHG_signal = 9
1h_MACDHG_return_value = HISTORGRAM

HMA_candle_period = 3600
HMA_length = 144
HMA_fast_length = 14
HMA_slow_length = 144

HMASLOW_candle_period = 3600
HMASLOW_length = 14
HMASLOW_only_closed_candles = true

RSI_candle_period = 3600
RSI_length = 10

PDHIGH_candle_period = 3600
PDHIGH_range = 4
