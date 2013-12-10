The [Jasmine testing framework](http://pivotal.github.com/jasmine/) from [Pivotal Labs](http://pivotallabs.com/) comes with this [default set of matchers](https://github.com/pivotal/jasmine/wiki/Matchers):

    expect(function(){fn();}).toThrow(e);
    expect(x).toBe(y);
    expect(x).toBeDefined();
    expect(x).toBeFalsy();
    expect(x).toBeGreaterThan(y);
    expect(x).toBeLessThan(y);
    expect(x).toBeNull();
    expect(x).toBeTruthy();
    expect(x).toBeUndefined();
    expect(x).toContain(y);
    expect(x).toEqual(y);
    expect(x).toMatch(pattern);

[jasmine-matchers](https://github.com/goliatone/jasmine-matchers) adds:

    expect(x).toBeArray();
    expect(x).toBeInstanceOf(Constructor);
    expect(x).toBeNan();
    expect(x).toBeOfType(type);
    expect(x).toHaveLength(length);
    expect(x).toHaveLengthGreaterThan(length);
    expect(x).toHaveLengthSmallerThan(length);
    expect(x).toHaveProperties(...properties);
    expect(x).toHaveMethods(...methods);
    expect(x).toHaveOwnMethods(...methods);
    expect(x).toHaveOwnProperties(...properties);
    expect(x).toEachHave(attr, val);
    expect(x).toBeCloneOf(source);
    expect(x).toNotBeCloneOf(source);
    expect(x).toHavePropertieValue(attr, val);
    expect(x).toIncludeObject(object);
    expect(x).toMatchObject(object);
    expect(x).toNotMatchObject(object); //not.toMatchObject(object);
    expect(x).toNotMatch(object);
    expect(x).toMatchLengthOf(object);
    expect(x).toThrowInstanceOf(ExceptionType);
    expect(x).toHaveBeenCalledXTimes(count);
    expect(x).toContainOnce(value);
    expect(x).toEndWith(value);
    expect(x).toEachEndWith(value);
    expect(x).toSomeEndWith(value);