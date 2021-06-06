var helpers = require("../../node_modules/@parcel/transformer-react-refresh-wrap/lib/helpers/helpers.js");
var prevRefreshReg = window.$RefreshReg$;
var prevRefreshSig = window.$RefreshSig$;
helpers.prelude(module);
try {
  var _parcelHelpers = require("@parcel/transformer-js/lib/esmodule-helpers.js");
  _parcelHelpers.defineInteropFlag(exports);
  var _react = require('react');
  var _reactDefault = _parcelHelpers.interopDefault(_react);
  var _reactAsyncHook = require('react-async-hook');
  var _dateFnsAddDays = require('date-fns/addDays');
  var _dateFnsAddDaysDefault = _parcelHelpers.interopDefault(_dateFnsAddDays);
  var _dateFnsFormat = require('date-fns/format');
  var _dateFnsFormatDefault = _parcelHelpers.interopDefault(_dateFnsFormat);
  var _Orbital = require('./Orbital');
  var _OrbitalDefault = _parcelHelpers.interopDefault(_Orbital);
  var _jsxFileName = "F:\\Sandesh\\JS\\mdnStudy\\will-it-miss\\src\\components\\App.js", _s = $RefreshSig$();
  function _extends() {
    _extends = Object.assign || (function (target) {
      for (var i = 1; i < arguments.length; i++) {
        var source = arguments[i];
        for (var key in source) {
          if (Object.prototype.hasOwnProperty.call(source, key)) {
            target[key] = source[key];
          }
        }
      }
      return target;
    });
    return _extends.apply(this, arguments);
  }
  function getDate(d = new Date()) {
    return d.toJSON().split('T')[0];
  }
  const fetchData = () => fetch(`https://api.nasa.gov/neo/rest/v1/feed?start_date=${getDate()}&api_key=DEMO_KEY`).then(res => res.json());
  function App() {
    _s();
    const data = _reactAsyncHook.useAsync(fetchData, []);
    if (data.loading) {
      document.title = 'Counting potential earth HAZARDS…';
      return (
        /*#__PURE__*/_reactDefault.default.createElement("p", {
          __self: this,
          __source: {
            fileName: _jsxFileName,
            lineNumber: 23,
            columnNumber: 7
          }
        }, "Getting data from NASA right now to check whether something from space is going to hit us. One moment…")
      );
    }
    const day = getDate(_dateFnsAddDaysDefault.default(new Date(), 1));
    const hazards = data.result.near_earth_objects[day].reduce((acc, curr) => {
      if (curr.is_potentially_hazardous_asteroid) {
        return acc + 1;
      }
      return acc;
    }, 0);
    document.title = `${hazards} potential HAZARDS ${hazards > 0 ? '😱' : '👍'}`;
    const results = data.result.near_earth_objects[day];
    return (
      /*#__PURE__*/_reactDefault.default.createElement("div", {
        __self: this,
        __source: {
          fileName: _jsxFileName,
          lineNumber: 42,
          columnNumber: 5
        }
      }, /*#__PURE__*/_reactDefault.default.createElement("p", {
        __self: this,
        __source: {
          fileName: _jsxFileName,
          lineNumber: 43,
          columnNumber: 7
        }
      }, _dateFnsFormatDefault.default(_dateFnsAddDaysDefault.default(new Date(), 1), 'EEEE d-MMM'), " there will be", ' ', /*#__PURE__*/_reactDefault.default.createElement("strong", {
        __self: this,
        __source: {
          fileName: _jsxFileName,
          lineNumber: 45,
          columnNumber: 9
        }
      }, results.length), " flying pigs"), /*#__PURE__*/_reactDefault.default.createElement("hr", {
        __self: this,
        __source: {
          fileName: _jsxFileName,
          lineNumber: 47,
          columnNumber: 7
        }
      }), results.sort(a => a.is_potentially_hazardous_asteroid ? -1 : 1).map(data => /*#__PURE__*/_reactDefault.default.createElement(_OrbitalDefault.default, _extends({
        key: data.id
      }, data, {
        __self: this,
        __source: {
          fileName: _jsxFileName,
          lineNumber: 51,
          columnNumber: 11
        }
      }))))
    );
  }
  exports.default = App;
  _s(App, "9wXMhUsmxHicUud68cGSOQnZgDo=", false, function () {
    return [_reactAsyncHook.useAsync];
  });
  _c = App;
  var _c;
  $RefreshReg$(_c, "App");
  helpers.postlude(module);
} finally {
  window.$RefreshReg$ = prevRefreshReg;
  window.$RefreshSig$ = prevRefreshSig;
}
