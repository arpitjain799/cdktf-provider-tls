# API Reference <a name="API Reference"></a>

## Constructs <a name="Constructs"></a>

### CertRequest <a name="@cdktf/provider-tls.CertRequest"></a>

Represents a {@link https://www.terraform.io/docs/providers/tls/r/cert_request.html tls_cert_request}.

#### Initializers <a name="@cdktf/provider-tls.CertRequest.Initializer"></a>

```typescript
import { CertRequest } from '@cdktf/provider-tls'

new CertRequest(scope: Construct, id: string, config: CertRequestConfig)
```

##### `scope`<sup>Required</sup> <a name="@cdktf/provider-tls.CertRequest.parameter.scope"></a>

- *Type:* [`constructs.Construct`](#constructs.Construct)

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="@cdktf/provider-tls.CertRequest.parameter.id"></a>

- *Type:* `string`

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Required</sup> <a name="@cdktf/provider-tls.CertRequest.parameter.config"></a>

- *Type:* [`@cdktf/provider-tls.CertRequestConfig`](#@cdktf/provider-tls.CertRequestConfig)

---

#### Methods <a name="Methods"></a>

##### `resetDnsNames` <a name="@cdktf/provider-tls.CertRequest.resetDnsNames"></a>

```typescript
public resetDnsNames()
```

##### `resetIpAddresses` <a name="@cdktf/provider-tls.CertRequest.resetIpAddresses"></a>

```typescript
public resetIpAddresses()
```

##### `resetUris` <a name="@cdktf/provider-tls.CertRequest.resetUris"></a>

```typescript
public resetUris()
```


#### Properties <a name="Properties"></a>

##### `certRequestPem`<sup>Required</sup> <a name="@cdktf/provider-tls.CertRequest.property.certRequestPem"></a>

```typescript
public readonly certRequestPem: string;
```

- *Type:* `string`

---

##### `id`<sup>Required</sup> <a name="@cdktf/provider-tls.CertRequest.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* `string`

---

##### `dnsNamesInput`<sup>Optional</sup> <a name="@cdktf/provider-tls.CertRequest.property.dnsNamesInput"></a>

```typescript
public readonly dnsNamesInput: string[];
```

- *Type:* `string`[]

---

##### `ipAddressesInput`<sup>Optional</sup> <a name="@cdktf/provider-tls.CertRequest.property.ipAddressesInput"></a>

```typescript
public readonly ipAddressesInput: string[];
```

- *Type:* `string`[]

---

##### `keyAlgorithmInput`<sup>Optional</sup> <a name="@cdktf/provider-tls.CertRequest.property.keyAlgorithmInput"></a>

```typescript
public readonly keyAlgorithmInput: string;
```

- *Type:* `string`

---

##### `privateKeyPemInput`<sup>Optional</sup> <a name="@cdktf/provider-tls.CertRequest.property.privateKeyPemInput"></a>

```typescript
public readonly privateKeyPemInput: string;
```

- *Type:* `string`

---

##### `subjectInput`<sup>Optional</sup> <a name="@cdktf/provider-tls.CertRequest.property.subjectInput"></a>

```typescript
public readonly subjectInput: CertRequestSubject[];
```

- *Type:* [`@cdktf/provider-tls.CertRequestSubject`](#@cdktf/provider-tls.CertRequestSubject)[]

---

##### `urisInput`<sup>Optional</sup> <a name="@cdktf/provider-tls.CertRequest.property.urisInput"></a>

```typescript
public readonly urisInput: string[];
```

- *Type:* `string`[]

---

##### `keyAlgorithm`<sup>Required</sup> <a name="@cdktf/provider-tls.CertRequest.property.keyAlgorithm"></a>

```typescript
public readonly keyAlgorithm: string;
```

- *Type:* `string`

---

##### `privateKeyPem`<sup>Required</sup> <a name="@cdktf/provider-tls.CertRequest.property.privateKeyPem"></a>

```typescript
public readonly privateKeyPem: string;
```

- *Type:* `string`

---

##### `subject`<sup>Required</sup> <a name="@cdktf/provider-tls.CertRequest.property.subject"></a>

```typescript
public readonly subject: CertRequestSubject[];
```

- *Type:* [`@cdktf/provider-tls.CertRequestSubject`](#@cdktf/provider-tls.CertRequestSubject)[]

---

##### `dnsNames`<sup>Optional</sup> <a name="@cdktf/provider-tls.CertRequest.property.dnsNames"></a>

```typescript
public readonly dnsNames: string[];
```

- *Type:* `string`[]

---

##### `ipAddresses`<sup>Optional</sup> <a name="@cdktf/provider-tls.CertRequest.property.ipAddresses"></a>

```typescript
public readonly ipAddresses: string[];
```

- *Type:* `string`[]

---

##### `uris`<sup>Optional</sup> <a name="@cdktf/provider-tls.CertRequest.property.uris"></a>

```typescript
public readonly uris: string[];
```

- *Type:* `string`[]

---

#### Constants <a name="Constants"></a>

##### `tfResourceType` <a name="@cdktf/provider-tls.CertRequest.property.tfResourceType"></a>

- *Type:* `string`

---

### DataTlsCertificate <a name="@cdktf/provider-tls.DataTlsCertificate"></a>

Represents a {@link https://www.terraform.io/docs/providers/tls/d/certificate.html tls_certificate}.

#### Initializers <a name="@cdktf/provider-tls.DataTlsCertificate.Initializer"></a>

```typescript
import { DataTlsCertificate } from '@cdktf/provider-tls'

new DataTlsCertificate(scope: Construct, id: string, config: DataTlsCertificateConfig)
```

##### `scope`<sup>Required</sup> <a name="@cdktf/provider-tls.DataTlsCertificate.parameter.scope"></a>

- *Type:* [`constructs.Construct`](#constructs.Construct)

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="@cdktf/provider-tls.DataTlsCertificate.parameter.id"></a>

- *Type:* `string`

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Required</sup> <a name="@cdktf/provider-tls.DataTlsCertificate.parameter.config"></a>

- *Type:* [`@cdktf/provider-tls.DataTlsCertificateConfig`](#@cdktf/provider-tls.DataTlsCertificateConfig)

---

#### Methods <a name="Methods"></a>

##### `certificates` <a name="@cdktf/provider-tls.DataTlsCertificate.certificates"></a>

```typescript
public certificates(index: string)
```

###### `index`<sup>Required</sup> <a name="@cdktf/provider-tls.DataTlsCertificate.parameter.index"></a>

- *Type:* `string`

---

##### `resetVerifyChain` <a name="@cdktf/provider-tls.DataTlsCertificate.resetVerifyChain"></a>

```typescript
public resetVerifyChain()
```


#### Properties <a name="Properties"></a>

##### `id`<sup>Required</sup> <a name="@cdktf/provider-tls.DataTlsCertificate.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* `string`

---

##### `urlInput`<sup>Optional</sup> <a name="@cdktf/provider-tls.DataTlsCertificate.property.urlInput"></a>

```typescript
public readonly urlInput: string;
```

- *Type:* `string`

---

##### `verifyChainInput`<sup>Optional</sup> <a name="@cdktf/provider-tls.DataTlsCertificate.property.verifyChainInput"></a>

```typescript
public readonly verifyChainInput: boolean | IResolvable;
```

- *Type:* `boolean` | [`cdktf.IResolvable`](#cdktf.IResolvable)

---

##### `url`<sup>Required</sup> <a name="@cdktf/provider-tls.DataTlsCertificate.property.url"></a>

```typescript
public readonly url: string;
```

- *Type:* `string`

---

##### `verifyChain`<sup>Optional</sup> <a name="@cdktf/provider-tls.DataTlsCertificate.property.verifyChain"></a>

```typescript
public readonly verifyChain: boolean | IResolvable;
```

- *Type:* `boolean` | [`cdktf.IResolvable`](#cdktf.IResolvable)

---

#### Constants <a name="Constants"></a>

##### `tfResourceType` <a name="@cdktf/provider-tls.DataTlsCertificate.property.tfResourceType"></a>

- *Type:* `string`

---

### DataTlsPublicKey <a name="@cdktf/provider-tls.DataTlsPublicKey"></a>

Represents a {@link https://www.terraform.io/docs/providers/tls/d/public_key.html tls_public_key}.

#### Initializers <a name="@cdktf/provider-tls.DataTlsPublicKey.Initializer"></a>

```typescript
import { DataTlsPublicKey } from '@cdktf/provider-tls'

new DataTlsPublicKey(scope: Construct, id: string, config: DataTlsPublicKeyConfig)
```

##### `scope`<sup>Required</sup> <a name="@cdktf/provider-tls.DataTlsPublicKey.parameter.scope"></a>

- *Type:* [`constructs.Construct`](#constructs.Construct)

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="@cdktf/provider-tls.DataTlsPublicKey.parameter.id"></a>

- *Type:* `string`

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Required</sup> <a name="@cdktf/provider-tls.DataTlsPublicKey.parameter.config"></a>

- *Type:* [`@cdktf/provider-tls.DataTlsPublicKeyConfig`](#@cdktf/provider-tls.DataTlsPublicKeyConfig)

---



#### Properties <a name="Properties"></a>

##### `algorithm`<sup>Required</sup> <a name="@cdktf/provider-tls.DataTlsPublicKey.property.algorithm"></a>

```typescript
public readonly algorithm: string;
```

- *Type:* `string`

---

##### `id`<sup>Required</sup> <a name="@cdktf/provider-tls.DataTlsPublicKey.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* `string`

---

##### `publicKeyFingerprintMd5`<sup>Required</sup> <a name="@cdktf/provider-tls.DataTlsPublicKey.property.publicKeyFingerprintMd5"></a>

```typescript
public readonly publicKeyFingerprintMd5: string;
```

- *Type:* `string`

---

##### `publicKeyOpenssh`<sup>Required</sup> <a name="@cdktf/provider-tls.DataTlsPublicKey.property.publicKeyOpenssh"></a>

```typescript
public readonly publicKeyOpenssh: string;
```

- *Type:* `string`

---

##### `publicKeyPem`<sup>Required</sup> <a name="@cdktf/provider-tls.DataTlsPublicKey.property.publicKeyPem"></a>

```typescript
public readonly publicKeyPem: string;
```

- *Type:* `string`

---

##### `privateKeyPemInput`<sup>Optional</sup> <a name="@cdktf/provider-tls.DataTlsPublicKey.property.privateKeyPemInput"></a>

```typescript
public readonly privateKeyPemInput: string;
```

- *Type:* `string`

---

##### `privateKeyPem`<sup>Required</sup> <a name="@cdktf/provider-tls.DataTlsPublicKey.property.privateKeyPem"></a>

```typescript
public readonly privateKeyPem: string;
```

- *Type:* `string`

---

#### Constants <a name="Constants"></a>

##### `tfResourceType` <a name="@cdktf/provider-tls.DataTlsPublicKey.property.tfResourceType"></a>

- *Type:* `string`

---

### LocallySignedCert <a name="@cdktf/provider-tls.LocallySignedCert"></a>

Represents a {@link https://www.terraform.io/docs/providers/tls/r/locally_signed_cert.html tls_locally_signed_cert}.

#### Initializers <a name="@cdktf/provider-tls.LocallySignedCert.Initializer"></a>

```typescript
import { LocallySignedCert } from '@cdktf/provider-tls'

new LocallySignedCert(scope: Construct, id: string, config: LocallySignedCertConfig)
```

##### `scope`<sup>Required</sup> <a name="@cdktf/provider-tls.LocallySignedCert.parameter.scope"></a>

- *Type:* [`constructs.Construct`](#constructs.Construct)

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="@cdktf/provider-tls.LocallySignedCert.parameter.id"></a>

- *Type:* `string`

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Required</sup> <a name="@cdktf/provider-tls.LocallySignedCert.parameter.config"></a>

- *Type:* [`@cdktf/provider-tls.LocallySignedCertConfig`](#@cdktf/provider-tls.LocallySignedCertConfig)

---

#### Methods <a name="Methods"></a>

##### `resetEarlyRenewalHours` <a name="@cdktf/provider-tls.LocallySignedCert.resetEarlyRenewalHours"></a>

```typescript
public resetEarlyRenewalHours()
```

##### `resetIsCaCertificate` <a name="@cdktf/provider-tls.LocallySignedCert.resetIsCaCertificate"></a>

```typescript
public resetIsCaCertificate()
```

##### `resetSetSubjectKeyId` <a name="@cdktf/provider-tls.LocallySignedCert.resetSetSubjectKeyId"></a>

```typescript
public resetSetSubjectKeyId()
```


#### Properties <a name="Properties"></a>

##### `certPem`<sup>Required</sup> <a name="@cdktf/provider-tls.LocallySignedCert.property.certPem"></a>

```typescript
public readonly certPem: string;
```

- *Type:* `string`

---

##### `id`<sup>Required</sup> <a name="@cdktf/provider-tls.LocallySignedCert.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* `string`

---

##### `readyForRenewal`<sup>Required</sup> <a name="@cdktf/provider-tls.LocallySignedCert.property.readyForRenewal"></a>

```typescript
public readonly readyForRenewal: any;
```

- *Type:* `any`

---

##### `validityEndTime`<sup>Required</sup> <a name="@cdktf/provider-tls.LocallySignedCert.property.validityEndTime"></a>

```typescript
public readonly validityEndTime: string;
```

- *Type:* `string`

---

##### `validityStartTime`<sup>Required</sup> <a name="@cdktf/provider-tls.LocallySignedCert.property.validityStartTime"></a>

```typescript
public readonly validityStartTime: string;
```

- *Type:* `string`

---

##### `allowedUsesInput`<sup>Optional</sup> <a name="@cdktf/provider-tls.LocallySignedCert.property.allowedUsesInput"></a>

```typescript
public readonly allowedUsesInput: string[];
```

- *Type:* `string`[]

---

##### `caCertPemInput`<sup>Optional</sup> <a name="@cdktf/provider-tls.LocallySignedCert.property.caCertPemInput"></a>

```typescript
public readonly caCertPemInput: string;
```

- *Type:* `string`

---

##### `caKeyAlgorithmInput`<sup>Optional</sup> <a name="@cdktf/provider-tls.LocallySignedCert.property.caKeyAlgorithmInput"></a>

```typescript
public readonly caKeyAlgorithmInput: string;
```

- *Type:* `string`

---

##### `caPrivateKeyPemInput`<sup>Optional</sup> <a name="@cdktf/provider-tls.LocallySignedCert.property.caPrivateKeyPemInput"></a>

```typescript
public readonly caPrivateKeyPemInput: string;
```

- *Type:* `string`

---

##### `certRequestPemInput`<sup>Optional</sup> <a name="@cdktf/provider-tls.LocallySignedCert.property.certRequestPemInput"></a>

```typescript
public readonly certRequestPemInput: string;
```

- *Type:* `string`

---

##### `earlyRenewalHoursInput`<sup>Optional</sup> <a name="@cdktf/provider-tls.LocallySignedCert.property.earlyRenewalHoursInput"></a>

```typescript
public readonly earlyRenewalHoursInput: number;
```

- *Type:* `number`

---

##### `isCaCertificateInput`<sup>Optional</sup> <a name="@cdktf/provider-tls.LocallySignedCert.property.isCaCertificateInput"></a>

```typescript
public readonly isCaCertificateInput: boolean | IResolvable;
```

- *Type:* `boolean` | [`cdktf.IResolvable`](#cdktf.IResolvable)

---

##### `setSubjectKeyIdInput`<sup>Optional</sup> <a name="@cdktf/provider-tls.LocallySignedCert.property.setSubjectKeyIdInput"></a>

```typescript
public readonly setSubjectKeyIdInput: boolean | IResolvable;
```

- *Type:* `boolean` | [`cdktf.IResolvable`](#cdktf.IResolvable)

---

##### `validityPeriodHoursInput`<sup>Optional</sup> <a name="@cdktf/provider-tls.LocallySignedCert.property.validityPeriodHoursInput"></a>

```typescript
public readonly validityPeriodHoursInput: number;
```

- *Type:* `number`

---

##### `allowedUses`<sup>Required</sup> <a name="@cdktf/provider-tls.LocallySignedCert.property.allowedUses"></a>

```typescript
public readonly allowedUses: string[];
```

- *Type:* `string`[]

---

##### `caCertPem`<sup>Required</sup> <a name="@cdktf/provider-tls.LocallySignedCert.property.caCertPem"></a>

```typescript
public readonly caCertPem: string;
```

- *Type:* `string`

---

##### `caKeyAlgorithm`<sup>Required</sup> <a name="@cdktf/provider-tls.LocallySignedCert.property.caKeyAlgorithm"></a>

```typescript
public readonly caKeyAlgorithm: string;
```

- *Type:* `string`

---

##### `caPrivateKeyPem`<sup>Required</sup> <a name="@cdktf/provider-tls.LocallySignedCert.property.caPrivateKeyPem"></a>

```typescript
public readonly caPrivateKeyPem: string;
```

- *Type:* `string`

---

##### `certRequestPem`<sup>Required</sup> <a name="@cdktf/provider-tls.LocallySignedCert.property.certRequestPem"></a>

```typescript
public readonly certRequestPem: string;
```

- *Type:* `string`

---

##### `validityPeriodHours`<sup>Required</sup> <a name="@cdktf/provider-tls.LocallySignedCert.property.validityPeriodHours"></a>

```typescript
public readonly validityPeriodHours: number;
```

- *Type:* `number`

---

##### `earlyRenewalHours`<sup>Optional</sup> <a name="@cdktf/provider-tls.LocallySignedCert.property.earlyRenewalHours"></a>

```typescript
public readonly earlyRenewalHours: number;
```

- *Type:* `number`

---

##### `isCaCertificate`<sup>Optional</sup> <a name="@cdktf/provider-tls.LocallySignedCert.property.isCaCertificate"></a>

```typescript
public readonly isCaCertificate: boolean | IResolvable;
```

- *Type:* `boolean` | [`cdktf.IResolvable`](#cdktf.IResolvable)

---

##### `setSubjectKeyId`<sup>Optional</sup> <a name="@cdktf/provider-tls.LocallySignedCert.property.setSubjectKeyId"></a>

```typescript
public readonly setSubjectKeyId: boolean | IResolvable;
```

- *Type:* `boolean` | [`cdktf.IResolvable`](#cdktf.IResolvable)

---

#### Constants <a name="Constants"></a>

##### `tfResourceType` <a name="@cdktf/provider-tls.LocallySignedCert.property.tfResourceType"></a>

- *Type:* `string`

---

### PrivateKey <a name="@cdktf/provider-tls.PrivateKey"></a>

Represents a {@link https://www.terraform.io/docs/providers/tls/r/private_key.html tls_private_key}.

#### Initializers <a name="@cdktf/provider-tls.PrivateKey.Initializer"></a>

```typescript
import { PrivateKey } from '@cdktf/provider-tls'

new PrivateKey(scope: Construct, id: string, config: PrivateKeyConfig)
```

##### `scope`<sup>Required</sup> <a name="@cdktf/provider-tls.PrivateKey.parameter.scope"></a>

- *Type:* [`constructs.Construct`](#constructs.Construct)

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="@cdktf/provider-tls.PrivateKey.parameter.id"></a>

- *Type:* `string`

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Required</sup> <a name="@cdktf/provider-tls.PrivateKey.parameter.config"></a>

- *Type:* [`@cdktf/provider-tls.PrivateKeyConfig`](#@cdktf/provider-tls.PrivateKeyConfig)

---

#### Methods <a name="Methods"></a>

##### `resetEcdsaCurve` <a name="@cdktf/provider-tls.PrivateKey.resetEcdsaCurve"></a>

```typescript
public resetEcdsaCurve()
```

##### `resetRsaBits` <a name="@cdktf/provider-tls.PrivateKey.resetRsaBits"></a>

```typescript
public resetRsaBits()
```


#### Properties <a name="Properties"></a>

##### `id`<sup>Required</sup> <a name="@cdktf/provider-tls.PrivateKey.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* `string`

---

##### `privateKeyPem`<sup>Required</sup> <a name="@cdktf/provider-tls.PrivateKey.property.privateKeyPem"></a>

```typescript
public readonly privateKeyPem: string;
```

- *Type:* `string`

---

##### `publicKeyFingerprintMd5`<sup>Required</sup> <a name="@cdktf/provider-tls.PrivateKey.property.publicKeyFingerprintMd5"></a>

```typescript
public readonly publicKeyFingerprintMd5: string;
```

- *Type:* `string`

---

##### `publicKeyOpenssh`<sup>Required</sup> <a name="@cdktf/provider-tls.PrivateKey.property.publicKeyOpenssh"></a>

```typescript
public readonly publicKeyOpenssh: string;
```

- *Type:* `string`

---

##### `publicKeyPem`<sup>Required</sup> <a name="@cdktf/provider-tls.PrivateKey.property.publicKeyPem"></a>

```typescript
public readonly publicKeyPem: string;
```

- *Type:* `string`

---

##### `algorithmInput`<sup>Optional</sup> <a name="@cdktf/provider-tls.PrivateKey.property.algorithmInput"></a>

```typescript
public readonly algorithmInput: string;
```

- *Type:* `string`

---

##### `ecdsaCurveInput`<sup>Optional</sup> <a name="@cdktf/provider-tls.PrivateKey.property.ecdsaCurveInput"></a>

```typescript
public readonly ecdsaCurveInput: string;
```

- *Type:* `string`

---

##### `rsaBitsInput`<sup>Optional</sup> <a name="@cdktf/provider-tls.PrivateKey.property.rsaBitsInput"></a>

```typescript
public readonly rsaBitsInput: number;
```

- *Type:* `number`

---

##### `algorithm`<sup>Required</sup> <a name="@cdktf/provider-tls.PrivateKey.property.algorithm"></a>

```typescript
public readonly algorithm: string;
```

- *Type:* `string`

---

##### `ecdsaCurve`<sup>Optional</sup> <a name="@cdktf/provider-tls.PrivateKey.property.ecdsaCurve"></a>

```typescript
public readonly ecdsaCurve: string;
```

- *Type:* `string`

---

##### `rsaBits`<sup>Optional</sup> <a name="@cdktf/provider-tls.PrivateKey.property.rsaBits"></a>

```typescript
public readonly rsaBits: number;
```

- *Type:* `number`

---

#### Constants <a name="Constants"></a>

##### `tfResourceType` <a name="@cdktf/provider-tls.PrivateKey.property.tfResourceType"></a>

- *Type:* `string`

---

### SelfSignedCert <a name="@cdktf/provider-tls.SelfSignedCert"></a>

Represents a {@link https://www.terraform.io/docs/providers/tls/r/self_signed_cert.html tls_self_signed_cert}.

#### Initializers <a name="@cdktf/provider-tls.SelfSignedCert.Initializer"></a>

```typescript
import { SelfSignedCert } from '@cdktf/provider-tls'

new SelfSignedCert(scope: Construct, id: string, config: SelfSignedCertConfig)
```

##### `scope`<sup>Required</sup> <a name="@cdktf/provider-tls.SelfSignedCert.parameter.scope"></a>

- *Type:* [`constructs.Construct`](#constructs.Construct)

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="@cdktf/provider-tls.SelfSignedCert.parameter.id"></a>

- *Type:* `string`

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Required</sup> <a name="@cdktf/provider-tls.SelfSignedCert.parameter.config"></a>

- *Type:* [`@cdktf/provider-tls.SelfSignedCertConfig`](#@cdktf/provider-tls.SelfSignedCertConfig)

---

#### Methods <a name="Methods"></a>

##### `resetDnsNames` <a name="@cdktf/provider-tls.SelfSignedCert.resetDnsNames"></a>

```typescript
public resetDnsNames()
```

##### `resetEarlyRenewalHours` <a name="@cdktf/provider-tls.SelfSignedCert.resetEarlyRenewalHours"></a>

```typescript
public resetEarlyRenewalHours()
```

##### `resetIpAddresses` <a name="@cdktf/provider-tls.SelfSignedCert.resetIpAddresses"></a>

```typescript
public resetIpAddresses()
```

##### `resetIsCaCertificate` <a name="@cdktf/provider-tls.SelfSignedCert.resetIsCaCertificate"></a>

```typescript
public resetIsCaCertificate()
```

##### `resetSetSubjectKeyId` <a name="@cdktf/provider-tls.SelfSignedCert.resetSetSubjectKeyId"></a>

```typescript
public resetSetSubjectKeyId()
```

##### `resetUris` <a name="@cdktf/provider-tls.SelfSignedCert.resetUris"></a>

```typescript
public resetUris()
```


#### Properties <a name="Properties"></a>

##### `certPem`<sup>Required</sup> <a name="@cdktf/provider-tls.SelfSignedCert.property.certPem"></a>

```typescript
public readonly certPem: string;
```

- *Type:* `string`

---

##### `id`<sup>Required</sup> <a name="@cdktf/provider-tls.SelfSignedCert.property.id"></a>

```typescript
public readonly id: string;
```

- *Type:* `string`

---

##### `readyForRenewal`<sup>Required</sup> <a name="@cdktf/provider-tls.SelfSignedCert.property.readyForRenewal"></a>

```typescript
public readonly readyForRenewal: any;
```

- *Type:* `any`

---

##### `validityEndTime`<sup>Required</sup> <a name="@cdktf/provider-tls.SelfSignedCert.property.validityEndTime"></a>

```typescript
public readonly validityEndTime: string;
```

- *Type:* `string`

---

##### `validityStartTime`<sup>Required</sup> <a name="@cdktf/provider-tls.SelfSignedCert.property.validityStartTime"></a>

```typescript
public readonly validityStartTime: string;
```

- *Type:* `string`

---

##### `allowedUsesInput`<sup>Optional</sup> <a name="@cdktf/provider-tls.SelfSignedCert.property.allowedUsesInput"></a>

```typescript
public readonly allowedUsesInput: string[];
```

- *Type:* `string`[]

---

##### `dnsNamesInput`<sup>Optional</sup> <a name="@cdktf/provider-tls.SelfSignedCert.property.dnsNamesInput"></a>

```typescript
public readonly dnsNamesInput: string[];
```

- *Type:* `string`[]

---

##### `earlyRenewalHoursInput`<sup>Optional</sup> <a name="@cdktf/provider-tls.SelfSignedCert.property.earlyRenewalHoursInput"></a>

```typescript
public readonly earlyRenewalHoursInput: number;
```

- *Type:* `number`

---

##### `ipAddressesInput`<sup>Optional</sup> <a name="@cdktf/provider-tls.SelfSignedCert.property.ipAddressesInput"></a>

```typescript
public readonly ipAddressesInput: string[];
```

- *Type:* `string`[]

---

##### `isCaCertificateInput`<sup>Optional</sup> <a name="@cdktf/provider-tls.SelfSignedCert.property.isCaCertificateInput"></a>

```typescript
public readonly isCaCertificateInput: boolean | IResolvable;
```

- *Type:* `boolean` | [`cdktf.IResolvable`](#cdktf.IResolvable)

---

##### `keyAlgorithmInput`<sup>Optional</sup> <a name="@cdktf/provider-tls.SelfSignedCert.property.keyAlgorithmInput"></a>

```typescript
public readonly keyAlgorithmInput: string;
```

- *Type:* `string`

---

##### `privateKeyPemInput`<sup>Optional</sup> <a name="@cdktf/provider-tls.SelfSignedCert.property.privateKeyPemInput"></a>

```typescript
public readonly privateKeyPemInput: string;
```

- *Type:* `string`

---

##### `setSubjectKeyIdInput`<sup>Optional</sup> <a name="@cdktf/provider-tls.SelfSignedCert.property.setSubjectKeyIdInput"></a>

```typescript
public readonly setSubjectKeyIdInput: boolean | IResolvable;
```

- *Type:* `boolean` | [`cdktf.IResolvable`](#cdktf.IResolvable)

---

##### `subjectInput`<sup>Optional</sup> <a name="@cdktf/provider-tls.SelfSignedCert.property.subjectInput"></a>

```typescript
public readonly subjectInput: SelfSignedCertSubject[];
```

- *Type:* [`@cdktf/provider-tls.SelfSignedCertSubject`](#@cdktf/provider-tls.SelfSignedCertSubject)[]

---

##### `urisInput`<sup>Optional</sup> <a name="@cdktf/provider-tls.SelfSignedCert.property.urisInput"></a>

```typescript
public readonly urisInput: string[];
```

- *Type:* `string`[]

---

##### `validityPeriodHoursInput`<sup>Optional</sup> <a name="@cdktf/provider-tls.SelfSignedCert.property.validityPeriodHoursInput"></a>

```typescript
public readonly validityPeriodHoursInput: number;
```

- *Type:* `number`

---

##### `allowedUses`<sup>Required</sup> <a name="@cdktf/provider-tls.SelfSignedCert.property.allowedUses"></a>

```typescript
public readonly allowedUses: string[];
```

- *Type:* `string`[]

---

##### `keyAlgorithm`<sup>Required</sup> <a name="@cdktf/provider-tls.SelfSignedCert.property.keyAlgorithm"></a>

```typescript
public readonly keyAlgorithm: string;
```

- *Type:* `string`

---

##### `privateKeyPem`<sup>Required</sup> <a name="@cdktf/provider-tls.SelfSignedCert.property.privateKeyPem"></a>

```typescript
public readonly privateKeyPem: string;
```

- *Type:* `string`

---

##### `subject`<sup>Required</sup> <a name="@cdktf/provider-tls.SelfSignedCert.property.subject"></a>

```typescript
public readonly subject: SelfSignedCertSubject[];
```

- *Type:* [`@cdktf/provider-tls.SelfSignedCertSubject`](#@cdktf/provider-tls.SelfSignedCertSubject)[]

---

##### `validityPeriodHours`<sup>Required</sup> <a name="@cdktf/provider-tls.SelfSignedCert.property.validityPeriodHours"></a>

```typescript
public readonly validityPeriodHours: number;
```

- *Type:* `number`

---

##### `dnsNames`<sup>Optional</sup> <a name="@cdktf/provider-tls.SelfSignedCert.property.dnsNames"></a>

```typescript
public readonly dnsNames: string[];
```

- *Type:* `string`[]

---

##### `earlyRenewalHours`<sup>Optional</sup> <a name="@cdktf/provider-tls.SelfSignedCert.property.earlyRenewalHours"></a>

```typescript
public readonly earlyRenewalHours: number;
```

- *Type:* `number`

---

##### `ipAddresses`<sup>Optional</sup> <a name="@cdktf/provider-tls.SelfSignedCert.property.ipAddresses"></a>

```typescript
public readonly ipAddresses: string[];
```

- *Type:* `string`[]

---

##### `isCaCertificate`<sup>Optional</sup> <a name="@cdktf/provider-tls.SelfSignedCert.property.isCaCertificate"></a>

```typescript
public readonly isCaCertificate: boolean | IResolvable;
```

- *Type:* `boolean` | [`cdktf.IResolvable`](#cdktf.IResolvable)

---

##### `setSubjectKeyId`<sup>Optional</sup> <a name="@cdktf/provider-tls.SelfSignedCert.property.setSubjectKeyId"></a>

```typescript
public readonly setSubjectKeyId: boolean | IResolvable;
```

- *Type:* `boolean` | [`cdktf.IResolvable`](#cdktf.IResolvable)

---

##### `uris`<sup>Optional</sup> <a name="@cdktf/provider-tls.SelfSignedCert.property.uris"></a>

```typescript
public readonly uris: string[];
```

- *Type:* `string`[]

---

#### Constants <a name="Constants"></a>

##### `tfResourceType` <a name="@cdktf/provider-tls.SelfSignedCert.property.tfResourceType"></a>

- *Type:* `string`

---

### TlsProvider <a name="@cdktf/provider-tls.TlsProvider"></a>

Represents a {@link https://www.terraform.io/docs/providers/tls tls}.

#### Initializers <a name="@cdktf/provider-tls.TlsProvider.Initializer"></a>

```typescript
import { TlsProvider } from '@cdktf/provider-tls'

new TlsProvider(scope: Construct, id: string, config?: TlsProviderConfig)
```

##### `scope`<sup>Required</sup> <a name="@cdktf/provider-tls.TlsProvider.parameter.scope"></a>

- *Type:* [`constructs.Construct`](#constructs.Construct)

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="@cdktf/provider-tls.TlsProvider.parameter.id"></a>

- *Type:* `string`

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `config`<sup>Optional</sup> <a name="@cdktf/provider-tls.TlsProvider.parameter.config"></a>

- *Type:* [`@cdktf/provider-tls.TlsProviderConfig`](#@cdktf/provider-tls.TlsProviderConfig)

---

#### Methods <a name="Methods"></a>

##### `resetAlias` <a name="@cdktf/provider-tls.TlsProvider.resetAlias"></a>

```typescript
public resetAlias()
```


#### Properties <a name="Properties"></a>

##### `aliasInput`<sup>Optional</sup> <a name="@cdktf/provider-tls.TlsProvider.property.aliasInput"></a>

```typescript
public readonly aliasInput: string;
```

- *Type:* `string`

---

##### `alias`<sup>Optional</sup> <a name="@cdktf/provider-tls.TlsProvider.property.alias"></a>

```typescript
public readonly alias: string;
```

- *Type:* `string`

---

#### Constants <a name="Constants"></a>

##### `tfResourceType` <a name="@cdktf/provider-tls.TlsProvider.property.tfResourceType"></a>

- *Type:* `string`

---

## Structs <a name="Structs"></a>

### CertRequestConfig <a name="@cdktf/provider-tls.CertRequestConfig"></a>

#### Initializer <a name="[object Object].Initializer"></a>

```typescript
import { CertRequestConfig } from '@cdktf/provider-tls'

const certRequestConfig: CertRequestConfig = { ... }
```

##### `count`<sup>Optional</sup> <a name="@cdktf/provider-tls.CertRequestConfig.property.count"></a>

```typescript
public readonly count: number | IResolvable;
```

- *Type:* `number` | [`cdktf.IResolvable`](#cdktf.IResolvable)

---

##### `dependsOn`<sup>Optional</sup> <a name="@cdktf/provider-tls.CertRequestConfig.property.dependsOn"></a>

```typescript
public readonly dependsOn: ITerraformDependable[];
```

- *Type:* [`cdktf.ITerraformDependable`](#cdktf.ITerraformDependable)[]

---

##### `lifecycle`<sup>Optional</sup> <a name="@cdktf/provider-tls.CertRequestConfig.property.lifecycle"></a>

```typescript
public readonly lifecycle: TerraformResourceLifecycle;
```

- *Type:* [`cdktf.TerraformResourceLifecycle`](#cdktf.TerraformResourceLifecycle)

---

##### `provider`<sup>Optional</sup> <a name="@cdktf/provider-tls.CertRequestConfig.property.provider"></a>

```typescript
public readonly provider: TerraformProvider;
```

- *Type:* [`cdktf.TerraformProvider`](#cdktf.TerraformProvider)

---

##### `keyAlgorithm`<sup>Required</sup> <a name="@cdktf/provider-tls.CertRequestConfig.property.keyAlgorithm"></a>

```typescript
public readonly keyAlgorithm: string;
```

- *Type:* `string`

Name of the algorithm to use to generate the certificate's private key.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/cert_request.html#key_algorithm CertRequest#key_algorithm}

---

##### `privateKeyPem`<sup>Required</sup> <a name="@cdktf/provider-tls.CertRequestConfig.property.privateKeyPem"></a>

```typescript
public readonly privateKeyPem: string;
```

- *Type:* `string`

PEM-encoded private key that the certificate will belong to.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/cert_request.html#private_key_pem CertRequest#private_key_pem}

---

##### `subject`<sup>Required</sup> <a name="@cdktf/provider-tls.CertRequestConfig.property.subject"></a>

```typescript
public readonly subject: CertRequestSubject[];
```

- *Type:* [`@cdktf/provider-tls.CertRequestSubject`](#@cdktf/provider-tls.CertRequestSubject)[]

subject block.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/cert_request.html#subject CertRequest#subject}

---

##### `dnsNames`<sup>Optional</sup> <a name="@cdktf/provider-tls.CertRequestConfig.property.dnsNames"></a>

```typescript
public readonly dnsNames: string[];
```

- *Type:* `string`[]

List of DNS names to use as subjects of the certificate.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/cert_request.html#dns_names CertRequest#dns_names}

---

##### `ipAddresses`<sup>Optional</sup> <a name="@cdktf/provider-tls.CertRequestConfig.property.ipAddresses"></a>

```typescript
public readonly ipAddresses: string[];
```

- *Type:* `string`[]

List of IP addresses to use as subjects of the certificate.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/cert_request.html#ip_addresses CertRequest#ip_addresses}

---

##### `uris`<sup>Optional</sup> <a name="@cdktf/provider-tls.CertRequestConfig.property.uris"></a>

```typescript
public readonly uris: string[];
```

- *Type:* `string`[]

List of URIs to use as subjects of the certificate.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/cert_request.html#uris CertRequest#uris}

---

### CertRequestSubject <a name="@cdktf/provider-tls.CertRequestSubject"></a>

#### Initializer <a name="[object Object].Initializer"></a>

```typescript
import { CertRequestSubject } from '@cdktf/provider-tls'

const certRequestSubject: CertRequestSubject = { ... }
```

##### `commonName`<sup>Optional</sup> <a name="@cdktf/provider-tls.CertRequestSubject.property.commonName"></a>

```typescript
public readonly commonName: string;
```

- *Type:* `string`

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/cert_request.html#common_name CertRequest#common_name}.

---

##### `country`<sup>Optional</sup> <a name="@cdktf/provider-tls.CertRequestSubject.property.country"></a>

```typescript
public readonly country: string;
```

- *Type:* `string`

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/cert_request.html#country CertRequest#country}.

---

##### `locality`<sup>Optional</sup> <a name="@cdktf/provider-tls.CertRequestSubject.property.locality"></a>

```typescript
public readonly locality: string;
```

- *Type:* `string`

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/cert_request.html#locality CertRequest#locality}.

---

##### `organization`<sup>Optional</sup> <a name="@cdktf/provider-tls.CertRequestSubject.property.organization"></a>

```typescript
public readonly organization: string;
```

- *Type:* `string`

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/cert_request.html#organization CertRequest#organization}.

---

##### `organizationalUnit`<sup>Optional</sup> <a name="@cdktf/provider-tls.CertRequestSubject.property.organizationalUnit"></a>

```typescript
public readonly organizationalUnit: string;
```

- *Type:* `string`

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/cert_request.html#organizational_unit CertRequest#organizational_unit}.

---

##### `postalCode`<sup>Optional</sup> <a name="@cdktf/provider-tls.CertRequestSubject.property.postalCode"></a>

```typescript
public readonly postalCode: string;
```

- *Type:* `string`

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/cert_request.html#postal_code CertRequest#postal_code}.

---

##### `province`<sup>Optional</sup> <a name="@cdktf/provider-tls.CertRequestSubject.property.province"></a>

```typescript
public readonly province: string;
```

- *Type:* `string`

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/cert_request.html#province CertRequest#province}.

---

##### `serialNumber`<sup>Optional</sup> <a name="@cdktf/provider-tls.CertRequestSubject.property.serialNumber"></a>

```typescript
public readonly serialNumber: string;
```

- *Type:* `string`

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/cert_request.html#serial_number CertRequest#serial_number}.

---

##### `streetAddress`<sup>Optional</sup> <a name="@cdktf/provider-tls.CertRequestSubject.property.streetAddress"></a>

```typescript
public readonly streetAddress: string[];
```

- *Type:* `string`[]

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/cert_request.html#street_address CertRequest#street_address}.

---

### DataTlsCertificateConfig <a name="@cdktf/provider-tls.DataTlsCertificateConfig"></a>

#### Initializer <a name="[object Object].Initializer"></a>

```typescript
import { DataTlsCertificateConfig } from '@cdktf/provider-tls'

const dataTlsCertificateConfig: DataTlsCertificateConfig = { ... }
```

##### `count`<sup>Optional</sup> <a name="@cdktf/provider-tls.DataTlsCertificateConfig.property.count"></a>

```typescript
public readonly count: number | IResolvable;
```

- *Type:* `number` | [`cdktf.IResolvable`](#cdktf.IResolvable)

---

##### `dependsOn`<sup>Optional</sup> <a name="@cdktf/provider-tls.DataTlsCertificateConfig.property.dependsOn"></a>

```typescript
public readonly dependsOn: ITerraformDependable[];
```

- *Type:* [`cdktf.ITerraformDependable`](#cdktf.ITerraformDependable)[]

---

##### `lifecycle`<sup>Optional</sup> <a name="@cdktf/provider-tls.DataTlsCertificateConfig.property.lifecycle"></a>

```typescript
public readonly lifecycle: TerraformResourceLifecycle;
```

- *Type:* [`cdktf.TerraformResourceLifecycle`](#cdktf.TerraformResourceLifecycle)

---

##### `provider`<sup>Optional</sup> <a name="@cdktf/provider-tls.DataTlsCertificateConfig.property.provider"></a>

```typescript
public readonly provider: TerraformProvider;
```

- *Type:* [`cdktf.TerraformProvider`](#cdktf.TerraformProvider)

---

##### `url`<sup>Required</sup> <a name="@cdktf/provider-tls.DataTlsCertificateConfig.property.url"></a>

```typescript
public readonly url: string;
```

- *Type:* `string`

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/d/certificate.html#url DataTlsCertificate#url}.

---

##### `verifyChain`<sup>Optional</sup> <a name="@cdktf/provider-tls.DataTlsCertificateConfig.property.verifyChain"></a>

```typescript
public readonly verifyChain: boolean | IResolvable;
```

- *Type:* `boolean` | [`cdktf.IResolvable`](#cdktf.IResolvable)

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/d/certificate.html#verify_chain DataTlsCertificate#verify_chain}.

---

### DataTlsPublicKeyConfig <a name="@cdktf/provider-tls.DataTlsPublicKeyConfig"></a>

#### Initializer <a name="[object Object].Initializer"></a>

```typescript
import { DataTlsPublicKeyConfig } from '@cdktf/provider-tls'

const dataTlsPublicKeyConfig: DataTlsPublicKeyConfig = { ... }
```

##### `count`<sup>Optional</sup> <a name="@cdktf/provider-tls.DataTlsPublicKeyConfig.property.count"></a>

```typescript
public readonly count: number | IResolvable;
```

- *Type:* `number` | [`cdktf.IResolvable`](#cdktf.IResolvable)

---

##### `dependsOn`<sup>Optional</sup> <a name="@cdktf/provider-tls.DataTlsPublicKeyConfig.property.dependsOn"></a>

```typescript
public readonly dependsOn: ITerraformDependable[];
```

- *Type:* [`cdktf.ITerraformDependable`](#cdktf.ITerraformDependable)[]

---

##### `lifecycle`<sup>Optional</sup> <a name="@cdktf/provider-tls.DataTlsPublicKeyConfig.property.lifecycle"></a>

```typescript
public readonly lifecycle: TerraformResourceLifecycle;
```

- *Type:* [`cdktf.TerraformResourceLifecycle`](#cdktf.TerraformResourceLifecycle)

---

##### `provider`<sup>Optional</sup> <a name="@cdktf/provider-tls.DataTlsPublicKeyConfig.property.provider"></a>

```typescript
public readonly provider: TerraformProvider;
```

- *Type:* [`cdktf.TerraformProvider`](#cdktf.TerraformProvider)

---

##### `privateKeyPem`<sup>Required</sup> <a name="@cdktf/provider-tls.DataTlsPublicKeyConfig.property.privateKeyPem"></a>

```typescript
public readonly privateKeyPem: string;
```

- *Type:* `string`

PEM formatted string to use as the private key.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/d/public_key.html#private_key_pem DataTlsPublicKey#private_key_pem}

---

### LocallySignedCertConfig <a name="@cdktf/provider-tls.LocallySignedCertConfig"></a>

#### Initializer <a name="[object Object].Initializer"></a>

```typescript
import { LocallySignedCertConfig } from '@cdktf/provider-tls'

const locallySignedCertConfig: LocallySignedCertConfig = { ... }
```

##### `count`<sup>Optional</sup> <a name="@cdktf/provider-tls.LocallySignedCertConfig.property.count"></a>

```typescript
public readonly count: number | IResolvable;
```

- *Type:* `number` | [`cdktf.IResolvable`](#cdktf.IResolvable)

---

##### `dependsOn`<sup>Optional</sup> <a name="@cdktf/provider-tls.LocallySignedCertConfig.property.dependsOn"></a>

```typescript
public readonly dependsOn: ITerraformDependable[];
```

- *Type:* [`cdktf.ITerraformDependable`](#cdktf.ITerraformDependable)[]

---

##### `lifecycle`<sup>Optional</sup> <a name="@cdktf/provider-tls.LocallySignedCertConfig.property.lifecycle"></a>

```typescript
public readonly lifecycle: TerraformResourceLifecycle;
```

- *Type:* [`cdktf.TerraformResourceLifecycle`](#cdktf.TerraformResourceLifecycle)

---

##### `provider`<sup>Optional</sup> <a name="@cdktf/provider-tls.LocallySignedCertConfig.property.provider"></a>

```typescript
public readonly provider: TerraformProvider;
```

- *Type:* [`cdktf.TerraformProvider`](#cdktf.TerraformProvider)

---

##### `allowedUses`<sup>Required</sup> <a name="@cdktf/provider-tls.LocallySignedCertConfig.property.allowedUses"></a>

```typescript
public readonly allowedUses: string[];
```

- *Type:* `string`[]

Uses that are allowed for the certificate.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/locally_signed_cert.html#allowed_uses LocallySignedCert#allowed_uses}

---

##### `caCertPem`<sup>Required</sup> <a name="@cdktf/provider-tls.LocallySignedCertConfig.property.caCertPem"></a>

```typescript
public readonly caCertPem: string;
```

- *Type:* `string`

PEM-encoded CA certificate.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/locally_signed_cert.html#ca_cert_pem LocallySignedCert#ca_cert_pem}

---

##### `caKeyAlgorithm`<sup>Required</sup> <a name="@cdktf/provider-tls.LocallySignedCertConfig.property.caKeyAlgorithm"></a>

```typescript
public readonly caKeyAlgorithm: string;
```

- *Type:* `string`

Name of the algorithm used to generate the certificate's private key.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/locally_signed_cert.html#ca_key_algorithm LocallySignedCert#ca_key_algorithm}

---

##### `caPrivateKeyPem`<sup>Required</sup> <a name="@cdktf/provider-tls.LocallySignedCertConfig.property.caPrivateKeyPem"></a>

```typescript
public readonly caPrivateKeyPem: string;
```

- *Type:* `string`

PEM-encoded CA private key used to sign the certificate.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/locally_signed_cert.html#ca_private_key_pem LocallySignedCert#ca_private_key_pem}

---

##### `certRequestPem`<sup>Required</sup> <a name="@cdktf/provider-tls.LocallySignedCertConfig.property.certRequestPem"></a>

```typescript
public readonly certRequestPem: string;
```

- *Type:* `string`

PEM-encoded certificate request.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/locally_signed_cert.html#cert_request_pem LocallySignedCert#cert_request_pem}

---

##### `validityPeriodHours`<sup>Required</sup> <a name="@cdktf/provider-tls.LocallySignedCertConfig.property.validityPeriodHours"></a>

```typescript
public readonly validityPeriodHours: number;
```

- *Type:* `number`

Number of hours that the certificate will remain valid for.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/locally_signed_cert.html#validity_period_hours LocallySignedCert#validity_period_hours}

---

##### `earlyRenewalHours`<sup>Optional</sup> <a name="@cdktf/provider-tls.LocallySignedCertConfig.property.earlyRenewalHours"></a>

```typescript
public readonly earlyRenewalHours: number;
```

- *Type:* `number`

Number of hours before the certificates expiry when a new certificate will be generated.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/locally_signed_cert.html#early_renewal_hours LocallySignedCert#early_renewal_hours}

---

##### `isCaCertificate`<sup>Optional</sup> <a name="@cdktf/provider-tls.LocallySignedCertConfig.property.isCaCertificate"></a>

```typescript
public readonly isCaCertificate: boolean | IResolvable;
```

- *Type:* `boolean` | [`cdktf.IResolvable`](#cdktf.IResolvable)

Whether the generated certificate will be usable as a CA certificate.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/locally_signed_cert.html#is_ca_certificate LocallySignedCert#is_ca_certificate}

---

##### `setSubjectKeyId`<sup>Optional</sup> <a name="@cdktf/provider-tls.LocallySignedCertConfig.property.setSubjectKeyId"></a>

```typescript
public readonly setSubjectKeyId: boolean | IResolvable;
```

- *Type:* `boolean` | [`cdktf.IResolvable`](#cdktf.IResolvable)

If true, the generated certificate will include a subject key identifier.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/locally_signed_cert.html#set_subject_key_id LocallySignedCert#set_subject_key_id}

---

### PrivateKeyConfig <a name="@cdktf/provider-tls.PrivateKeyConfig"></a>

#### Initializer <a name="[object Object].Initializer"></a>

```typescript
import { PrivateKeyConfig } from '@cdktf/provider-tls'

const privateKeyConfig: PrivateKeyConfig = { ... }
```

##### `count`<sup>Optional</sup> <a name="@cdktf/provider-tls.PrivateKeyConfig.property.count"></a>

```typescript
public readonly count: number | IResolvable;
```

- *Type:* `number` | [`cdktf.IResolvable`](#cdktf.IResolvable)

---

##### `dependsOn`<sup>Optional</sup> <a name="@cdktf/provider-tls.PrivateKeyConfig.property.dependsOn"></a>

```typescript
public readonly dependsOn: ITerraformDependable[];
```

- *Type:* [`cdktf.ITerraformDependable`](#cdktf.ITerraformDependable)[]

---

##### `lifecycle`<sup>Optional</sup> <a name="@cdktf/provider-tls.PrivateKeyConfig.property.lifecycle"></a>

```typescript
public readonly lifecycle: TerraformResourceLifecycle;
```

- *Type:* [`cdktf.TerraformResourceLifecycle`](#cdktf.TerraformResourceLifecycle)

---

##### `provider`<sup>Optional</sup> <a name="@cdktf/provider-tls.PrivateKeyConfig.property.provider"></a>

```typescript
public readonly provider: TerraformProvider;
```

- *Type:* [`cdktf.TerraformProvider`](#cdktf.TerraformProvider)

---

##### `algorithm`<sup>Required</sup> <a name="@cdktf/provider-tls.PrivateKeyConfig.property.algorithm"></a>

```typescript
public readonly algorithm: string;
```

- *Type:* `string`

Name of the algorithm to use to generate the private key.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/private_key.html#algorithm PrivateKey#algorithm}

---

##### `ecdsaCurve`<sup>Optional</sup> <a name="@cdktf/provider-tls.PrivateKeyConfig.property.ecdsaCurve"></a>

```typescript
public readonly ecdsaCurve: string;
```

- *Type:* `string`

ECDSA curve to use when generating a key.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/private_key.html#ecdsa_curve PrivateKey#ecdsa_curve}

---

##### `rsaBits`<sup>Optional</sup> <a name="@cdktf/provider-tls.PrivateKeyConfig.property.rsaBits"></a>

```typescript
public readonly rsaBits: number;
```

- *Type:* `number`

Number of bits to use when generating an RSA key.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/private_key.html#rsa_bits PrivateKey#rsa_bits}

---

### SelfSignedCertConfig <a name="@cdktf/provider-tls.SelfSignedCertConfig"></a>

#### Initializer <a name="[object Object].Initializer"></a>

```typescript
import { SelfSignedCertConfig } from '@cdktf/provider-tls'

const selfSignedCertConfig: SelfSignedCertConfig = { ... }
```

##### `count`<sup>Optional</sup> <a name="@cdktf/provider-tls.SelfSignedCertConfig.property.count"></a>

```typescript
public readonly count: number | IResolvable;
```

- *Type:* `number` | [`cdktf.IResolvable`](#cdktf.IResolvable)

---

##### `dependsOn`<sup>Optional</sup> <a name="@cdktf/provider-tls.SelfSignedCertConfig.property.dependsOn"></a>

```typescript
public readonly dependsOn: ITerraformDependable[];
```

- *Type:* [`cdktf.ITerraformDependable`](#cdktf.ITerraformDependable)[]

---

##### `lifecycle`<sup>Optional</sup> <a name="@cdktf/provider-tls.SelfSignedCertConfig.property.lifecycle"></a>

```typescript
public readonly lifecycle: TerraformResourceLifecycle;
```

- *Type:* [`cdktf.TerraformResourceLifecycle`](#cdktf.TerraformResourceLifecycle)

---

##### `provider`<sup>Optional</sup> <a name="@cdktf/provider-tls.SelfSignedCertConfig.property.provider"></a>

```typescript
public readonly provider: TerraformProvider;
```

- *Type:* [`cdktf.TerraformProvider`](#cdktf.TerraformProvider)

---

##### `allowedUses`<sup>Required</sup> <a name="@cdktf/provider-tls.SelfSignedCertConfig.property.allowedUses"></a>

```typescript
public readonly allowedUses: string[];
```

- *Type:* `string`[]

Uses that are allowed for the certificate.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/self_signed_cert.html#allowed_uses SelfSignedCert#allowed_uses}

---

##### `keyAlgorithm`<sup>Required</sup> <a name="@cdktf/provider-tls.SelfSignedCertConfig.property.keyAlgorithm"></a>

```typescript
public readonly keyAlgorithm: string;
```

- *Type:* `string`

Name of the algorithm to use to generate the certificate's private key.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/self_signed_cert.html#key_algorithm SelfSignedCert#key_algorithm}

---

##### `privateKeyPem`<sup>Required</sup> <a name="@cdktf/provider-tls.SelfSignedCertConfig.property.privateKeyPem"></a>

```typescript
public readonly privateKeyPem: string;
```

- *Type:* `string`

PEM-encoded private key that the certificate will belong to.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/self_signed_cert.html#private_key_pem SelfSignedCert#private_key_pem}

---

##### `subject`<sup>Required</sup> <a name="@cdktf/provider-tls.SelfSignedCertConfig.property.subject"></a>

```typescript
public readonly subject: SelfSignedCertSubject[];
```

- *Type:* [`@cdktf/provider-tls.SelfSignedCertSubject`](#@cdktf/provider-tls.SelfSignedCertSubject)[]

subject block.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/self_signed_cert.html#subject SelfSignedCert#subject}

---

##### `validityPeriodHours`<sup>Required</sup> <a name="@cdktf/provider-tls.SelfSignedCertConfig.property.validityPeriodHours"></a>

```typescript
public readonly validityPeriodHours: number;
```

- *Type:* `number`

Number of hours that the certificate will remain valid for.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/self_signed_cert.html#validity_period_hours SelfSignedCert#validity_period_hours}

---

##### `dnsNames`<sup>Optional</sup> <a name="@cdktf/provider-tls.SelfSignedCertConfig.property.dnsNames"></a>

```typescript
public readonly dnsNames: string[];
```

- *Type:* `string`[]

List of DNS names to use as subjects of the certificate.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/self_signed_cert.html#dns_names SelfSignedCert#dns_names}

---

##### `earlyRenewalHours`<sup>Optional</sup> <a name="@cdktf/provider-tls.SelfSignedCertConfig.property.earlyRenewalHours"></a>

```typescript
public readonly earlyRenewalHours: number;
```

- *Type:* `number`

Number of hours before the certificates expiry when a new certificate will be generated.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/self_signed_cert.html#early_renewal_hours SelfSignedCert#early_renewal_hours}

---

##### `ipAddresses`<sup>Optional</sup> <a name="@cdktf/provider-tls.SelfSignedCertConfig.property.ipAddresses"></a>

```typescript
public readonly ipAddresses: string[];
```

- *Type:* `string`[]

List of IP addresses to use as subjects of the certificate.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/self_signed_cert.html#ip_addresses SelfSignedCert#ip_addresses}

---

##### `isCaCertificate`<sup>Optional</sup> <a name="@cdktf/provider-tls.SelfSignedCertConfig.property.isCaCertificate"></a>

```typescript
public readonly isCaCertificate: boolean | IResolvable;
```

- *Type:* `boolean` | [`cdktf.IResolvable`](#cdktf.IResolvable)

Whether the generated certificate will be usable as a CA certificate.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/self_signed_cert.html#is_ca_certificate SelfSignedCert#is_ca_certificate}

---

##### `setSubjectKeyId`<sup>Optional</sup> <a name="@cdktf/provider-tls.SelfSignedCertConfig.property.setSubjectKeyId"></a>

```typescript
public readonly setSubjectKeyId: boolean | IResolvable;
```

- *Type:* `boolean` | [`cdktf.IResolvable`](#cdktf.IResolvable)

If true, the generated certificate will include a subject key identifier.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/self_signed_cert.html#set_subject_key_id SelfSignedCert#set_subject_key_id}

---

##### `uris`<sup>Optional</sup> <a name="@cdktf/provider-tls.SelfSignedCertConfig.property.uris"></a>

```typescript
public readonly uris: string[];
```

- *Type:* `string`[]

List of URIs to use as subjects of the certificate.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/self_signed_cert.html#uris SelfSignedCert#uris}

---

### SelfSignedCertSubject <a name="@cdktf/provider-tls.SelfSignedCertSubject"></a>

#### Initializer <a name="[object Object].Initializer"></a>

```typescript
import { SelfSignedCertSubject } from '@cdktf/provider-tls'

const selfSignedCertSubject: SelfSignedCertSubject = { ... }
```

##### `commonName`<sup>Optional</sup> <a name="@cdktf/provider-tls.SelfSignedCertSubject.property.commonName"></a>

```typescript
public readonly commonName: string;
```

- *Type:* `string`

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/self_signed_cert.html#common_name SelfSignedCert#common_name}.

---

##### `country`<sup>Optional</sup> <a name="@cdktf/provider-tls.SelfSignedCertSubject.property.country"></a>

```typescript
public readonly country: string;
```

- *Type:* `string`

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/self_signed_cert.html#country SelfSignedCert#country}.

---

##### `locality`<sup>Optional</sup> <a name="@cdktf/provider-tls.SelfSignedCertSubject.property.locality"></a>

```typescript
public readonly locality: string;
```

- *Type:* `string`

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/self_signed_cert.html#locality SelfSignedCert#locality}.

---

##### `organization`<sup>Optional</sup> <a name="@cdktf/provider-tls.SelfSignedCertSubject.property.organization"></a>

```typescript
public readonly organization: string;
```

- *Type:* `string`

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/self_signed_cert.html#organization SelfSignedCert#organization}.

---

##### `organizationalUnit`<sup>Optional</sup> <a name="@cdktf/provider-tls.SelfSignedCertSubject.property.organizationalUnit"></a>

```typescript
public readonly organizationalUnit: string;
```

- *Type:* `string`

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/self_signed_cert.html#organizational_unit SelfSignedCert#organizational_unit}.

---

##### `postalCode`<sup>Optional</sup> <a name="@cdktf/provider-tls.SelfSignedCertSubject.property.postalCode"></a>

```typescript
public readonly postalCode: string;
```

- *Type:* `string`

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/self_signed_cert.html#postal_code SelfSignedCert#postal_code}.

---

##### `province`<sup>Optional</sup> <a name="@cdktf/provider-tls.SelfSignedCertSubject.property.province"></a>

```typescript
public readonly province: string;
```

- *Type:* `string`

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/self_signed_cert.html#province SelfSignedCert#province}.

---

##### `serialNumber`<sup>Optional</sup> <a name="@cdktf/provider-tls.SelfSignedCertSubject.property.serialNumber"></a>

```typescript
public readonly serialNumber: string;
```

- *Type:* `string`

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/self_signed_cert.html#serial_number SelfSignedCert#serial_number}.

---

##### `streetAddress`<sup>Optional</sup> <a name="@cdktf/provider-tls.SelfSignedCertSubject.property.streetAddress"></a>

```typescript
public readonly streetAddress: string[];
```

- *Type:* `string`[]

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls/r/self_signed_cert.html#street_address SelfSignedCert#street_address}.

---

### TlsProviderConfig <a name="@cdktf/provider-tls.TlsProviderConfig"></a>

#### Initializer <a name="[object Object].Initializer"></a>

```typescript
import { TlsProviderConfig } from '@cdktf/provider-tls'

const tlsProviderConfig: TlsProviderConfig = { ... }
```

##### `alias`<sup>Optional</sup> <a name="@cdktf/provider-tls.TlsProviderConfig.property.alias"></a>

```typescript
public readonly alias: string;
```

- *Type:* `string`

Alias name.

Docs at Terraform Registry: {@link https://www.terraform.io/docs/providers/tls#alias TlsProvider#alias}

---

## Classes <a name="Classes"></a>

### DataTlsCertificateCertificates <a name="@cdktf/provider-tls.DataTlsCertificateCertificates"></a>

#### Initializers <a name="@cdktf/provider-tls.DataTlsCertificateCertificates.Initializer"></a>

```typescript
import { DataTlsCertificateCertificates } from '@cdktf/provider-tls'

new DataTlsCertificateCertificates(terraformResource: ITerraformResource, terraformAttribute: string, complexComputedListIndex: string)
```

##### `terraformResource`<sup>Required</sup> <a name="@cdktf/provider-tls.DataTlsCertificateCertificates.parameter.terraformResource"></a>

- *Type:* [`cdktf.ITerraformResource`](#cdktf.ITerraformResource)

---

##### `terraformAttribute`<sup>Required</sup> <a name="@cdktf/provider-tls.DataTlsCertificateCertificates.parameter.terraformAttribute"></a>

- *Type:* `string`

---

##### `complexComputedListIndex`<sup>Required</sup> <a name="@cdktf/provider-tls.DataTlsCertificateCertificates.parameter.complexComputedListIndex"></a>

- *Type:* `string`

---



#### Properties <a name="Properties"></a>

##### `isCa`<sup>Required</sup> <a name="@cdktf/provider-tls.DataTlsCertificateCertificates.property.isCa"></a>

```typescript
public readonly isCa: any;
```

- *Type:* `any`

---

##### `issuer`<sup>Required</sup> <a name="@cdktf/provider-tls.DataTlsCertificateCertificates.property.issuer"></a>

```typescript
public readonly issuer: string;
```

- *Type:* `string`

---

##### `notAfter`<sup>Required</sup> <a name="@cdktf/provider-tls.DataTlsCertificateCertificates.property.notAfter"></a>

```typescript
public readonly notAfter: string;
```

- *Type:* `string`

---

##### `notBefore`<sup>Required</sup> <a name="@cdktf/provider-tls.DataTlsCertificateCertificates.property.notBefore"></a>

```typescript
public readonly notBefore: string;
```

- *Type:* `string`

---

##### `publicKeyAlgorithm`<sup>Required</sup> <a name="@cdktf/provider-tls.DataTlsCertificateCertificates.property.publicKeyAlgorithm"></a>

```typescript
public readonly publicKeyAlgorithm: string;
```

- *Type:* `string`

---

##### `serialNumber`<sup>Required</sup> <a name="@cdktf/provider-tls.DataTlsCertificateCertificates.property.serialNumber"></a>

```typescript
public readonly serialNumber: string;
```

- *Type:* `string`

---

##### `sha1Fingerprint`<sup>Required</sup> <a name="@cdktf/provider-tls.DataTlsCertificateCertificates.property.sha1Fingerprint"></a>

```typescript
public readonly sha1Fingerprint: string;
```

- *Type:* `string`

---

##### `signatureAlgorithm`<sup>Required</sup> <a name="@cdktf/provider-tls.DataTlsCertificateCertificates.property.signatureAlgorithm"></a>

```typescript
public readonly signatureAlgorithm: string;
```

- *Type:* `string`

---

##### `subject`<sup>Required</sup> <a name="@cdktf/provider-tls.DataTlsCertificateCertificates.property.subject"></a>

```typescript
public readonly subject: string;
```

- *Type:* `string`

---

##### `version`<sup>Required</sup> <a name="@cdktf/provider-tls.DataTlsCertificateCertificates.property.version"></a>

```typescript
public readonly version: number;
```

- *Type:* `number`

---



