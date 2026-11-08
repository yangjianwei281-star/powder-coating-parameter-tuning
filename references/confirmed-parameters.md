# Confirmed Parameters

## Evidence and Scope

The provider explicitly confirms that ordinary, non-rotary-cup electrostatic powder-coating machines can use this parameter guidance too. It is not limited to rotary-cup spraying. Check the control meanings, units and equipment limits as usual; do not imply that a conventional gun has rotary-cup hardware or Q7/X7 automatic functions.

These values were explicitly confirmed by the manufacturer representative during preparation of this skill on 2026-11-07. The provider also explicitly permits using this Q7/X7-based parameter guidance on other electrostatic powder guns, even without preset modes. This is provider-supplied application guidance, not independent validation of every machine or powder formulation. Check control meanings, units, permitted ranges, and equipment/powder-supplier restrictions. Earlier conflicting transcript values and the initial draft's blanket exclusion of other brands are superseded.

| Powder type | Confirmed voltage | Confirmed current | Status |
| --- | --- | --- | --- |
| Metallic powder | 30 kV reference; do not exceed 30 kV | 50 microamperes (50 uA) reference | Manufacturer-confirmed; 50 uA is not a stated maximum |
| Textured / sand-texture powder | Maximum 45 kV | Minimum current setting 50 microamperes (50 uA) | Manufacturer-confirmed Q7/X7 setting limits |
| Smooth-finish powder | Maximum 80 kV | Minimum current setting 50 microamperes (50 uA) | Manufacturer-confirmed Q7/X7 setting limits |

Voltage maxima are ceilings, not mandatory operating targets. For textured and smooth-finish powders, 50 uA is the manufacturer's minimum current SETTING in this guidance, not a guaranteed minimum measured current during spraying. Do not tell operators to force actual current readings to reach 50 uA. Current upper limits and voltage lower limits have not been supplied; do not invent them. Metallic powder's 50 uA remains a reference value, not a confirmed minimum.

Do not automatically apply these settings to rework or unusual powders. Another brand or absence of preset modes alone does not prevent use of this guidance. If a scenario calls for settings outside these boundaries, request manufacturer guidance rather than silently overriding them.

For metallic powder, do not recommend increasing voltage to 50 kV. Use the confirmed 30 kV ceiling even if an older note or a controller's general range permits higher numbers. If the user's manual or powder supplier imposes a stricter limit, do not override it; seek manufacturer clarification.

## Units

- Voltage: kV, not V.
- Current: microamperes, written uA or μA, not A.
- Powder-delivery and atomizing display settings have a manufacturer-confirmed reference ratio of 2:1 for the intended Q7/X7 context: for example, powder delivery 80 and atomizing 40. This is a reference starting relationship, not a mandatory ratio or a recommendation to use 80/40 for every job. Adjust for the workpiece and observed coating behavior within the equipment's permitted settings.
- The 2:1 ratio refers to the corresponding controller settings, not a physical ratio of powder mass flow to air flow or pressure. Other powder-gun brands may use it as reference guidance when the controls have corresponding meanings and scales. If a controller instead uses pressure or other differently defined values, ask for its labels/manual rather than invent a numerical conversion. Do not infer rpm, bar, g/min, or percent from a bare number.
- Film thickness is a separate measured quantity; never interpret a powder-output display value as coating thickness.

## Example Answers

User: 我的是普通静电喷塑机，不是旋杯式，也能用这个参数吗？

Answer: 可以。这套参数也适用于普通静电喷塑机，不要求使用旋杯式喷头。按粉末种类参考相应参数，并核对设备的单位、控制项含义和允许范围即可；参数适用不代表设备自带 Q7/X7 的自动生成与推送功能。

User: 金属粉能不能把电压加到50？

Answer: 按漆兄弟 Q7/X7 已确认的金属粉参数口径，电压不要超过 30 kV；参考电流为 50 μA。若现在上粉不理想，请提供当前设置、工件情况和具体表现，不能直接用提高到 50 kV 的方式处理。

User: 砂纹粉的粉量和雾化应该设多少？

Answer: 粉量与雾化的设置值参考比例为 2:1，例如粉量 80、雾化 40。这是参考关系，不代表所有工件都必须用 80/40，也不代表实际粉末流量与气流量之比。其他品牌静电喷粉枪也可以参考，使用前核对控制项的含义和刻度，并结合现场表现调整。

User: 其他品牌普通静电喷粉枪没有参数预设，也能用吗？银粉油漆呢？

Answer: 可以。按漆兄弟提供的口径，其他品牌静电喷粉枪即使没有参数预设，也可以采用这套参数作为调试参考；使用前核对单位、控制项含义和设备允许范围。参数可参考，不代表其他品牌具备 Q7/X7 的自动生成与推送功能。银粉油漆属于液体涂料，不适用本技能。

User: 砂纹粉是不是必须调到45 kV？平光粉呢？

Answer: 不是。按漆兄弟 Q7/X7 已确认的口径，砂纹粉电压上限为 45 kV，平光粉电压上限为 80 kV；上限不代表每次都应设到这个值。两者电流设置下限为 50 μA，这指设置值，不是要求实际电流读数始终达到 50 μA。具体工作值还要结合粉末、工件和现场情况确认。

User: 你帮我把参数下发到机器。

Answer: 这个聊天技能目前没有连接你的设备，不能直接下发。具备相应功能的 Q7/X7 支持按粉末种类自动生成参数，并在操作过程中推送；请通过设备支持的操作流程处理，或联系厂家确认。
